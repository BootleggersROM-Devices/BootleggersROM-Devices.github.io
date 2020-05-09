---
codename:oneplus3
---

Bootleggers:
====================
     2020-05-09
====================


 * external/bash
b330f71 bashrc: Add `ll` alias

====================
     2020-05-08
====================


 * packages/apps/SimIcons
d4012a3 Make whatsapp adaptive

====================
     2020-05-07
====================


 * packages/apps/SimIcons
b9ec1f7 Merge branch 'master' of https://github.com/simrat39/icon-pack
7402801 Improve? settings icon
ab868af Merge pull request #2 from simrat39/dependabot/gradle/com.android.support.test-runner-1.0.2
dc53fa6 build(deps): bump runner from 1.0.1 to 1.0.2
e348702 Merge pull request #1 from simrat39/dependabot/gradle/com.android.support.test.espresso-espresso-core-3.0.2
05dbf45 Merge pull request #4 from simrat39/dependabot/gradle/junit-junit-4.13
70eaecc Merge pull request #5 from simrat39/dependabot/gradle/com.android.tools.build-gradle-3.6.3
0aa76b1 build(deps): bump gradle from 3.3.2 to 3.6.3
205c92e Make settings adaptive

====================
     2020-05-06
====================


 * frameworks/base
3556d6dc2ec Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/frameworks/base into HEAD

 * system/core
80570ea16 adb: Also check for ALLOW_ADBD_ROOT
025ba2681 Make adb use a custom prop for adb root
a181c29f0 Add adb_root daemon and hooks
0fbd270d0 adb: support wait-for- with multiple states.
8a783dd3f libbase: add ConsumePrefix/ConsumeSuffix.
2089efecf adb: fix double close in wait-for-*.
56575bc4f Revert "adb: Add wait-for-online command"
7c975a267 fastbootd: hacks for legacy
1b28eb164 fastbootd: usb: fallback to v1 descriptors
e81e7ee02 reboot: allow opting-in to fastbootd
753a9ca2e fs_mgr: autodetect filesystem type
2f4b77f14 LockscreenCharging: squashed (2/3)
f418fd56e adb: host: Fix windows build after 5c0999c
f3ac718d5 Change search order for system processes in vndk_lite.
b15321328 Set /sys/power/wake_lock permissions on init.
7c562ba3a ueventd: make parallel restorecon functionality optional
0aad61185 healthd: cover devices that have voltage_max file with value of 0
6f83b83e2 camera: Add L-compatible camera feature enums
73307afb0 set /system/etc/init.d/* permissions
03f72b0cc init: always allow local.prop overrides
3925540a1 mkbootimg: add 32K 64K and 128K pagesizes
b5f13be04 utils: Threads: Handle empty thread names
2bf353f23 adb: host: Provide better sideload status
eed61648e healthd: allow custom charger images
35d63ca29 healthd: Reinitialize mChargerNames for every battery update
961e0e5fe healthd: Add support for HVDCP_3 chargers
02e358a78 logcat: Map '-C' to 'logcat -v color'
618199847 Add wrapped key support
a90e59e50 Revert "Format formattable partitions if mount fails"
83a1a9ad8 fs_mgr: mount: don't set the block device as ro for recovery
fbe227e96 reboot: mark as recovery_available
6471d729b fs_mgr: Fix EnsurePathMounted with a given mount_point.
a7bd6397e Camera: Add feature extensions
c9bd3649f adb: Add wait-for-online command
b42cace7e init: Don't run update_sys_usb_config if /data isn't mounted
59db8591b mkbootimg: Make unpack_bootimg py3 compatible
3374ce962 bsdgrep: for -r, use the working directory if none specified
964e0cb69 Disable flashing of stock recovery correctly
7e9da4017 healthd: Add DASH charger type
8881adf3e init: Add vendor-specific initialization hooks.
7354bbad1 mkbootimg: add support for --dt
0d0837bb5 init: don't skip starting a service with no domain if permissive
ba5839945 ueventd: parallelize restorecon /sys

====================
     2020-05-05
====================


 * build/make
c7236de72 Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/build into HEAD

 * frameworks/av
17966d3e2 Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/frameworks/av into HEAD

 * manifest
b59be01 Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/manifest into HEAD
d8bc74e Manifest for Android 10.0.0 Release 35
3900458 Manifest for Android 10.0.0 Release 34

 * packages/apps/Settings
8c4941fd9d Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/packages/apps/Settings into HEAD

 * packages/services/Telephony
508f5887b Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/packages/services/Telephony into HEAD

 * system/bt
9f6e5a17d Merge tag 'android-10.0.0_r35' of https://android.googlesource.com/platform/system/bt into HEAD

====================
     2020-05-04
====================


====================
     2020-05-03
====================


====================
     2020-05-02
====================


====================
     2020-05-01
====================


 * hardware/qcom/display
7d10f4b5c msm8084: libhwcomposer fix some warnings

====================
     2020-04-30
====================


 * external/bash
aeab988 inputrc: Import from Ubuntu

 * hardware/qcom/display
d20c3f894 Make hwc_vsync thread realtime
b9bd88086 msm8084: Deprecate usage of cutils/log.h

====================
     2020-04-29
====================


 * packages/providers/MediaProvider
b86aa46 MediaProvider: Less spam

====================
     2020-04-28
====================


====================
     2020-04-27
====================


 * packages/apps/BootlegDumpster
730709d Dumpster: Make ls artwork blur simple
58b716e Squash the Battery Bar [2/2]
9d96578  Bring back Gaming mode [3/3]
4222776  preference: Add SystemSettingsMasterSwitchPreference
9b93617  Less boring heads up option [2/2]
f64f8f1 Dumpster: Nuke some FOD icons and bootleg new FOD icons [2/2]
31e3870 Dumpster: Nuke some useless fod animations

 * packages/apps/Camera2
6496123f4 Camera2: Rename prevent power key permission

 * vendor/bootleggers
9bd9742f vendor: [SQUASH] Update changelog.sh

====================
     2020-04-26
====================


 * packages/apps/BootlegDumpster
d4c5091 Dumpster: Add new FOD pressed state icons [2/2]

====================
     2020-04-25
====================


