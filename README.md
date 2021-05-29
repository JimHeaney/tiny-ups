# Tiny UPS

## Overview
The Tiny UPS is a small device that provides an all-in-one power solution for projects. 

The Tiny UPS will always provide stable 5v power. If there is no USB cable connected, a LiPo will be boosted to make the 5 volts. If there is a USB cable connected, the 5 volts is drawn from that, and the LiPo is charged. Switching between the two is nearly instantaneous, and connected devices should not (hopefully) experience a change in their voltage. 

To work properly, the connected circuit needs a lot of capacitance. The moment that the input source changes from 3.7v to 5v or vice-versa, there may be a small dip. Depending on the power draw of the circuit and sensitivity to voltage drops, this may result in nothing, or it may result in a brownout. The baseline I'm targeting for this device is that it will not trigger the 4.2v brownout detection in an Arduino Uno when it is running code that blinks on and off 2 LEDs (i.e. one LED is always on). Loads larger than this can benefit from a large electrolytic capacitor between 5 volts and ground.

The Tiny UPS is still very much a WIP and the first iteration is barely tested. I strongly suggest against using this circuitry as anything except a reference until I finish work on the next version!

## Photos & Media
Coming Soon

## Current Release
There is no stable release. 

## Current State
The Tiny UPS is currently being developed to Version 1.1.


## Support Me
You can buy me a coffee [here](https://www.buymeacoffee.com/jimheaney)!

## License
This project is licensed under the Creative Commons 4.0 Attribution-NonCommercial-ShareAlike. For more information, click [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you want to use this project under a different license, please contact me. 
