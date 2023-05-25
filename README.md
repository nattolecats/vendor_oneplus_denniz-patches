# Evolution X patches for OnePlus Nord 2 5G (denniz)

## General infos

This repository contains all the patches needed for Evolution X on denniz, OnePlus Nord 2 5G.

Contains patches for:

* build_soong
* frameworks_av
* frameworks_base
* frameworks_native
* packages\_modules\_Bluetooth

## Usage

Clone this and create vendorsetup.sh in your tree, then write:
```
source "$ANDROID_BUILD_TOP"/vendor/oneplus/denniz-patches/functions.sh

discardPatches

applyPatches
```
