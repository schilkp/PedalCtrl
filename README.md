# PedalCtrl
Philipp Schilk 2020

https://github.com/TheSchilk/PedalCtrl

A very simple, PIC12F1572-based, footpedal-controlled, relay 250V Mains switch.

![PCB Render](https://raw.githubusercontent.com/TheSchilk/PedalCtrl/master/Doc/pcb_render.png)

## Mandatory Warning

Please don't work with mains-connected circuits unless you know what you are doing.

## Status

Waiting for PCB prototype to develop Firmware.

## Details

Allows mains-powered devices to be quickly powered on and off using a footswitch.
Both Line and Neutral are switched.

Pressing the pedal once enables the device and starts an automatic timer controlled
by the potentiometer. Once that timer runs out, or the pedal is pressed again, the 
device will switch back off.

Quickly pressing the pedal twice causes the device to stay permanently powered on until
the pedal is pressed again.

## Production Files
Please see Github 'Releases' for Schematic, Gerbers, Interactive BOM usw.


