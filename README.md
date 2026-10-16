# Starbie

## Introduction:

This is my Patrick Star Starbie for the Hackclub Half Life challenge. It's a desktop pet that can interact with the user. I learned a lot doing this project as it was my first time designing a PCB. 

## Firmware:

Patrick Star will have different emotional states, which will change when the user interacts with him. 
If you leave Patrick Star alone for too long he will progressively become sad. 

## How to flash the firmware:

1. Download the code which will soon be in this repo.
2. Download the Arduino IDE.
3. Open File → Preferences. In Additional Boards Manager URLs, add:

https://espressif.github.io/arduino-esp32/package_esp32_index.json

4. Open Tools → Board → Boards Manager, search for esp32, and install esp32 by Espressif Systems.
5. Under Tools → Board → esp32, select XIAO_ESP32C3.
6. Open Sketch → Include Library → Manage Libraries. Install these libraries one at a time:

-Adafruit GFX Library
-Adafruit SSD1306
-Adafruit MPU6050
-DHT sensor library
If Arduino asks to install dependencies, choose Install All.

7. Connect the Patrick Star Starbie to your pc and flash the code.


## PCB picture:

![My Project](Pictures/PCB.png)

## Schematic picture:

![My Project](Pictures/Schematic.png)

## Picture from a render of the PCB:

![My Project](Pictures/Render.png)

## Picture of a drawing for the face of the Starbie:

![My Project](Pictures/Starbie%20Screen.png)

## Bill of Materials

[View the parts list (CSV)](BOM.csv)
