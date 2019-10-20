# Align Trex-450V2 Heli (Aluminum Chassis with Flybar) v0.0.1a

What is this?
 
The Align Trex 450 V2 is am RC helicopter in the "micro" class which was popular in the early 2000's. This version is mechanical flybar stabilized
aling with a tail-rotor serve that is 1-axis gyro stabilised. The helicopters were notoriously difficuly to set-up for novices, required considerable
transmitter configurations and considerable experience in orientations and flight control operation. Once figured out, it's like riding a bike-- one 
can flay any RC heli with ease given nothing is set-up incorrectly from the factory.

These helicopters boast amazing return-to-target, load carrying, and aerobatic capabilties due to their fully articulated and bell-hiller mixed rotor 
systems (just like a traditional helicopter). Unlike a traditional helicopter, they can apply negative collective pitch which allows for sustained inverted 
flight. They use only one motor as a propulsion source (unlike quad-copters). Some micro-heli's may have a second smaller motor or ducted fan for the tail 
rotor / anti-yaw mechanism. Each have their pro's and con's. 

Generally, flight times can range from 5 to 20 minutes depending on control input, wind, and throttle usage.  

Newer micro-heli's come standard with flybar-less heads and 6-axis stabilization systems as flybar-heli's were trick to fly for first-timers. Flybar-less
heads are also less complex, but the complexity is transferred to the 6-axis electronic gyro system. We might look into adding computer control later and
select what works best for pure software / fly-by-wire flight. Stay tuned.

## There's no code here really?!?!

We'll figure something out. :)

## Basic Setup

* aluminum chassis
* Align 430L motor
* phoenix-35 ESC
* 3x HS-65HB P/R
* Futaba GT-401 SMM Gyro
* Futaba S9650 Yaw Servo
* Spektrum AR6000 RX (2.4Ghz)
* Swashaplate: 120 degree

## Servo and Gyro Connections:
* CH2 / AIL - Left
* CH6 / AUX - Right
* CH3 / ELE - Rear
* CH4 / RUD - Gyro
* CH5 / GEA - Gyro Control
* CH1 / THR - BEC / ESC

## TX (Transmitter) Settings:
* Mode: Heli
* CCPM: On
* Gyro Rate Switch: AIL (0 == Heading Hold / 1 == Rate Only)
* Gryo Gain (Gear Sub-trim): (-)50

## Reverse Settings:
* AIL - Norm
* ELE - Norm
* RUD - Norm
* GER - Norm
* PIT - Reverse
* THR - Norm

## CCPM Settings:
* CP2 - (+)60%
* CP3 - (-)60%
* CP6 - (-)60%

## Throttle / Collective Pitch Curve:
* PLN - (+)53%
* P2N - (+)65%
* PHN - (+)100%

## Throttle Curve:
* TLS - 0%
* T2S - (+)52%
* THS - (+)100%

## Changelog v0.0.1a
```
	- initial commit
	- heli fly's just as stable as I remember it
```
## Known Issues
```
	- need to add assets / pictures / initial schematics
	- add software stabilization and code
```
