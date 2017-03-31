# android_device_nubia_nx529j-cwm
Build CWM Recovery V6.0.5.1 for Nubia NX529J（Z11 mini）

========================================================

source build/envsetup.sh

make -j4 otatools

lunch cm_nx529j-userdebug

make -j4 recoveryimage

========================================================
