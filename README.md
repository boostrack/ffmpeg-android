FFmpeg-Android 
==============

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
  1. Run the following commands (you need [Homebrew](http://brew.sh/)):
  		 `brew Install autoconf libtool pkg-config gettext yasm wget`
  2. ./init_update_libs.sh
  3. ./android_build.sh
* To update submodules and libraries you can use ./init_update_libs.sh command
* Find the executable binary in `build` directory. 

License
----
  check files LICENSE.GPLv3 and LICENSE
