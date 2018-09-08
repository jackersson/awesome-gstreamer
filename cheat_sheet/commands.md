
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
