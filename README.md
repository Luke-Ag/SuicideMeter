# SuicideMeter
This is aimed to be similar to an ignition interlock system but aimed at being a streamline quick survey to attest to the operators mental health and either chose to allow use of the vehicle or not. 

The hardware running this will be a Raspberry Pi Zero W 2 (control device) running TinyCore/piCore connected to a 8000mAh power bank which will be powered by a 100 W power inverter connected to the 12V battery using 3/8" eyelet connectors. The control device will either complete the circuit allowing you vehicle to run or not. This will be accomplished by controlling a 30A 30VDC bearing relay with a 5V/3A switch connected to the pi.
