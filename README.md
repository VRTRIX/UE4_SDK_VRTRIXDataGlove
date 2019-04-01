# Introduction [中文][chinese]

<p align="center">
  <img src="https://github.com/VRTRIX/VRTRIXGlove_Unity3D_SDK/blob/master/docs/img/digital_glove.jpg?raw=true"/>
</p>


VRTRIX Data Glove is a product based on high accuracy IMU modules that populated on each finger & hand. Each IMU result can detect rotation of one joint. Combined with sophisticated Inverse-Kenetic Algorithm,  VRTRIX Data Glove is able to detect & simulate all gestures of human hands with six IMUs per hand (12 for a pair). 

VRTRIX IMU modules includes 9-axis sensors (gyro, accel & mag), where rotation quaternions are calculated with adaptive multi-state Kalman Filter algorithms and the output of the data stream is up to 400Hz while the latency of this module remain under 5ms. All IMU modules are connected to RF processor and the sensor tracking data packets are transmitted through 2.4GHz proprietary protocol. Thanks to the strict power control during the system design, the glove's battery can last at least 16 hours even when heavily used. The time latency between rotating your hands and the virtual hand gesture rendered in VR headset is less than 10ms. Lightning fast real-time response, precise tracking and full finger gesture detection brings the most impressive interactive experience to Virtual Reality!

# VRTRIXGlove_UE4_SDK

This repository contains the VRTRIX Glove UE4 Plugin, which includes assets that you can use to develop applications in Unity on your Windows PC while using our VRTRIX Data Glove. These assets include models, buleprints and some simple examples to help you quickly get the hand on development in both 3D & VR/AR environment. 

**To download VRTRIX Glove latest stable UE4 Plugin Release, visit [our release page][devsite].**

## Support

- VRTRIXGlove_UE4_SDK supports UE4.16 and up, Window 10 OS**

- Note that this repository may contains code for work-in-progress modules, tentative modules, or older modules that may be unsupported.We recommend using the release version packages available on the [our release page][devsite].

[chinese]: https://github.com/VRTRIX/UE4_SDK_VRTRIXDataGlove/blob/master/README_CN.md "chinese"
[devsite]: https://github.com/VRTRIX/UE4_SDK_VRTRIXDataGlove/releases "VRTRIX Glove UE4 Release site"
