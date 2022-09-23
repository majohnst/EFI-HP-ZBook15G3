# EFI-HP-ZBook15G3

This repository contains EFI folder for macOS Monterey 12.6 on the HP ZBook 15 G3 using OpenCore 8.4

## Attention! This configuration won't work until you change PlatformInfo according to this guide: 

https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html

You can use OpenCore Configurator or ProperTree to change needed values (DON'T use VS Code for that, it doesn't recognize data fields properly)

Working:
* Graphic acceleration
* Built-in speakers and mic
* Headphone audio through 3.5mm jack (mic not working)
* HDMI
* Touchpad with gestures
* Battery indicator
* Bluetooth and WiFi
* Handoff
* iServices
* CPU Temp and Fan Speed Monitoring
* Thunderbolt docking
* USB C ports
* NvMe 

Known issues:
* Sleep not working (better disable auto sleep)
* Headphone mic through combo jack (I think possible solution will be to buy Thunderbolt to 3.5mm adapter, but not tested yet)
* Battery time is worse comparing to Windows (nearly twice worse)
* NumLock toggle (it's always turned on)
* Lower touchpad buttons (closest to edge) - Ones at keyboard function.