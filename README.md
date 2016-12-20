# Device Tree for LeEco Le 2 (s2)
==============

The LeEco Le 2 (s2) is a smartphone from LeEco or LeMobile Information Technology Co. Ltd.

Device Configuration for s2
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | Qualcomm MSM8976 Snapdragon 652
CPU     | Quad-core 1.8 GHz Cortex-A72 & Quad-core 1.4 GHz Cortex-A53
GPU     | Adreno 510
Memory/RAM  | 3 GB
Storage | 32 GB
Battery | 3000 mAh (Non-Removable)
Dimensions | 151.1 x 74.2 x 7.5 mm
Display | 1080 x 1920 pixels 5.5"
Rear Camera  | 16.0 MP
Front Camera | 8.0 MP
Release Date | June 2016

![LeEco Le 2](http://in.img3.lemall.com/file/20160606/default/3370481864506311 "LeEco Le 2")

To initialize your local repository using the CyanogenMod 13 trees, use a command like this:

        $ repo init -u git://github.com/CyanogenMod/android.git -b cm-13.0

Then to sync up:

        $ repo sync

Download s2 Device Trees:

        $ git clone https://github.com/s2-devs/android_device_leeco_s2.git -b cm-13.0

Full Compilation
        
        $ source build/envsetup.sh

        $ lunch cm_s2-userdebug
        
        $ make clean && make -j8
