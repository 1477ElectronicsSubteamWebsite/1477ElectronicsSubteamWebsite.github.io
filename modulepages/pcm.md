---
layout: page
permalink: /modules/pneumatics-control-module/
title: "Pneumatics Control Module"
---
### Pneumatics Control Module (PCM)

Controls the pneumatics on the robot by turning on/off the compressor and controlling solenoids. 

### New REV Pneumatic Hub

Functions similarly to the PCM, with enhanced compatibility with the REV system.  16 solenoid channel and capacity for 2 analog pressure sensors in addition to a pressure switch.

### Troubleshooting

##### Won't turn on:

Check connection to the PDP. Specifically the crimps & the fuse

##### Not supplying power to a solenoid:

Check crimps to verify, and make sure there is no break in the wire.

##### Not in CANbus:
Check for breaks in the CANbus, specifically the crimps leading to the PCM if it is not getting communication. The simplest way to check for breaks is by plugging into REV Sparkmax client and seeing which devices are visible.

##### Solenoids acting up (won't work):

Make sure that the voltage is the same on both sides of the solenoid and the voltage jumper on the PCM is in the correct spot for the voltage.
