----------------
Kernel thread :
----------------

-

* latest version : 

----------------
Build commands :
----------------

// (old) - android-ndk

export CROSS_COMPILE=~/toolchains/arm-eabi-4.4.3/prebuilt/linux-x86/bin/arm-eabi-
----------------

// (new) - Linaro 2012.03

export CROSS_COMPILE=~/gcc-linaro-arm-linux-gnueabi-2012.04-20120426_linux/bin/arm-linux-gnueabi-
----------------

make adridu59_hallon_defconfig

make
