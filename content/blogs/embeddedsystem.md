---
title: "Embedded system"
date: 2020-09-24T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

The International Meteorological Agency (IMAA) has a project to deploy surveillance ships equipped with on-board weather stations. The purpose of weather stations is to measure the parameters influencing natural disasters. For this, they must be simple, efficient and controllable by a crew member.

## Problem

How to make a simple and effective weather station?

## Achievements

First of all, we had the following hardware:
- An AVR ATmega328 microcontroller integrated to the Arduino board to design the prototype.
- Various components :
  - SD card reader (SPI) which will allow the saving of the sensors' data
  - RTC clock (I2C) that will allow the system to know the date and time of day.
  - RGB LED (2-wire) which will allow to communicate the status of the system
  - 2 push buttons (digital) that will allow interaction with the system
- Different sensors :
  - Air pressure (I2C or SPI)
  - Air temperature (I2C or SPI)
  - Hygrometry (I2C or SPI)
  - GPS (UART)
  - Brightness (analog)
- Various additional third-party modules that will be integrated into the project later on:
  - Water temperature (analog)
  - Sea current force (I2C)
  - Wind force (I2C)
  - Fine particle rate (2-wire)

We started by making several diagrams to better understand the functioning of our future weather station. In particular by representing the use cases, but also the triggers of certain events.

![Algorithm](/img/projects/embedded/algo.png)

It is then possible to start the system in different ways. The startup will be either normal or done with a red button. If the startup is carried out with the red button then the system passes in configuration mode which makes it possible to configure the system but which does not make it possible to acquire data. If the startup is normal, the system passes in standard mode and will acquire data thanks to the various sensors. From the standard mode it is then possible to activate the economic mode by pressing the green button for 5 seconds. This mode allows to save the battery while continuing to acquire some data, indeed some sensors as well as some treatments will be deactivated but the acquisition remains possible. To return to standard mode, simply press the green button for 5 seconds. From the standard mode and the economic mode it is possible to activate the maintenance mode by pressing the red button for 5 seconds. This mode will allow access to the data and to change the SD card. To return to the previous mode, press the red button again for 5 seconds.
Once the acquisition of the data is done thanks to the different sensors, the data must be processed. This will allow to detect the different errors that can occur before transmitting the data to the user. Once the data is transmitted, the system can be turned off.
To summarize, different modes are possible for the system and the goal is to acquire meteorological data thanks to the different sensors. Then these data will be transmitted to the user who will be able to forecast different weather events.

We were then able to set up our weather station and run the program.



## Acquired skills

During this project, we went back to the basics of programming in an embedded environment:
- Automata and modeling
- Computer architectures
- Compilation
- Program structuring
- Resource optimization
- Input and output management
- Handling of a linux system
