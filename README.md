This is achieved using the following code snippet:

     mkdir openwrt
     cd openwrt
     svn co svn://svn.openwrt.org/openwrt/trunk aYYar
     git clone https://github.com/ayyaris/ayyar.git
     cd aYYar
     patch -p0 <../ayyar/Openwrt-rt5350-ayyari.patch
     make menuconfig
