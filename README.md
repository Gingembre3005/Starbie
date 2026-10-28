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
|---:|---|---:|---|
| 1 | 0.96" OLED |  2.99 | [AliExpress]([https://de.aliexpress.com/item/1005007475013244.html?spm=a2g0o.productlist.main.1.6d2014c3TzMwfG&algo_pvid=b96e7c29-bb73-43d6-8ad9-56e24584bb3a&algo_exp_id=b96e7c29-bb73-43d6-8ad9-56e24584bb3a-0&pdp_ext_f=%7B%22order%22%3A%22301%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.51%212.49%21%21%2118.18%2118.03%21%40210398e917931961607873221e0ccd%2112000040902623417%21sea%21DE%218427292374%21ABX%211%210%21n_tag%3A-29910%3Bd%3Aaf2815fb%3Bm03_new_user%3A-29895&curPageLogUid=0JzHXNCRZCjm&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007475013244%7C_p_origin_prod%3A]) |
| 1 | MPU6050 | 3.29 | [AliExpress]([https://de.aliexpress.com/item/1005009925487659.html?spm=a2g0o.productlist.main.2.75f215f9KceZsF&algo_pvid=6fdad029-dce3-4cbe-8554-f53b04c18259&algo_exp_id=6fdad029-dce3-4cbe-8554-f53b04c18259-1&pdp_ext_f=%7B%22order%22%3A%2296%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%212.15%212.15%21%21%2115.57%2115.57%21%400b88ad2b17931962859502002e0d3c%2112000050595570254%21sea%21DE%218427292374%21ABX%211%210%21n_tag%3A-29910%3Bd%3Aaf2815fb%3Bm03_new_user%3A-29895&curPageLogUid=cu7F5WUZFwko&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009925487659%7C_p_origin_prod%3A]) |
| 1 | 220 Ω Resistor |  0.18 | [AliExpress](https://de.aliexpress.com/item/1005011886443911.html?spm=a2g0o.productlist.seoads.1.1e2c4710u1212S&p4p_pvid=202610280705232452802854227200000752280_1&gatewayAdapt=glo2deu) |
| 1 | 10 kΩ Resistor |  0.12 | [AliExpress](https://de.aliexpress.com/item/1005011886443911.html?spm=a2g0o.productlist.seoads.1.1e2c4710u1212S&p4p_pvid=202610280705232452802854227200000752280_1&gatewayAdapt=glo2deu) |
| 2 | MX Switches |  0.19 | [AliExpress](https://www.onbuy.com/de/p/tastaturschalter-50-stuck-3-pin-blaue-tastaturklicker-ersatz-staubdichte-mechanische-tastaturschalter~p271163583/) |
| 1 | EC11E Rotary Encoder | 2.00 | [AliExpress](https://www.manomano.de/p/drehgeber-10-stuck-ec11-drehgeber-codierschalter-digitalpotentiometer-mit-schalter-5-polig-weit-verbreitet-in-der-automobilelektronik-86491443) |
| 1 | XIAO ESP32-C3 | 5.00 | [Seeed Studio](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) |
| 1 | DHT11 | 1.79 | [AliExpress](https://www.roboter-bausatz.de/p/dht11-modul-digitaler-feuchtigkeits-und-temperatursensor) |
| 1 | Buzzer  | 0.70 | [AliExpress](https://www.digikey.de/en/products/detail/tdk-corporation/PS1240P02BT/935924) |
| 1 | PCB  | 10.00 | [JLCPCB](https://www.jlcpcb.com/) |
| | **Total (per kit)** | | **26.47** | |
