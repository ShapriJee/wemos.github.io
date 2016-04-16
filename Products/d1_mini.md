---
layout: tutorial
title: "D1 mini"
---  

The D1 mini is a mini wifi board based on ESP-8266EX.[Buy it](http://www.aliexpress.com/store/product/D1-mini-Mini-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266/1331105_32529101036.html)

  * 11 digital input/output pins, all pins have interrupt/pwm/I2C/one-wire supported(except **D0**)
  * 1 analog input(3.2V max input)
  * a Micro USB connection
  * Compatible with [Arduino](https://github.com/esp8266/Arduino)
  * Compatible with [nodemcu](http://www.nodemcu.com)
  * lots of [shields](./mini_shields.html)

[![D1 mini](./images/mini_v2.jpg)](./images/mini_v2.jpg)

## Getting Started

### Arduino

  * [Getting Started in Arduino](/tutorial/get_started_in_arduino.html)

### NodeMcu

  * [Getting Started in NodeMCU](/tutorial/get_started_in_nodemcu.html)

## Technical specs

|Microcontroller| ESP-8266EX |
|Operating Voltage|3.3V|
|Digital I/O Pins| 11|
|Analog Input Pins|1(Max input: 3.2V)|
|Clock Speed|80MHz/160MHz|
|Flash|4M bytes|
|Length|34.2mm|
|Width|25.6mm|
|Weight|10g|

## Documentation

### Board size
[di_mini_size.jpg](./images/di_mini_size.jpg)

### Schematics

[d1_mini.pdf](./images/d1_mini.pdf)

### Fritzing Part

[https://github.com/mcauser/Fritzing-Part-WeMos-D1-Mini](https://github.com/mcauser/Fritzing-Part-WeMos-D1-Mini)


## Pin

| Pin | Function |ESP-8266 Pin|
|TX|TXD|TXD|
|RX|RXD|RXD|
|A0|Analog input, max 3.3V input |A0|
|D0|IO|GPIO16|
|D1|IO, SCL|GPIO5|
|D2|IO, SDA|GPIO4|
|D3|IO, 10k Pull-up|GPIO0|
|D4|IO, 10k Pull-up, BUILTIN_LED|GPIO2|
|D5|IO, SCK|GPIO14|
|D6|IO, MISO|GPIO12|
|D7|IO, MOSI|GPIO13|
|D8|IO, 10k Pull-down, SS |GPIO15|
|G|Ground|GND|
|5V|5V|-|
|3V3|3.3V|3.3V|
|RST|Reset|RST|

\\
***All IO have interrupt/pwm/I2C/one-wire supported(except D0)***


## Programming

The D1 mini has a micro USB for auto programming.\\
Also you can programming it using OTA.

## Warnings
All IO is work at 3.3V.