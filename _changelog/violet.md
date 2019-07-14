---
codename:violet
---

=====================
    13/07/2019
=====================

Device Side Changes
- Parts: Migrate to androidx
- Add QPerformance and UxPerformance jars
- Compile kernel with clang 9.0.5
- Camera: Hack focus modes
- Add missing media blobs
- Import media properties XML from LA.UM.7.9.r1-07500-sm6150.0
- Update gps config from caf
- Build some soundfx from source
- Bring back WMA
- Restore stock bluetooth HAL

ROM Side Changes:
- July Security Patches

=====================
    01/07/2019
=====================

Device Side Changes
- Update blobs to MIUI 9.6.27
- Drop goodix firmware
- Update Build fingerprint to V10.3.9.0
- Enable OEM unlocking option
- Add Vector icons to Xiaomi Parts
- Update rootdir/configs from caf
- Drop prebuilt media HAL
- Partially  build display HAL
- Force VoLTE on supported carriers
- Update GPS HAL to  LA.UM.7.9.r1-07300-sm6150.0
- Enable 4k recording on front cam
- Use Studio Thermal Profile for camera
- Address Camera lags
- Improved signal reception
- Build context hub / qti camera device
- Add Dirac Sound Control

=====================
    13/06/2019
=====================

NOTE:- Before doing an OTA you need to read https://t.me/keepthebootlegviolet/626

Device Side Stuff
* Rebased to GuaiYiHu's Trees
* Vendor is now built inline
* Blobs updated from Redmi K20
* Supports proper System as Root mounting
* Other changes

ROM Side Stuff
* ROM version bump to 4.2
* Added translations
* Fixed emergency icon tinting, credits to PE
* Rebased telephony repos
* Lockscreen date styles
* Shishu Themes now have LIT instead of LTE
* Added Q clock with extra changes for date and owner
* Aggresive Battery
* Custom fingerprint icons for OP devices
* Fixed Markup building for all devices
* Added Q seekbar with a small ui change
* Added improvements for 3 finger screenshot
* Re-introduced Woodman due to devices bootlooping
* One Hand UI
* Pixel Navbar animation
* Some extra undocumented kanging for legal reasons
* Added some new QS styles
* Fixes and improvements
* Launcher3 now has the window to icon animations, and also, fixed dark google feed
* Revert: Revert: [DO NOT MERGE] Partial Revert of john woodman

=====================
    12/05/2019
=====================

Device Side Stuff
* Updated panel FW (fixes touch delay) thanks to @TheScarastic
* Included dtbo

ROM Side Stuff
* Enabled Notch city from POSP
* Source upstream

=====================
    10/05/2019
=====================

NOTE: You have to flash stock vendor image from miui and fcrypt disabler zip before OTA or seeya bois in fastboot. Check @keepthebootlegviolet for more details

Device Side Stuff
* Added VDSO
* Fixed IR Blaster
* Fixed D2TW not working in some cases
* Fixed notification led not working in some cases
* Updated power hal

ROM Side Stuff
* Merged May Security Patches

=====================
    03/05/2019
=====================

* Actually fix Preferred Network FC.

=====================
    03/05/2019
=====================

* Intial Build
* Preferred Network FC has been fixed
