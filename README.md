"# samsung_twrp" 
For SM-G313HU Samsung Galaxy S Dous 3
[RECOVERY] [SM-G313HU/HN] TWRP-Materialized 2.8.7.0
[RECOVERY][UNOFFICAL] TWRP 3.1.1-0 For SM-G313HU a.k.a Ace4/S Duos 3.
Team Win Recovery Project (TWRP) is an open-source software custom recovery image for Android-based devices. It provides a touchscreen-enabled interface that allows users to install third-party firmware and back up the current system, functions often unsupported by stock recovery images. It is, therefore, often installed when rooting Android devices, although it isn't dependent on a device being rooted to be installed.

Notes for themers: In addition to the udpated theme, we have introduced a theme version variable to the TWRP theme system. If the theme version does not match the version that TWRP expects, TWRP will reject the custom theme and load its stock theme. This change will ensure that people who update TWRP without updating their theme will still have a workable recovery. We have removed libjpeg support. The stock theme was only using a jpeg image for the splash / curtain. This change means that any custom themes will no longer be able to use jpeg images. It also means that tools used to repack recovery images with a different curtain / splash will need to be updated to use the new method.

Version number notes: For a while we’ve been using a 4 digit version number and reserved the 4th digit for device-specific updates. For instance, we find and fix a device-specific issue like decryption of data on Nexus 5, we would release that as a 2.8.7.1. After a while, some people would start asking where 2.8.7.1 was for other devices. So, going forward we have decided to change the numbering scheme to 3.0.0-2, etc. Our hope is that this version numbering scheme will more clearly identify that the 4th digit does not indicate a version change for the code base.

this Image of Twrp is Compiled with Latest 2018 Source Code. So enjoy. :p


Bugs:
You Tell :p

DOWNLOAD:

see attached files below.

Installation Instructions:

Method-1:
If you have already any custom recovery installed. you can Download that twrp zip file and directly flash it with custom recovery. after flashing select reboot and select reboot to recovery.

Method-2:
just Download recovery.img.tar and flash it via odin in AP.




TWRP For S Duos 3/Ace 4

Thanks to @itigr for Device Trees.

Contributers: @JaskaranSM

Status : Stable

Created: 5-Feb-2019
