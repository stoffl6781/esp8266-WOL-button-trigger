# esp8266-WOL-button-trigger
ESP8266 Wake on LAN 

This program is used to turn on a PC when a GPIO is closed.

D4 = AP mode
D3 = trigger pin

D4 / 3 must be switched to GND.

Pin D3 is monitored; if it is closed, it triggers a WOL message.
Another button can be used to switch to AP mode in order to save the settings for Wifi and destination MAC address.

The project was created with Wifimanager from tzapu.

Required libraries:
include <FS.h> Lib Manager

include <ArduinoJson.h> V5 Lib Manager

include <WiFiManager.h> https://github.com/tzapu/WiFiManager

include <WiFiUDP.h> Lib Manager

include <WakeOnLan.h> https://github.com/koenieee/WakeOnLan-ESP8266
