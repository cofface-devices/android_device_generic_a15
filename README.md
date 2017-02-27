## TWRP device tree for Huawei Mate 9

```
repo init -u https://github.com/omnirom/android.git -b android-7.1
TWRP: 6.0 branch
xda link:https://forum.xda-developers.com/mate-9/development/recovery-unofficial-twrp-huawei-mate-9-t3515617
```

Then run `repo sync` to check it out.

To build:

```sh
. build/envsetup.sh
lunch omni_generic_a15-eng && mka recoveryimage
```

