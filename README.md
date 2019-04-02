# TWRP Tree for Coolpad Cool 1 (C106)
==============

The Coolpad Cool 1 (C106) is a smartphone from LeEco and Coolpad.

Device Configuration for C106
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | Qualcomm MSM8976 Snapdragon 652
CPU     | Quad-core 1.8 GHz Cortex-A72 & Quad-core 1.4 GHz Cortex-A53
GPU     | Adreno 510
Memory/RAM  | 3 GB or 4 GB 
Storage | 32 GB or 64 GB
Battery | 4000 mAh (Non-Removable)
Dimensions | 152 x 74.8 x 8.2 mm
Display | 1080 x 1920 pixels 5.5"
Rear Camera  | 13.0 MP + 13.0 MP
Front Camera | 8.0 MP
Release Date | August 2016


To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

        repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0

Then to sync up:

        $ repo sync

Full Compilation
	
		$ export ALLOW_MISSING_DEPENDENCIES=true
		
		$ source build/envsetup.sh
		
        $ lunch omni_C106-userdebug

        $ make clean
        
        $ mka recoveryimage

	

