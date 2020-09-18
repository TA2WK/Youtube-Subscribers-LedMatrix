# YoutubeSubscribers
Basic YouTube subscribers and viewer counter that can be done using **ESP32s**, **ESP8226** or **Wemos D1 Mini**. I used Wemos D1 Mini but any other ESP devices can be used.

This project was inspired by https://github.com/DIY-Machines/YoutubeSubcriberV1 and done using new **YouTube APIs** and excellent animated **MD_Max72XX** and **MD_Parola** LedMatrix display libraries.

### Required Hardware/Tools
---
- Wemos D1 Mini
- MAX7219 Display Matrix (4 panels)
- Breadboard Jumper Cables
- USB A to USB Micro B Cable (Basic microUSB Android cable, data capable)
- Some Nuts and Bolts (if you would like to use it with 3D printer box - see below)

### Required Arduino IDE Libraries
---
Following libraries can be installed in Arduino IDE library manager
- MD_Max72XX https://github.com/MajicDesigns/MD_MAX72XX
- MD_Parola https://github.com/MajicDesigns/MD_Parola
- YouTube API https://github.com/witnessmenow/arduino-youtube-api
- Arduino JSON https://github.com/bblanchon

#### Following libraries and ESP boards should be installed in Arduino IDE | File > Settings > Additional Board Manager URLs:
and paste this https://arduino.esp8266.com/stable/package_esp8266com_index.json
- WiFiClientSecure
- ESP8266WiFi

### 3D STL Files
---
https://www.thingiverse.com/thing:3444779
