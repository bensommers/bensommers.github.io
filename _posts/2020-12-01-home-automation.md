---
layout: post
title: "Home Automation"
author: "Ben Sommers"
categories: documentation
tags: [documentation,sample]
image: cactus.jpg
---

# Home Assistant

# Hardware
    * Raspberry Pi 4  
    * 1x Google Nest Home  
    * 2x Google Nest Speakers  
    * WS2812B RGB 60 Pixels/m  
    * USB Audio/Video Capture Card  

    Zwave
    : Aeon Labs MultiSensor
    : Aeon Labs Zwave Stick
    : 2x Aeon Labs Smart Dimmer
    : Ecolink Water Detector
    : 3x Zwave Power Switches (15A)
    : Vision Security Motion Sensor
    : Vision Security Recessed Door/Window Sensor

    Camera
    : Amcrest NVR 8Ch System

Currently deployed via docker, running automations as follows:
* Lights on sundown
* Lights on upon entry to office, off after 10 minutes no activity

# Google Home
Integrated into Home Assistant
* 1 x Google Nest Home acting as photo frame 
* 2 x Google Nest Speakers spread cross downstairs
* Downstairs Speaker group for broadcast on first floor
