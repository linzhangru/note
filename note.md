##1. XMAKE

build command:
-------------------------------------------
cd prebuilts/tools;
./ctnr_image_reuse.sh SC9832_M-5.5.0-E-20161124.0907 eng;
./configure --with-platform=phone --with-product=sc9832_m --with-buildtype=userdebug --with-board=sprd --enable-closed-source --with-permission=yes
source xdirs
xmake
xmake image-stripped

so there are 2 main points about build:
   1. ctnr_image_reuse.sh
   2. xmake

###1. ctnr_image_reuse.sh
###2. xmake







##2. init/systemd/Superstart
##3. dbus mechanism
##4. mount bind/chroot/rootfs
##5. libhybris/function mapping
##6. 
