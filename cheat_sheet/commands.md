
## Additional Gstreamer commands
1. [GStreamer command-line cheat sheet](https://github.com/matthew1000/gstreamer-cheat-sheet)
2. [Gstreamer cheat sheet (Wiki)](http://wiki.oz9aec.net/index.php/Gstreamer_cheat_sheet)


## Mixing

- How to mix two test streams (**videobox**, **videomixer**)

      gst-launch-1.0 videomixer name=mixer ! gtksink \
      videotestsrc ! videoscale ! video/x-raw,width=960,height=540 ! \
      tee name=t !  queue ! videoconvert ! videobox left=-960 ! videoconvert ! mixer. \
      t. ! queue ! videobox left=0  ! videoconvert ! mixer.
      
## Networking

### TCP

#### Test stream (videotestsrc)

- send

      gst-launch-1.0 videotestsrc ! videoscale ! video/x-raw,width=100,height=100 ! \
      x264enc tune="zerolatency" ! mpegtsmux ! tcpserversink host=127.0.0.1 port=5000
    
- receive

      gst-launch-1.0 tcpclientsrc port=5000 host=127.0.0.1 ! tsdemux ! \
      h264parse ! avdec_h264 ! videoconvert ! gtksink


#### From webcamera (v4l2src)

- send 

      gst-launch-1.0 v4l2src ! jpegenc ! tcpserversink host=localhost port=5000
    
- receive

      gst-launch-1.0 tcpclientsrc port=5000 ! jpegdec ! videoconvert ! autovideosink sync=true
