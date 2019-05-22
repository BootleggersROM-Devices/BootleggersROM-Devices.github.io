---
codename:potter 
---

==============
   14/04/19
==============
Device Side Stuff
* SHISHIFIED
* Updated post-boot script for better memory management
* Updated IMMENSITY Kernel
* Merged branch "android-3.18" of  https://android.googlesource.com/kernel/common.git/
* Compiled with new optimization Flags
* Fix Reboot When Changing I/O & Screen Off
* Added New Display Wakeup Tweaks
* Enabled ULPS on All Displays [ forgot to add in last build]
* Readded KLAPSE
* Updated CPU_INPUT_BOOST
* Tuned FingerPrint Driver for Faster Response
* Tuned synaptics touchscreen driver for Faster Response
* added Neon Accelerated XOR crypto algorithm
* Some under the Hood Memory Optimizations
* Added powersave bias on cpufreq interactive
* Converted cpufreq interactive to use statenotifier instead of display_state
* wcd9xxx added support for 44.1Khz sample rate
* Optimized msm KGSl for GPU processing
* fsync disabled by default

ROM Side Stuff

CLEAN FLASH PLS

=====================
    22/05/2019
=====================

* May Security Patch.
* added CAF binderised PowerHAL.
* added Dirac Support.
* added Dirac QS tile.
* updated MotoActions with dirac settings.
* switch to IMMENSITY-CAF kernel
* Fixed MiFare NFC.
* Updated configs from stock.
