**This device tree can be used to build twrp for SDM632 QRD**

## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
source build/envsetup.sh
lunch omni_qrdsdm632-eng
mka recoveryimage
```
