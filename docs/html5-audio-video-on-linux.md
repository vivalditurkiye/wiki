**HTML5 Proprietary Audio and Video on Linux**


HTML5 “proprietary” audio and video includes all media types that are patented, such as MP4 (H.264/AAC). Under Linux, Vivaldi requires a suitable, third-party library to play these.

**Ubuntu Installation**

If you use Ubuntu, you can install a suitable package as follows:

1. Start a “Terminal”
2. Issue the following command:
sudo apt update && sudo apt install chromium-codecs-ffmpeg-extra
3. Restart Vivaldi

----

This is primarily written for guide for Vivaldi stable. If you are running Vivaldi snapshots and continue to encounter issues please [read this](https://vivaldi.com/blog/snapshots/understanding-video-issues-with-vivaldi-for-linux-snapshots/).

----

Testing
You can then test video support on [this page](http://www.quirksmode.org/html5/tests/video.html) and audio support on [this page](https://hpr.dogphilosophy.net/test/).

Alternative installation options
A more complete guide, with options for other distros, can be found [here](https://gist.github.com/ruario/bec42d156d30affef655). If you are using a Raspberry Pi, refer to [the relevant section of the Raspberry Pi tips page](https://help.vivaldi.com/article/raspberry-pi/#proprietary-media).

Websites using Encrypted Media Extensions
To use DRM protected media services like Netflix, HBO and Amazon Prime, you will also need to ensure that the [Widevine library](https://help.vivaldi.com/article/netflix-on-linux/) is installed.
