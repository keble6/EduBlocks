---
id: Moisture Sensor
summary: Connect a moisture sensor to a Raspberry Pi and write Edublocks code
categories: raspberrypi
tags: projects, raspberrypi, easy, fun
difficulty: 2
status: draft
published:
author: Rob Wilson rob@rwilson.org.uk
feedback_url:

#Moisture Sensor
## Overview
This project shows how you can connect a low-cost moisture sensor to a Raspberry Pi and use EduBlocks to use its output - for example, to display "wet" or "dry" on the screen.

This can be used as part of a bigger project to automate the watering of a plant (for example).

You will need:
* An internet connection
* A setup Raspberry Pi with EduBlocks Connect installed (Follow the guide on the [Raspberry Pi page](https://edublocks.org/pi.html) to learn more.
* A moisture sensor from (for example) [ModMyPi](<img src="https://www.modmypi.com/image/cache/catalog/electronics/sensors/soil-mositure/DSC_0173-747x569.jpg" alt="Soil Moisture Sensor"/>
* )

## Get started
* Launch EduBlocks Connect (from the Programming menu)
* Launch a web browser and go to https://app.edublocks.org/
* When this has loaded, select Raspberry Pi **mode**.
* You should now see the EduBlocks on the left

## Connecting the sensor
* The sensor circuit board needs
 * power (3.3V) and ground (0V) connections from the Pi's GPIO pins
 * a signal wire to a GPIO pin that will be used as an **input**
 * two wires to the actual sensor

The photo shows these connections.
![Connections](images/sensor_connections.jpg)

The power wire (red) connects from the sensor board pin VDC to the Pi's pin 1 (3V3).
The ground wire(black) connects from the sensor board pin GND to the Pi's pin 9 (Ground)
The signal wire(orange) connects from the sensor board pin DO to the Pi's pin 11 (GPIO17)
 
## Setting up the libraries
## Setting up the pins
## Create a loop
## Test the code
## Print the time when the moisture changes
---