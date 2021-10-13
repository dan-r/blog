---
layout: post
title: "3D Printer Laser Interlock"
date:   2021-10-13 17:00:00 +0100
categories: [Lasers, 3D Printing]
image: /images/2021-09-17-IMG_4117.jpeg
---

As mentioned in my previous article, lasers for the Ender 3 typically use the PWM power supply from the fan header. Although these connections could manually be switched, it would be laborious and could also potentially be dangerous. 

My solution to this was a simple 3D printed switcher, allowing me to maintain the use of the fan and also have independant laser control. 

![Laser interlock device](/images/2021-09-17-IMG_4117.jpeg)

## Parts List
- [3D Printed Case](https://www.thingiverse.com/thing:5020191)
- 4x M3 screws
- 1x 3mm LED
- 1x Miniature SPST Rocker Switch
- 1x SPST Toggle Switch
- 1x 12mm SPST Key Switch

The parts for this build are all available both locally (in the UK at least) and from China. I haven't provided any links as listings often change and these can all be found fairly easily.

## Schematic
![Schematic](/images/2021-10-13-Fritzing.png)

The SPST toggle switch is wired to the fan header of the 3D printer. I used a JST cable extension, but you can splice an existing cable or crimp your own connectors if you'd prefer. I did the same for the two outputs.

## Conclusion
This interlock requires a key input and two switches to activate the laser. This is intended to prevent any case of accidental activation, whether by pets or family. Many key switches of this size provide no real 'security', and the one I used was easily switched by a screwdriver. I only mention this to reiterate that this is only intended to prevent accidental activation.