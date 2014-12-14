FFmpeg-Android 
==============

A Fork from [ffmpeg-android](https://github.com/hiteshsondhi88/ffmpeg-android) modified to run on Mac

######Note: Some libs are removed from the original repo to fit my project need. 

* FFmpeg for Android compiled with x264
* Supports Android L 
* Tested on `Mac OS X Yosemite` and using Android NDK `android-ndk-r10d`. 

Supported Architecture
----
* armv7
* armv7-neon
* x86

Instructions
----
1. Clone the repo: `git clone https://github.com/falnatsheh/ffmpeg-android.git`
2. Navigate to the repo file: `cd ffmpeg-android`
2. Set environment variable `export ANDROID_NDK={Android NDK Base Path}`
2. Run following commands to compile ffmpeg 
  1. `git submodule update --init`
  2. `./android_build.sh` 
3. Find the executable binary in `build` directory. 

License
----
  check files LICENSE.GPLv3 and LICENSE
