undefined-reference-to--accept4---Fedora
========================================

qnativesocketengine_unix.cpp:(.text+0x674): undefined reference to `accept4' .obj/release-shared-emb-arm/qlocalserver_unix.o: In function `QLocalServerPrivate::_q_onNewConnection()': qlocalserver_unix.cpp:(.text+0x6f8): undefined reference to `accept4' collect2: ld returned 1 exit status make[1]: *** [../../lib/libQtNetwork.so.4.6.3] Error 1 make[1]: Leaving directory `/opt/FriendlyARM/mini2440/arm-qte-4.6.3/qt-everywhere-opensource-src-4.6.3/src/network' make: *** [sub-network-make_default-ordered] Error 2 
