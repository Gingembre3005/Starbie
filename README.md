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

## Bill of Materials (BOM)

| Qty | Item  | Cost (ea.) (€) | Link |
|---:|---|---|---:|---|
| 1 | 0.96" OLED |  2.99 | [Makeroo](https://makeroo.de/products/096-zoll-oled-display-modul-ssd1306-i2c-spi-128x64-fuer-arduino-weiss) |
| 1 | MPU6050 | 3.29 | [Roboter-Bausatz](https://www.roboter-bausatz.de/p/3-achsen-beschleunigungs-lagesensor-gy-521-mpu-6050) |
| 1 | 220 Ω Resistor |  0.18 | [Reichelt](https://www.reichelt.de/de/de/shop/produkt/widerstand_metalloxyd_220_ohm_0207_1_0_w_5_-1800) |
| 1 | 10 kΩ Resistor |  0.12 | [Reichelt](https://www.reichelt.de/de/de/shop/produkt/widerstand_kohleschicht_10_kohm_0207_250_mw_5_-1338) |
| 2 | MX Switches |  0.19 | [OnBuy](https://www.onbuy.com/de/p/tastaturschalter-50-stuck-3-pin-blaue-tastaturklicker-ersatz-staubdichte-mechanische-tastaturschalter~p271163583/) |
| 1 | EC11E Rotary Encoder | 2.00 | [ManoMano](https://www.manomano.de/p/drehgeber-10-stuck-ec11-drehgeber-codierschalter-digitalpotentiometer-mit-schalter-5-polig-weit-verbreitet-in-der-automobilelektronik-86491443) |
| 1 | XIAO ESP32-C3 | 5.00 | [Seeed Studio](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) |
| 1 | DHT11 | 1.79 | [Roboter-Bausatz](https://www.roboter-bausatz.de/p/dht11-modul-digitaler-feuchtigkeits-und-temperatursensor) |
| 1 | Buzzer  | 0.70 | [DigiKey](https://www.digikey.de/en/products/detail/tdk-corporation/PS1240P02BT/935924) |
| 1 | PCB  | 10.00 | [JLCPCB](https://www.jlcpcb.com/) |
| | **Total (per kit)** | | **26.47** | |
