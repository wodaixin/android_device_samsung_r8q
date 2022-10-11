# Android device tree for samsung SM-G7810 (r8q)

## How To Compile It:

    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_r8q-eng

The build target is dependent on the device, and should reflect the location of stock recovery on the device. Issue the build command that applies to your device:

- Recovery partition: `mka recoveryimage`
- Boot image ramdisk: `mka bootimage`
- Vendor_boot image ramdisk: `mka vendorbootimage`

```
#
# Copyright (C) 2022 The Android Open Source Project
# Copyright (C) 2022 SebaUbuntu's TWRP device tree generator
#
# SPDX-License-Identifier: Apache-2.0
#
```
