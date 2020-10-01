---
layout: post
title: "CHAT Project"
date: 2020-01-27
description: 
author: Charles Ramey
img: /assets/img/chat.jpg
tags:
  - Wearables
---
![CHAT](/assets/images/chat.jpg)
Since  2010  Georgia  Institute  of  Technology  has  been collaborating with marine biologists from the Wild Dolphin Project to build computers which facilitate two-way human, wild dolphin interaction through the assignment of artificial whistles  to  objects  such  as  pieces  of  rope,  seaweed, seagrass,  and  scarfs. We call this project Cetacean Hearing and Telemetry (or CHAT for short).

Starting in 2015, I began to work on the CHAT project as an undergraduate researcher. My first roles on the project were documentation and aiding with the construction of the 2015 generation of wearable computers. Georgia Tech research scientist Scott Gilliland showed me the ropes as I followed him through the production process. Scott designed custom high frequency speakers and waterproof keyboards specifically for these wearable computers. These parts were the first things I was able to help construct for the project. Along the way, I compiled an extensive assembly and operations manual for the wearable computers. 

As we began deploying the wearables more frequently and collected more data, we soon realized that our software recognition pipeline for matching patterns in the dolphin whistles was not sophisticated enough to actually detect sounds we might expect the dolphins to make. The initial recognition software employed what was the best algorithm our (somewhat computational limited) computers could run in real time. This algorithm was very similar to the process that Shazam employs to recognize what song is playing around you. You can read more about the Shazam algorithm [here](https://www.ee.columbia.edu/~dpwe/papers/Wang03-shazam.pdf) if you're curious.

![A CHAT Wearable Computer System](/assets/images/CHATsystem.JPG)

While very accurate, the version of the Shazam algorithm we employed ran around a process which was limited in the number of frequencies it could analyze and our computer's processor could only run this algorithm at 44.1kHz sampling rate. This essentially meant that while dolphins can make sounds anywhere in the frequency range from 200Hz to 150kHz (with whistles in the 2kHz to 50kHz range typically used for social communications), we were only able to analyze whistles in the 2kHz to 20kHz range. 

![Example FFT and filter responses](/assets/images/fft_filters.JPG)
(Note: This page is in progress.)
