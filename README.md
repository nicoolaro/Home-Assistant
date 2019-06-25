# Home-Assistant



Setup:

Home Assistant:
- Hass.io on RPI2 +16GB SD Sandisk ( database MariaDB is on another RPI3 )
- RPI 3B+ running Dietpi + Kodi + Transmission(media on external HD) .  MariaDB separated to USB Stick attached to RPI
 
 addons:
  - EspHome https://github.com/esphome/hassio
  - Mopidy https://github.com/assada/hassio-addons/tree/master/mopidy
  - Mosquitto broker #official
  - SSH server  #official
  - NGINX Home Assistant SSL proxy #official
  - Samba #official

Light:
- Addresable 3m (90 leds) WS2812 running on Nodemcu
- RGBWW 4m strip 240 leds on MagicHome controller 
- RGB 3m strip on IR controller.
- RGB Yeelight v2

Sensors:
- Door sensor (reed switch) attached to Nodemcu which is running WS2812 & PIR sensor 
- Capacitive soil sensors attached to  Wemos D1 mini
- Aqara door/window sensor 
- Aqara motion sensor 
- Aqara temperature and humidity sensor 


Network:
- Mikrotik HAP lite2 and DD-WRT on an old TP-Link as routers.

- Sonoff basic x 3 #flashed with EspHome https://esphome.io/devices/sonoff_basic.html
- Broadlink RM Mini 
- Scripts for Kodi and various light/videos, on Kodi as an ambient experience
- Google home mini 
- Telegram as a way of providing notifications to the phone

to be continued....
