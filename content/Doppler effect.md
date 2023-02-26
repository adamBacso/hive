---
title: "Doppler effect"
alias: ["Doppler shift", "Doppler"]
type: note
subject: physics
tags:
 - physics
 - extra
 - main
 - supersonic
 - waves
 - sound
created: 2023.02.26 10:06
created_by: Ádám
TARGET DECK: physics
summary: 
status: draft
---
# Basic principle
when a source is stationary, waves propagate from it with a uniform frequency in all directions
when a **source** is moving in a **medium**, the waves in the direction of its movement are generated closer together (the relative velocity of the wave and source is lower) → higher frequency 
→ lower frequency behind the source
![](https://upload.wikimedia.org/wikipedia/commons/9/90/Dopplerfrequenz.gif)

>[!important] the velocity of the observer or source is relative to the medium
>the total Doppler effect may be the result of the combinating the motion of the **source**, the **observer**, or the **medium** itself

# History
discovered by Austrian physicist **Christian Doppler** in 1842

# Equations
$$f=\left( \frac{c\pm v_{r}}{c\pm v_{s}} \right)f_{0}$$
$f=\text{observed frequency}$
$f_{0}=\text{emitted frequency}$
$c=\text{propagation speed of waves in medium }$
$v_{r}=\text{relative speed of reciever}$ 

>[!warning] added to c when $r\to s$, subtracted from c when $(s)r\to$,

$v_{s}=\text{relative speed of source}$

>[!warning] added to c when $(r)s\to$, subtracted from c when $s\to r$,

# Uses
## Acoustic Doppler current profiler
used to measure water current velocities (laser Doppler velocimeter (LDV) acoustic Doppler velocimeter (ADV))
can also be used for:
- air (SODAR)
- blood (echocardiogram)
- 
## Robotics
used for path planning when environment is changing

## Sirens
aids drivers to determine the location and **heading** of emergency vehicles
if it is higher pitched → it is moving in the direction of the driver
if the pitch is lower → it is moving away
if pitch is changing → either relative speed is changing **OR** it is passing by ($v_{\text{radial}}=v_{s}\cos(\theta)$)

## Astronomy
Doppler effect for EM waves → red- and blueshift
**not the same as [[cosmological redshift]]** ← doppler redshift will affect

used to detect [[binary stars|close binary stars]], measure rotational speed of galaxies, or to detect [[exoplanets]] using [[doppler spectroscopy]]

## Radar
radar waves are sent and received to determine (relative) speed of object
$$\Delta f=\frac{2\Delta v}{c}f_{0}$$
## Satellite
[[DORIS]]
### Communication
fast moving satellites → shift of frequency relative to ground station
frequency is changed dynamically to compensate

# [[Sonic boom]]

# Sources
https://www.youtube.com/watch?v=kdiHmSWI2Ks
https://hubblesite.org/contents/media/images/4509-Image.html#:~:text=The%20universe%20is%20expanding%2C%20and,distance%20the%20light%20has%20traveled
https://www.nhs.uk/conditions/echocardiogram/#:~:text=An%20echocardiogram%2C%20or%20%22echo%22,different%20parts%20of%20the%20body
https://en.wikipedia.org/wiki/Doppler_effect
https://en.wikipedia.org/wiki/Doppler_spectroscopy
https://en.wikipedia.org/wiki/Sonic_boom
https://en.wikipedia.org/wiki/DORIS_(satellite_system)
https://en.wikipedia.org/wiki/Sodar