FFmpeg-Android 
==============

A Fork from [ffmpeg-android](https://github.com/hiteshsondhi88/ffmpeg-android) modified to run on Mac

######Note: Some libs are removed from the original repo to fit my project need. 

* FFmpeg for Android compiled with x264
* Supports Android L 

Supported Architecture
----
* armv7
* armv7-neon
* x86

Instructions
----
* Set environment variable
  1. export ANDROID_NDK={Android NDK Base Path}
* Run following commands to compile ffmpeg 
  2. Run `submodule update --init`
  3. ./android_build.sh 
* Find the executable binary in `build` directory. 

License
----
  check files LICENSE.GPLv3 and LICENSE
