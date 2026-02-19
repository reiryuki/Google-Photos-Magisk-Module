# Google Photos Magisk Module

[ DISCONTINUED BECAUSE THE LATEST VERSION OF GOOGLE PHOTOS IS ALREADY FIXED THE PERMISSION ISSUE AND INSTALLING THIS MODULE CAN EVEN CAUSE SIGNATURE ISSUE LIKE EDIT FEATURE DOESN'T WORK]

## DISCLAIMER
- Google apps are owned by Google LLC
- The MIT license specified here is for the Magisk Module only, not for Google apps.

## Descriptions
- Gallery app by Google LLC integrated as a Magisk Module for all supported and rooted devices with Magisk
- Usually, GApps installs Photos.apk in */app instead of */priv-app because it refers to default location on Google Pixel ROM. However, Photos.apk will not run properly on custom ROMs which usually have different signature than the Photos.apk because the WRITE_MEDIA_STORAGE permission is not granted. This module places Photos.apk into */priv-app instead and whitelist the WRITE_MEDIA_STORAGE permission so it runs it's function correctly on any ROM.
- You can run this terminal command to see is the WRITE_MEDIA_STORAGE permission granted (true) or not (false):

`su`

`dumpsys package com.google.android.apps.photos | grep WRITE_MEDIA_STORAGE`


## Sources
- https://apkmirror.com com.google.android.apps.photos by Google LLC

## Screenshots
- https://t.me/ryukimodsscreenshots/22

## Requirements
- arm64-v8a is for arm64-v8a architecture
- armeabi-v7a is for armeabi-v7a architecture
- x86_64 is for x86_64 architecture
- x86 is for x86 architecture
- Android 6 (SDK 23) and up
- GApps installed
- Magisk or KernelSU installed

## Installation Guide & Download Link
- Download the right module according to your device architecture here: https://www.pling.com/p/2223094/
- Install the module via Magisk app or KernelSU app or Recovery if Magisk installed
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards

## Optionals
- Global: https://t.me/ryukinotes/35

## Troubleshootings
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- @HuskyDG
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/ryukinotes/25


