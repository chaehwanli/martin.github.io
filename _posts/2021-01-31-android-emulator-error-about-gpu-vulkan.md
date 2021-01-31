---
layout : post
title : Dependency Injection - 1
---

I got the error message when I try to run android sample codes.

error window
> ![error window](..\images\android_emulator_vulkan_error.png)

How to resolve it?
> [how to resolve from stackoverflow](https://stackoverflow.com/questions/44328225/cant-change-emulated-performance-of-avd-in-android-studio/58376934#58376934)

I got AVD as {home}.android\avd\Pixel_3a_API_30_x86.avd
and gpu is enabled.

So, I change some config (config.ini)

>hw.gpu.enabled=yes7
hw.gpu.mode=sofware

Then I can run AVD.

