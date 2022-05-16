---
title: "Motor Controllers"
permalink:/modules/motor-controllers/
layout:page
---



### REV SparkMAX

The REV motor controller that runs Neos and Mini Neos. Neos are brushless motors that have built in encoders. Compatible with REV Sparkmax client and can also be ran by PWM wire to

### TalonSRX and Victor SPX Speed Controllers

Run brushed motors, such as the 775 pro., and can be connected to an external mag encoder. Similar to the VEX VictorSPX, that also runs brushed motors.

### Troubleshooting

##### Isn't getting power:

Verify the connection powering the module. Verify that there is a breaker, then check the connection. If problem persists, bypass the power wire with a fresh one to test for a cut somewhere on the wire.

##### CANBus Inconsistencies:

CAN may be annoying to troubleshoot, however the most important thing to know is that REV Sparkmax client can save your CANBus if you know how to use it. Make sure every motor controller in your bus has a physcial label, which makes it easier to detect breaks. Follow the path of your device, and confirm on the client that each device is in the bus.

##### Not running a motor:

Specifically on Sparkmaxes (but can be on the others), check to make sure firmware is updated, and the CAN ID is correctly set. Then,  isolate the specific motor controller and try and run a motor to catch any defective/burnt out motor controllers.
