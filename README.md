This is achieved using the following code snippet:

     svn co svn://svn.openwrt.org/openwrt/trunk AYYAR
     cd AYYAR
     git clone https://github.com/ayyaris/ayyar.git
     patch -p0 < ayyar/Openwrt-rt5350-ayyari.patch
     patch -p0 < ayyar/Openwrt-add-AYYAR-dts.patch
     ./scripts/feeds update -a
     ./scripts/feeds install luci -p
