# Awesome ESP with stars

A curated list of awesome ESP8266/32 projects and code.

<a href="http://espressif.com/en/products/hardware/esp8266ex/overview"><img src="img/esp8266.jpg" alt="ESP8266" align="left" style="margin-right: 25px" height=150></a> <a href="http://espressif.com/en/products/hardware/esp32/overview"><img src="https://pbs.twimg.com/profile_images/863510403120222208/rjVOiTe3.jpg" alt="ESP32" align="left" style="margin-right: 25px" height=150></a>

> Both the [ESP8266](http://espressif.com/en/products/hardware/esp8266ex/overview) and the [ESP32](http://espressif.com/en/products/hardware/esp32/overview) are low-cost Wi-Fi microchips with full TCP/IP stack and microcontroller capabilities produced by the Shanghai-based manufacturer Espressif Systems. <br/>
> See [Contributing](contributing.md) for information on how to contribute to this list. <br/><br/>

***

## Contents

* [Firmware](#firmware)
* [Tools](#tools)
* [Projects](#projects)
  * [Smart Home and IoT](#smart-home-and-iot)
  * [InfoSec](#infosec)
  * [Biomedical](#biomedical)
  * [LoRa](#lora)
  * [Music and Audio](#music-and-audio)
  * [Smartwatches](#smartwatches)
  * [Others](#others)
* [Libraries](#libraries)

## Firmware

* [MicroPython](https://github.com/micropython/micropython/) ⭐ 22,009 | 🐛 1,539 | 🌐 C | 📅 2026-08-25 - An implemention of Python3 for the ESP8266 and 32.
* [RT-Thread](https://github.com/RT-Thread/rt-thread) ⭐ 12,166 | 🐛 492 | 🌐 C | 📅 2026-08-24 - Chinese open source firmware available for the ESP32.
* [NodeMCU](https://github.com/nodemcu/nodemcu-firmware) ⭐ 7,942 | 🐛 119 | 🌐 C | 📅 2026-06-07 - An eLua-based firmware for the ESP8266.
* [MongooseOS](https://github.com/cesanta/mongoose-os) ⭐ 2,663 | 🐛 97 | 🌐 C | 📅 2026-07-26 - An IoT specific firmware, with both C and JS. Available for the ESP32/8266.
* [ESP3D](https://github.com/luc-github/ESP3D) ⭐ 1,990 | 🐛 5 | 🌐 C | 📅 2026-07-22 - An experimental firmware for 3D Printers, both the ESP32 and 8266.
* [Sming Framework](https://github.com/SmingHub/Sming) ⭐ 1,569 | 🐛 82 | 🌐 C++ | 📅 2026-07-20 - Superb C/C++ IoT Framework with support for ESP8266 and ESP32.
* [Frankenstein](https://github.com/nekromant/esp8266-frankenstein) ⭐ 326 | 🐛 7 | 🌐 C | 📅 2020-06-03 - A quick and dirty firmware with cool features for the ESP8266.
* [Espressif AT](http://bbs.espressif.com/) - The default vanilla firmware for the ESP8266.
* [ESPBasic](http://www.esp8266basic.com/) - A BASIC firmware for easy and wireless programming, ready for the 8266.
* [DeviceHive](https://devicehive.com/) - A firmware made as a client for DeviceHive's IoT data platform, only for the 8266.

## Tools

* [Arduino Core/32](https://github.com/espressif/arduino-esp32) ⭐ 17,281 | 🐛 159 | 🌐 C++ | 📅 2026-08-25 - The other Arduino core for the ESP32.
* [Arduino Core/8266](https://github.com/esp8266/arduino) ⭐ 16,668 | 🐛 406 | 🌐 C++ | 📅 2026-07-29 - The Arduino core for the ESP8266.
* [PlatformIO](https://github.com/platformio/platformio-core) ⭐ 9,421 | 🐛 316 | 🌐 Python | 📅 2026-08-22 - Cross Platform IDE and Debugger that supports both the ESP32 and ESP8266.
* [ESPTool](https://github.com/espressif/esptool) ⭐ 6,456 | 🐛 16 | 🌐 Python | 📅 2026-08-20 - Espressif's command line tool for bootloader comms in both ESP's.
* [Tuya-Convert](https://github.com/ct-Open-Source/tuya-convert) ⭐ 5,074 | 🐛 215 | 🌐 Python | 📅 2024-09-06 - A Wi-Fi firmware flasher ESP8266 that has been pre-loaded with Tuya firmware.
* [NodeMCU Flasher](https://github.com/nodemcu/nodemcu-flasher) ⭐ 2,215 | 🐛 47 | 🌐 Pascal | 📅 2017-08-08 - The official flashing tool for the NodeMCU OS.
* [ESP-Open-SDK](https://github.com/pfalcon/esp-open-sdk) ⭐ 1,988 | 🐛 139 | 🌐 Makefile | 📅 2022-01-12 - An open SDK for the ESP8266.
* [Tasmotizer](https://github.com/tasmota/tasmotizer) ⭐ 1,537 | 🐛 38 | 🌐 Python | 📅 2024-01-30 - A graphical flashing tool for Tasmota firmware. Can manage Wi-Fi & MQTT settings, modules & templates.
* [LuaNode](https://github.com/Nicholas3388/LuaNode) ⭐ 1,332 | 🐛 36 | 🌐 C | 📅 2024-05-30 - A lua-only SDK for 32/8266.
* [Arduino FS Plugin](https://github.com/esp8266/arduino-esp8266fs-plugin) ⭐ 737 | 🐛 57 | 🌐 Java | 📅 2022-11-30 - An Arduino plugin for filesystem uploads in the 8266.
* [ESPTool-ck](https://github.com/igrr/esptool-ck) ⭐ 370 | 🐛 41 | 🌐 C | 📅 2020-12-21 - A CLI tool for flashing in the ESP8266.
* [ESPTool-gui](https://github.com/Rodmg/esptool-gui) ⭐ 204 | 🐛 0 | 🌐 C++ | 📅 2022-09-19 - A flashing GUI tool based on ESPTool-ck.
* [ESP Flash Tool](http://espressif.com/en/support/download/other-tools) - The vanilla firmware flasher for both ESP's.

## Projects

### Smart Home and IoT

* [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) ⭐ 4,081 | 🐛 51 | 🌐 C++ | 📅 2026-08-25 - An implementation of a multiprotocol MQTT gateway for both ESP's among other devices.
* [ESPEasy](https://github.com/letscontrolit/ESPEasy) ⭐ 3,567 | 🐛 381 | 🌐 C++ | 📅 2026-08-24 - Easily turn ESP modules into multifunction sensor devices for home automation systems.
* [Sonoff-Homekit](https://github.com/Gruppio/Sonoff-Homekit) ⭐ 1,004 | 🐛 2 | 🌐 C | 📅 2025-04-16 - An alternative firmware for Sonoff devices (and other 8266 devices) which allows control through Apple's Homekit.
* [HomePoint](https://github.com/sieren/Homepoint) ⭐ 661 | 🐛 29 | 🌐 C | 📅 2022-08-04 - Control MQTT/HomeKit smart home devices from an ESP32-powered screen.
* [SuperGreenOS](https://github.com/supergreenlab/SuperGreenOS) ⭐ 220 | 🐛 0 | 🌐 C | 📅 2024-06-05 - A full-featured home farming automation software for the ESP32.
* [EPaperWeatherDisplay](https://github.com/henri98/esp32-e-paper-weatherdisplay) ⭐ 169 | 🐛 0 | 🌐 C | 📅 2020-10-31 - A very cute e-ink weather display using the ESP32.
* [CanAirIO](https://github.com/kike-canaries/canairio_firmware#canairio-firmware) ⭐ 129 | 🐛 29 | 🌐 C++ | 📅 2026-08-18 - Citizen science project that uses mobile and fixed stations to measure air quality with ESP32 and smartphones.
* [DoorsignEPD](https://github.com/jamct/DoorsignEPD) ⭐ 103 | 🐛 11 | 🌐 PHP | 📅 2024-09-29 - A smart doorsign with an E-Paper display using the ESP32.
* [ESPHome](https://esphome.io/) - A full-featured system for controlling ESP's through simple yet powerful configuration files and Home Automation systems.
* [Tasmota](https://tasmota.github.io/docs/) - An alternative firmware for Sonoff & other ESP8266/ESP32 devices. Includes a large collection of sensor drivers & integrates with [Home Assistant](https://www.home-assistant.io/) natively or via MQTT.
* [openHASP](https://www.openhasp.com/) - Control your home automation devices from a customizable touchscreen UI connected via MQTT.

### InfoSec

* [ESP8266 Deauther](https://github.com/spacehuhn/esp8266_deauther) ⭐ 14,938 | 🐛 99 | 🌐 C | 📅 2024-08-14 - A very cool pseudojammer (deauther) of Wifi networks that uses the ESP8266.
* [ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) ⭐ 12,110 | 🐛 328 | 🌐 C++ | 📅 2026-08-25 - An integrated suite of offensive and defensive tools for WiFi and Bluetooth.
* [WiFiDuck](https://github.com/spacehuhn/WiFiDuck) ⭐ 3,274 | 🐛 22 | 🌐 C++ | 📅 2023-06-02 - A wireless-enabled keystroke injector, analogous, but even more awesome than the Rubber Ducky.
* [ESP8266 Beacon Spam](https://github.com/spacehuhn/esp8266_beaconSpam) ⭐ 1,365 | 🐛 25 | 🌐 C++ | 📅 2024-08-08 - Want to confuse people? This device creates hundreds of fake WiFi networks.
* [DeauthDetector](https://github.com/spacehuhn/DeauthDetector) ⭐ 972 | 🐛 19 | 🌐 C++ | 📅 2023-08-28 - A small device that shines a light if it detects a WiFi deauth attack. Made by the same guy as the last six projects.
* [ArduinoPcap](https://github.com/spacehuhn/ArduinoPcap) ⭐ 463 | 🐛 15 | 🌐 C++ | 📅 2024-03-03 - A library which allows generation of .pcap files with network traffic, for both ESP's.
* [PacketMonitor](https://github.com/spacehuhn/PacketMonitor32) ⭐ 402 | 🐛 7 | 🌐 C++ | 📅 2020-11-20 - A beautiful OLED monitor for packet activity in a WiFi channel. Two versions for each ESP.
* [ESP32-BLECollector](https://github.com/tobozo/ESP32-BLECollector) ⭐ 362 | 🐛 1 | 🌐 C | 📅 2024-09-04 - A wardriving device which displays BLE devices and collects data from them, all in a nice screen interface.
* [WiFi Satellite](https://hackaday.io/project/28831-wifi-satellite-34c3) - A giant Wifi "satellite" that can monitor all 14 2.4Ghz channels using, well, 14 ESP32s.

### Biomedical

* [HeartyPatch](https://heartypatch.protocentral.com/) - A wearable BLE and WiFi connected ECG-HR patch which uses the ESP32.
* [HealthyPi v4](https://www.crowdsupply.com/protocentral/healthypi-v4-unplugged) - An amazing open source vital signs monitor that can monitor ECG, respiration, pulse oximetry and body temperature, all run by an ESP32.

### LoRa

* [ESP32-Paxcounter](https://github.com/cyberman54/ESP32-Paxcounter#esp32-paxcounter) ⭐ 2,086 | 🐛 18 | 🌐 C++ | 📅 2026-08-12 - Wifi & Bluetooth driven, LoRaWAN enabled, battery powered mini Paxcounter built on cheap ESP32 LoRa IoT boards.
* [Meshtastic](https://www.meshtastic.org/) - ESP32 LoRA boards as secure, long battery life, mesh GPS communicators.
* [Disaster Radio](https://disaster.radio/) - A disaster-resilient communications network powered by the sun.

### Music and Audio

* [Squeezelite-esp32](https://github.com/sle118/squeezelite-esp32) ⭐ 2,171 | 🐛 89 | 🌐 C | 📅 2026-07-30 - Streaming audio receiver with multi-room sync, AirPlay, Bluetooth, hardware buttons, display and more.
* [ESP32-Radio](https://github.com/Edzelf/ESP32-Radio) ⭐ 1,065 | 🐛 343 | 🌐 C++ | 📅 2024-10-21 - Internet radio based on ESP32, VS1053 and a TFT screen.
* [PedalinoMini](https://github.com/alf45tar/PedalinoMini) ⭐ 613 | 🐛 47 | 🌐 Python | 📅 2026-05-04 - A wireless MIDI pedal controller for guitarists, built with the ESP32.
* [ESPuino](https://github.com/biologist79/ESPuino) ⭐ 417 | 🐛 5 | 🌐 C++ | 📅 2026-08-16 - RFID-controlled music player powered by ESP32.
* [Alles](https://github.com/bwhitman/alles) ⭐ 322 | 🐛 2 | 🌐 C | 📅 2024-11-04 - A many speaker distributed music synthesizer using UDP multicast over WiFi, modeled after the alles machine/AMY.
* [ThingPulse esp8266-spotify-remote](https://github.com/ThingPulse/esp8266-spotify-remote) ⭐ 273 | 🐛 1 | 🌐 C | 📅 2023-09-30 - Control your Spotify player from a ESP8266 with color touch display.
* [Knobby](https://github.com/quadule/knobby) ⭐ 213 | 🐛 1 | 🌐 C | 📅 2025-12-14 - A handheld Spotify remote that encourages you to explore unfamiliar music.

### Smartwatches

* [StickWatch](https://github.com/eggfly/StickWatch) ⭐ 96 | 🐛 2 | 🌐 C++ | 📅 2022-10-02 - A smartwatch module based on the M5Stick, using the ESP32.
* [mutantW\_V1](https://mutantcybernetics.com/mutantW_V1.html) - An ESP32 based open source smartwatch with 1.7 inch display, WiFi, Bluetooth, NeoPixel and vibration.
* [Open SmartWatch](https://open-smartwatch.github.io/) - A FOSS smartwatch with GPS, an inertial unit and an extremely cool 3D-printed case.
* [Watchy](https://watchy.sqfmi.com) - An open source e-paper watch with lots of options for customization.

### Others

* [DroneBridge](https://github.com/DroneBridge/ESP32) ⭐ 1,078 | 🐛 7 | 🌐 C | 📅 2026-08-24 - An implementation of DroneBridge, a signal link for drones and UAV's on the ESP32.
* [SoftRF](https://github.com/lyusupov/SoftRF) ⭐ 1,005 | 🐛 0 | 🌐 C | 📅 2026-08-24 - A DIY aviation proximity awareness system that can be used in UAV projects.
* [Retro ESP32](https://github.com/retro-esp32/RetroESP32) ⭐ 723 | 🐛 21 | 🌐 C | 📅 2024-07-31 - An extremely cool launcher for the Odroid Go (with the ESP32), which allows emulating several retro consoles.
* [FreeTouchDeck](https://github.com/DustinWatts/FreeTouchDeck) ⭐ 710 | 🐛 0 | 🌐 C | 📅 2024-05-22 - Open source touch macropad and stream control deck with built-in web configurator.
* [E-TKT](https://github.com/andreisperid/E-TKT) ⭐ 473 | 🐛 20 | 🌐 C++ | 📅 2023-05-04 - An ESP32 powered DIY label maker that mixes both old fashioned and contemporary technology.
* [WirelessPrinting](https://github.com/probonopd/WirelessPrinting) ⭐ 382 | 🐛 32 | 🌐 C++ | 📅 2023-04-24 - Print wirelessly from Cura, PrusaSlicer or Slic3r to your 3D printer connected to an ESP module.
* [SmartSpin2k](https://github.com/doudar/SmartSpin2k) ⭐ 277 | 🐛 26 | 🌐 C++ | 📅 2026-08-24 - Transform your spin bike into a smart trainer with automatic resistance knob control in fitness apps like Zwift.
* [WLED](https://kno.wled.ge/) - Control many types of RGB(W) LED strips with an ESP8266 or ESP32 over WiFi.

## Libraries

* [Wasm3](https://github.com/wasm3/wasm3) ⭐ 7,999 | 🐛 40 | 🌐 C | 📅 2026-08-24 - A lightning fast WebAssembly interpreter designed for embedded devices, compatible with both ESP's.
* [IRremoteESP8266](https://github.com/markszabo/IRremoteESP8266) ⭐ 3,572 | 🐛 103 | 🌐 C++ | 📅 2026-08-23 - Emit and receive IR signals in the ESP8266.
* [ESPAudio](https://github.com/earlephilhower/ESP8266Audio) ⭐ 2,390 | 🐛 0 | 🌐 C | 📅 2026-08-02 - Library for playing a diverse range of audio formats in the ESP8266/ESP32.
* [TinyGSM](https://github.com/vshymanskyy/TinyGSM) ⭐ 2,212 | 🐛 354 | 🌐 C++ | 📅 2026-07-21 - A quick and simple Arduino library for interaction with GSM modules which can also control the 8266 through AT commands.
* [HomeSpan](https://github.com/HomeSpan/HomeSpan) ⭐ 2,150 | 🐛 9 | 🌐 C++ | 📅 2026-08-24 - A robust and extremely easy-to-use Arduino library for creating your own ESP32-based HomeKit devices.
* [mJS](https://github.com/cesanta/mjs) ⭐ 2,054 | 🐛 196 | 🌐 C | 📅 2026-03-16 - A lightweight and restricted JS engine that is used by MongooseOS, compatible on the 32 and 8266.
* [LedFx](https://github.com/LedFx/LedFx) ⭐ 2,030 | 🐛 15 | 🌐 Python | 📅 2026-08-24 - A library for using audio input to create realtime light shows. LedFx can control multiple devices and works great with cheap ESP8266 nodes.
* [ESP32-audioI2S](https://github.com/schreibfaul1/ESP32-audioI2S) ⭐ 1,678 | 🐛 29 | 🌐 C | 📅 2026-08-24 - Plays mp3, m4a and wav files from SD card or stream via I2S interface.
* [ESP-Dash](https://github.com/ayushsharma82/ESP-DASH) ⭐ 1,398 | 🐛 0 | 🌐 C++ | 📅 2025-11-22 - Beautiful and fast framework for creating remote dashboards in the 8266/32. No internet required.
* [Homie8266](https://github.com/marvinroger/homie-esp8266) ⭐ 1,371 | 🐛 89 | 🌐 HTML | 📅 2026-03-06 - Framework implementation of the Homie protocol for the 8266.
* [GUIslice](https://github.com/ImpulseAdventure/GUIslice) ⭐ 1,361 | 🐛 48 | 🌐 C | 📅 2026-07-14 - A drag and drop GUI framework for several devices and screen controllers. Compatible with 8266 and 32.
* [ESP\_mqtt](https://github.com/tuanpmt/esp_mqtt) ⭐ 1,172 | 🐛 41 | 🌐 C | 📅 2020-12-22 - MQTT helper library for the ESP8266.
* [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) ⭐ 1,165 | 🐛 33 | 🌐 C | 📅 2023-12-18 - Homekit implementation for 8266 on RTOS.
* [ESPUI](https://github.com/s00500/ESPUI) ⭐ 1,124 | 🐛 53 | 🌐 C++ | 📅 2026-04-30 - A simply library for making interactive web interfaces for both ESP's.
* [AsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP) ⚠️ Archived - Asynchronous TCP Library for both the 8266 and the 32.
* [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) ⭐ 719 | 🐛 55 | 🌐 Python | 📅 2025-08-18 - A very powerful MicroPython web server which can be used in the ESP32.
* [TFTLibrary](https://github.com/loboris/ESP32_TFT_library) ⭐ 658 | 🐛 65 | 🌐 C | 📅 2024-06-19 - TFT compatibility for the ESP32.
* [WiFiESP](https://github.com/bportaluri/WiFiEsp) ⭐ 571 | 🐛 134 | 🌐 C++ | 📅 2024-03-26 - Arduino library for Wifi management, client/server for 8266 board.
* [Free802.11](https://github.com/Jeija/esp32free80211) ⭐ 570 | 🐛 7 | 🌐 C | 📅 2022-01-24 - Library to emit arbitrary 802.11 signals with the ESP32.
* [painlessMesh](https://github.com/gmag11/painlessMesh) ⭐ 563 | 🐛 0 | 🌐 C++ | 📅 2019-08-29 - A library that takes care of the particulars of creating a simple mesh network using ESP8266 and ESP32 hardware.
* [esphomelib](https://github.com/OttoWinter/esphomelib) ⚠️ Archived - Framework to integrate with HomeAssistant in the 8266.
* [ESP8266Wifi](https://github.com/ekstrand/ESP8266wifi) ⭐ 463 | 🐛 41 | 🌐 C++ | 📅 2018-06-28 - Simple Arduino Wifi library for the 8266.
* [ESPHelper](https://github.com/ItKindaWorks/ESPHelper) ⭐ 328 | 🐛 3 | 🌐 C++ | 📅 2025-06-18 - MQTT and Wi-fi automation-oriented library for the 8266.
* [WifiEspNow](https://github.com/yoursunny/WifiEspNow) ⭐ 293 | 🐛 7 | 🌐 C++ | 📅 2026-03-18 - Arduino library for [ESP-NOW](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/network/esp_now.html), a connectionless WiFi communication protocol defined by [Espressif](https://github.com/espressif).
* [ESP32 ePaper](https://github.com/loboris/ESP32_ePaper_example) ⭐ 243 | 🐛 12 | 🌐 C | 📅 2018-11-25 - A full-featured library for using ePaper modules with the ESP32.
* [TTS](https://github.com/jscrane/TTS) ⭐ 216 | 🐛 5 | 🌐 C | 📅 2023-06-29 - A somehow good text to speech library for several Arduino devices, both ESP's included.
* [TinyUPnP](https://github.com/ofekp/TinyUPnP) ⭐ 110 | 🐛 22 | 🌐 C++ | 📅 2024-08-16 - A lightweight UPnP IGD library for automatic port forwarding on the 8266 and 32.
* [UTFT-ESP](https://github.com/gnulabis/UTFT-ESP) ⭐ 93 | 🐛 7 | 🌐 C | 📅 2019-09-06 - UTFT Support for the ESP32/8266.
* [Koyn](https://github.com/elkrem/koyn) ⭐ 66 | 🐛 1 | 🌐 C++ | 📅 2019-05-31 - A decentralized Bitcoin library for the ESP32 and the ESP8266.
* [ESPHelper/32](https://github.com/ItKindaWorks/ESPHelper32) ⭐ 53 | 🐛 1 | 🌐 C++ | 📅 2019-04-02 - Port of the ESPHelper library for the 32.
* [Esp32SSHClient](https://github.com/J-Rios/Arduino-esp32sshclient) ⭐ 53 | 🐛 2 | 🌐 C | 📅 2022-10-29 - A library that implements a SSH client in the ESP32.
* [CanAirIO SensorLib](https://github.com/kike-canaries/canairio_sensorlib#canairio-air-quality-sensors-library) ⭐ 45 | 🐛 12 | 🌐 C++ | 📅 2026-08-13 - ESP32/8266 library with auto-configuration of multiple PM2.5, CO2 and environment sensors.
* [Dhyara](https://github.com/neel/dhyara) ⭐ 21 | 🐛 1 | 🌐 C++ | 📅 2021-12-20 - A C/C++ library for making a Mobile Ad hoc Network (MANET) using ESP Now.
* [go-mcu](https://github.com/matiasinsaurralde/go-mcu) ⭐ 14 | 🐛 6 | 🌐 Go | 📅 2021-01-14 - Golang package for interacting with NodeMCU-based boards.
* [LVGL](https://lvgl.io) - An open-source graphics library providing everything you need to create embedded GUIs with easy-to-use graphical elements, beautiful visual effects and low memory footprint.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
