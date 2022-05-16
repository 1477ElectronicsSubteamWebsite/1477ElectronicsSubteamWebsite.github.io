---
title:  "roboRIO"
permalink: /modules/roborio/
layout: page
---

### NI roboRIO 2.0

The newest version of the roboRIO, the brain of the FRC system. 10 DIO and 10 PWM ports for various modules, compatible with the navX navigation sensor, and houses a USB and ethernet port.

### Troubleshooting

##### Housekeeping:  

Confirm that the roboRIO is imaged properly. This can prevent future problems.

##### Won't turn on:

Verify the connection powering the module. Check crimps, fuse, etc. 

##### Not delivering power to a certain module:

Verify the connection by checking crimps and wire, also check to make sure the pins aren't bent.

##### Not in CANbus:

Check for breaks in CAN (using REV Sparkmax client is simplest)

##### No robot communications:

Check connection to radio, and ensure that the radio is getting enough power.
