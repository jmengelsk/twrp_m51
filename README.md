# TWRP Tree for Samsung Galaxy M51

### How to build
This was tested and it's fully compatible with [minimal manifest twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp).
1. Set up the build environment following instructions from [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-11/README.md#getting-started)
2. Clone device tree:
```bash
git clone -b android-12.1 https://github.com/jmengelsk/twrp_m51.git device/samsung/m51
```
3. To build:
```bash
export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch twrp_M51q-eng && mka recoveryimage
```

### Credits
* DarthJabba9
* travarilo
* hendramanu

### Links
* [Kernel source](https://github.com/jmengelsk/android_kernel_samsung_sm7125/tree/twrp)
