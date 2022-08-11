# awesome-gstreamer

![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Gstreamer-logo.svg/1200px-Gstreamer-logo.svg.png)

### Official Resources
- [Gstreamer. Website](https://gstreamer.freedesktop.org/)
- [Gstreamer. Plugins](https://gstreamer.freedesktop.org/documentation/plugins_doc.html?gi-language=c)
- [Twitter Account](https://twitter.com/gstreamer)
    - interesting news, links, thoughts 
- [#gstreamer IRC channel](https://freenode.net/)
    - responsive, kind developers that always can help with any question.
- [Gstreamer. Conferences](https://gstconf.ubicast.tv/)
    - videos collected from 2010 to present. There are a lot of useful tricks, fun applications and base knowledges
- [Gstreamer Developers Forum](http://gstreamer-devel.966125.n4.nabble.com/)

### Dependencies
- [GLib. Reference Manual](https://developer.gnome.org/glib/stable/) 
    - Gstreamer is based on Glib principles, so understanding of main GObject and Glib could be very useful.
- [Gnome](https://developer.gnome.org/) 
    - a lot of other libraries that are being used by Gstreamer applications

### Installation
- [Official Guides](https://gstreamer.freedesktop.org/documentation/installing/index.html?gi-language=c)
- [Ubuntu. Installation](http://lifestyletransfer.com/how-to-install-gstreamer-on-ubuntu/)
    - [Docker Containers](https://github.com/jackersson/env-setup)

### Gstreamer Python
- [PyGObject](https://pygobject.readthedocs.io/en/latest/)
- [PyGObject API Reference](https://lazka.github.io/pgi-docs/)
    - [Gst](https://lazka.github.io/pgi-docs/#Gst-1.0)
    - [GstBase](https://lazka.github.io/pgi-docs/#GstBase-1.0)
    - [GstVideo](https://lazka.github.io/pgi-docs/#GstVideo-1.0)
    - [GstApp](https://lazka.github.io/pgi-docs/#GstApp-1.0)
    - [GstRTSP](https://lazka.github.io/pgi-docs/#GstRtsp-1.0)
- Tutorials
    - [How to write Gstreamer plugin with Python?](http://lifestyletransfer.com/how-to-write-gstreamer-plugin-with-python/)
    - [How to launch Gstreamer pipleine from Python](http://lifestyletransfer.com/how-to-launch-gstreamer-pipeline-in-python/)
    - [How to capture buffers from Gstreamer pipelines with AppSink](http://lifestyletransfer.com/how-to-use-gstreamer-appsink-in-python/)
    - [How to push buffers into Gstreamer pipeline with AppSrc](http://lifestyletransfer.com/how-to-use-gstreamer-appsink-in-python/)
    - [How to work with Metadata in Python](http://lifestyletransfer.com/how-to-add-metadata-to-gstreamer-buffer-in-python/)

### Blogs
- [LifeStyleTransfer. Content](http://lifestyletransfer.com/content/)
- [Blog. Igalia](https://blogs.igalia.com/vjaquez/)
- [mathieuduponchelle.github.io](https://mathieuduponchelle.github.io/index.html?gi-language=undefined)
- [Collabora. Blog](https://www.collabora.com/about-us/open-source/open-source-projects/gstreamer.html)
- [RidgeRun. Blog](https://www.ridgerun.com/blog)

### Videos
- [Ridge Run. Youtube Channel](https://www.youtube.com/channel/UCrOCAheHWwCKn5zfO_qShYQ/videos)
- [Collabora. Youtube Channel](https://www.youtube.com/channel/UCPh7R2PWtJHmTfSGWuLkGTg/videos)

### Video Analytics Frameworks based on Gstreamer
- [NNStreamer. Samsung](https://github.com/nnsuite/nnstreamer)
- [Gst-Inference. RidgeRun](https://github.com/RidgeRun/gst-inference)
- [DeepStream SDK. Nvidia](https://developer.nvidia.com/deepstream-sdk)
    - [Github Repository with Awesome Projects](https://github.com/NVIDIA-AI-IOT) 
- [Gst-Video-Analytics. OpenCV](https://github.com/opencv/gst-video-analytics)
- [Overview and Comparison Table for Video Analytics Frameworks](http://lifestyletransfer.com/deep-learning-video-analytics-gstreamer/)

### Useful Gstreamer Pipelines
- [Cheat Sheet](https://github.com/jackersson/awesome-gstreamer/blob/master/cheat_sheet/commands.md) - simples commands to understand basic plugins and to try Gstreamer capabilities.

### Tutorials
- [Tutorials. From official website](https://gstreamer.freedesktop.org/documentation/tutorials/index.html)
- [Hello World](https://gstreamer.freedesktop.org/documentation/tutorials/basic/hello-world.html)
- [Github Examples](https://github.com/GStreamer/gst-docs/tree/master/examples/tutorials)
- [Synchronised multi-room multimedia playback and synchronised live media processing and mixing with G](https://www.youtube.com/watch?v=C7sH4TSc054)
- [Gstreamer for tiny Devices](https://www.youtube.com/watch?v=RE3ylldz-Fs)
- [Gstreamer for mobile platforms](https://gstconf.ubicast.tv/videos/gstreamer-for-mobile-platforms-android-and-ios_/)

#### Plugins
- [Python Plugin Template](https://github.com/qtec/build-qt5022-core/wiki/GStreamer-Advanced#python-element-template)
- [Gstreamer in Python. Intoduction (PDF)](https://brettviren.github.io/pygst-tutorial-org/pygst-tutorial.pdf)
- [Getting started with Gstreamer in Python](https://www.jonobacon.com/2006/08/28/getting-started-with-gstreamer-with-python/)
- [Using Gnonlin with Gstreamer and Python](https://www.jonobacon.com/2006/12/27/using-gnonlin-with-gstreamer-and-python/)
- [Gstreamer dynamic Pads Explained](https://www.jonobacon.com/2006/12/27/using-gnonlin-with-gstreamer-and-python/)
- [Gstreamer Hacks/Tutorials/Projects](http://lifestyletransfer.com/)
- [Building Video Player with Gstreamer on Python](https://medium.com/@Gnaphron/gst-r-eamer-in-a-cockleshell-46236d02a74e)
- [How to write Gstreamer plugins in Python (audio)](https://mathieuduponchelle.github.io/2018-02-01-Python-Elements.html?gi-language=undefined)
- [Proper AppSrc Pipeline Implemetation](https://programtalk.com/vs2/python/543/kaldi-gstreamer-server/kaldigstserver/decoder.py/)

### Awesome projects
- [Gstreamer for Gravitational Waves](https://wiki.ligo.org/Computing/DASWG/GstLAL)
- [Simple DVB with Gstreamer and GNU Radio](http://wiki.oz9aec.net/index.php/Simple_DVB_with_Gstreamer_and_GNU_Radio)
- [My GStreamer-Enabled Home](https://gstconf.ubicast.tv/videos/my-gstreamer-enabled-home/#slide)
- [GStreamer in the living room and in outer space](https://www.youtube.com/watch?v=DRBzCASAm3g)
- [GStreamer is in the air](https://gstconf.ubicast.tv/videos/gstreamer-is-in-the-air/#slide)

### Edge Platforms
- [Google Coral TPU. Gstreamer Pipelines](https://github.com/google-coral/examples-camera/tree/master/gstreamer)
- [Nvidia Jetson, Gstreamer Pipelines](https://developer.download.nvidia.com/embedded/L4T/r32_Release_v1.0/Docs/Accelerated_GStreamer_User_Guide.pdf?i_Y2wpVYeC4aKDkehQNi7nZijaqPu-zUqO228keXSjtyD_7FHVxEAYFmYhzbmT-MgdoAimuP1FuS62KQPIADER2TQ0BaCa0MJNpQLjDYzEzqhZtQEKo6q2RiyXtc4vhbHiUxfvJ8mfLS8Sn-_USkttoqhaLmk5Epe_--Sh4rapNOZ-lHYq8)

### Hardware-Accelerated Video Processing
- [Accelerated Gstreamer Guide. Nvidia](https://developer.download.nvidia.com/embedded/L4T/r32_Release_v1.0/Docs/Accelerated_GStreamer_User_Guide.pdf?i_Y2wpVYeC4aKDkehQNi7nZijaqPu-zUqO228keXSjtyD_7FHVxEAYFmYhzbmT-MgdoAimuP1FuS62KQPIADER2TQ0BaCa0MJNpQLjDYzEzqhZtQEKo6q2RiyXtc4vhbHiUxfvJ8mfLS8Sn-_USkttoqhaLmk5Epe_--Sh4rapNOZ-lHYq8)


### How to
- [How to loop video?](https://gist.github.com/jackersson/7c476f6293cb74ff0d97101304a005c0)

### Companies
- [Samsung]()
- [Nvidia](https://developer.nvidia.com/deepstream-sdk)
- [RidgeRun](https://www.ridgerun.com/)
- [Collabora](https://www.collabora.com/)
- [Igalia](https://www.igalia.com/)
