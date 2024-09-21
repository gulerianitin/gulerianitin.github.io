---
title: 'Infotainment System'
date: 2018-08-14
permalink: /posts/GM-automotive
tags:
  - Automotive
  - GM
  - Infotainment System
  - Android
---


![Cadillac](..\images\Cadillac-XTS_2013_1280x960.jpg)


## Introduction

At GM, I contributed to the development of the Cadillac CUE(Cadillac User Experience) infotainment system, working on a fork of the Android Open Source Project (AOSP) that was acquired from Harman Kardon around 2014. The infotainment system, although it appears simple when integrated into a car, consists of numerous hardware modules. The main components, like a computer, include a motherboard from vendors such as Intel or Texas Instruments. Additional modules manage specific functions like climate control (HVAC) and seat massage.



![GM infotainment system](..\images\GM_Infotainement_System.jpg)



## Main Responsibilities
My primary focus was the Settings application, similar to the settings app on mobile devices, which controls the entire infotainment system's settings. While developing user stories was straightforward, bug fixing proved challenging due to the app's interfaces with other systems, often requiring collaboration across teams.

I also worked with a Windows-based vehicle simulator that used CAN signals to emulate vehicle functions. My role in this project included utilizing C# to interact with the simulator. For my Six Sigma Green Belt project, I automated parts of the simulator, which resulted in a 40% reduction in defect resolution time. Additionally, parts of the project involved building the AOSP in a Linux environment, requiring the use of powerful computing resources.

![GM infotainment system](..\images\GM_Infotainment_Complete.webp)




## Description of the infotainment system  

The GM Cadillac CUE (Cadillac User Experience) infotainment system offers a range of features designed to provide a smooth and connected experience for drivers and passengers. The Settings app within the CUE system allows users to customize various aspects of the vehicle’s infotainment, comfort and connectivity functions. Here’s how it typically works:

  * User Interface (UI) Navigation: The CUE system’s touch-sensitive screen serves as the central control hub. The Settings app can be accessed via the home screen, where different categories are presented, usually organized by system functions such as audio, climate, navigation, and vehicle preferences.

  * Customization Options:
      1.  Audio Settings: Users can adjust equalizer settings, balance, fade, and speaker preferences. They can also customize volume settings for different sources like radio, Bluetooth, or media.

      2. Climate Control: Settings for the vehicle's climate system, such as automatic climate preferences, air distribution, and seat heating/cooling, can be adjusted.

      3. Navigation Preferences: Options for route preferences, map display, and voice guidance for the built-in navigation system are adjustable here.

      4. Vehicle Settings: This includes door lock preferences, lighting (interior/exterior), and even how long lights stay on after exiting the vehicle.

  * Driver Profiles: The CUE system allows multiple driver profiles to be saved, so personalized settings (e.g., seat position, mirror angles, radio stations) can be automatically restored based on which driver is using the vehicle.

  * Connectivity and Bluetooth: Users can manage Bluetooth devices, configure Wi-Fi settings, and set up connections for smartphones. This section also allows syncing contacts, call history, and other information from paired devices.

  * Updates and Diagnostics: The system can be updated via USB or over-the-air (OTA) if supported. It may also include diagnostic features, letting users check system health and connectivity status.

  * Gesture and Voice Control: Many versions of CUE support gesture and voice control, allowing users to interact with the settings using touch gestures (e.g., swiping) or voice commands.

The Cadillac CUE’s Settings app streamlines the process of tailoring the in-car experience, making it highly customizable to user preferences, enhancing both convenience and comfort during the driving experience.