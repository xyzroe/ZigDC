---
layout: page
hide_title: true
hide: true                          
---
### About
Zigbee based 6ch DC power meter
E18-MS1-PA2, 2xINA3221, SHTC3
0 - 26V, 8mV resolution
+/- 5.2A, 1.3mA resolution

### Overview
<div align="center">
<img width="48%" src="https://raw.githubusercontent.com/xyzroe/ZigDC/master/images/top.png">
<img width="48%" src="https://raw.githubusercontent.com/xyzroe/ZigDC/master/images/bottom.png">
</div>

<div align="center">
<img width="55%" src="https://raw.githubusercontent.com/xyzroe/ZigDC/master/images/ZigDC.png">
</div>


### Schematic
[PDF](./files/Schematic.pdf)  
![Schematic](https://raw.githubusercontent.com/xyzroe/ZigDC/master/images/Schematic.png) 

### Where to buy?
<a href="https://www.tindie.com/stores/mind/?ref=offsite_badges&utm_source=sellers_xyzroe&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" height="120"></a>

### Firmware 
PTVO firmware constructor was used to build the firmware. There are two versions:
- Router - Supports routing but doesn't report the uptime of the device. [hex](./files/ZigDC_router.hex) 🔵 [txt](./files/ZigDC_router.txt) 
- End Device - No router functions, no SHTC3 sensor (temperature & humidity), but reports the uptime of the device. [hex](./files/ZigDC_end.hex) 🟠 [txt](./files/ZigDC_end.txt) 
  
#### Use PTVO version 2024-01-04 because newer version use different clusters and don't support 3 channels on 1 endpoint.

### Support 
Currently only supports in zigbee2mqtt. (Without external converter)

### DIY
- [iBOM page](./files/iBOM.html) 🌍
- [Gerber zip](./files/Gerber.zip) 🗂

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>

### Like ♥️?
[![badges](https://badges.aleen42.com/src/buymeacoffee.svg)](https://www.buymeacoffee.com/xyzroe) 
[![badges](https://badges.aleen42.com/src/github.svg)](https://github.com/sponsors/xyzroe)
[![badges](https://badges.aleen42.com/src/paypal.svg)](http://paypal.me/xyzroe) 
