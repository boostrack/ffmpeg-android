FFmpeg-Android (http://stackoverflow.com/questions/27832052/how-do-i-modify-this-ffmpeg-build-script-for-minimal-binary-size-output) 
==============

A Fork from [ffmpeg-android](https://github.com/hiteshsondhi88/ffmpeg-android) modified to run on Mac

######Note: Some libs are removed from the original repo to fit my project needs. 

* FFmpeg for Android compiled with x264
* Supports Android 5 (Lollipop) 
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
2. Set environment variable (add your Android NDK path) `export ANDROID_NDK={Android NDK Base Path}`
2. Run following commands to compile ffmpeg 
  1. `git submodule update --init`
  2. `./android_build.sh` 
3. Find the executable binary in `build` directory. 

License
----
  check files LICENSE.GPLv3 and LICENSE
