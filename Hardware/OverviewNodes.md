# LoRa hardware - Nodes

## Overview
Here's a table of a few hardware boards supporting LoRa.
Specific instructions can be found below. If you're unsure
what to buy, send us an [email](Contact).

| Device            | Chip   | MCU       | Connector   | Cost (EUR)   | Comments                   |
| ----------------- | ------ | --------- | ----------- | ------------:| -------------------------- |
| Sodaq Tatu + Bee  | ?      | AVR       | Bee         | 35,- + 35,-  | Arduino-IDE compatible     |
| Netblocks         | SX1272 | STM32L151 | IO          | 35,-         | program with ST-link       |
| HopeRF RFM92W     | RFM92W | -         | (raw board) | 10,-         | cheap but hard             |
| Kerlink loramote  | SX1272 | yes       | IO          | 150,-        | professional; has GPS      |
| ....              |        |           |             |              |                            |

There's many more; for a bigger list, [contact us](Contact).

## SODAQ Tatu
The SODAQ Tatu is based on the ATmega1284P and Arduino compatible.

1. Download the Arduino IDE: https://www.arduino.cc/en/Main/Software
2. Install hardware support for Tatu: https://github.com/SodaqMoja/HardwareTatu
3. Install dependencies: https://github.com/bblanchon/ArduinoJson
4. Clone our demo repository: https://github.com/TheThingsNetwork/loraduino
5. Add sensors, add custom logic
6. Compile, Upload, boot.


## Netblocks
todo


## HopeRF
We're struggling with this board ourselves.

Here is howto connect it to an Arduino Uno: https://github.com/matthijskooijman/arduino-lmic/wiki

For now the LoRa is working, but the WAN not. The github is based on IBM LMIC (LoraMAC-in-C).

## Kerlink Loramote
This device should work out-of-the-box. It will start sending GPS, temperature and battery data as soon as it is powered.

TODO: custom applications compile. Kerlink has a nice wiki with instructions.


## More devices will be contributed soon (by you?)
