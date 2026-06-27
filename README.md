# TOBY-MK1 - TOBYOS V.1 PRO Tactical Device 🌍

<div align="center">

**100% Open Source | TOBYOS V.1 PRO | ESP32**  
**Created by Antony Cleiton, 12 years old**  
**ACML DEV 2026 | Natal, RN - Brazil**

[[License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[[Status: In Development](https://img.shields.io/badge/Status-In%20Development-yellow.svg)]()
[[Hardware: Dec/2026](https://img.shields.io/badge/Hardware-Dec%2F2026-blue.svg)]()

</div>

---

## ⚠️ DOCUMENTATION DISCLAIMER

**THIS DOCUMENTATION MAY CONTAIN ERRORS. I AM 12 YEARS OLD.**  
**VERIFY ALL SCHEMATICS, CODE, AND PINOUTS BEFORE BUILDING.**  
**ACML DEV 2026 IS NOT RESPONSIBLE FOR FIRES, INJURIES, OR BROKEN DREAMS.**  
**BUILD AT YOUR OWN RISK.**

---

## 🚀 What is TOBY MK1?

**TOBY MK1** runs **TOBYOS V.1 PRO** - an offline tactical operating system on ESP32.

**Philosophy:** Pocket computer. No internet. No cloud. No tracking. Just hardware.

**Hardware Status:** Planning phase. Physical assembly scheduled for **December/2026**.

## ⚙️ Hardware - Real BOM

| Component | Model | Function in TOBYOS |
| --- | --- | --- |
| **MCU** | ESP32-WROOM-32 | Runs TOBYOS + WiFi + BT + SPI |
| **Display** | 2.8" TFT Touch ST7789 | 240x320 Touch UI + Virtual Keyboard |
| **Storage** | MicroSD Slot | Built into TFT module. TOBYOS file system |
| **GPS** | NEO-6M | GPS App - Coordinates + GPX logging |
| **Radio** | CC1101 433MHz | RF Scanner App - Detects 433MHz signals |
| **IR** | IR LED + Receiver | IR App - Clone/control TV, AC remotes |
| **Power** | 18650 3.7V | Main battery |
| **Button** | 1x Power | ON/OFF ONLY. Does NOT control apps |

**NOT INCLUDED:** RTC, FM radio, calculator, physical keypad.  
**Estimated Cost:** $50 - $65 USD

## 📱 TOBYOS V.1 PRO - 8 Independent Apps

All apps work standalone via touchscreen. No app requires another.

| App | Icon | Function |
| --- | --- | --- |
| **Settings** | ⚙️ | Adjust brightness, sound, touch calibration, WiFi AP password |
| **Wi-Fi** | 📶 | Scan 2.4GHz networks, AP mode, packet info |
| **Bluetooth** | 📡 | BLE scanner, detect beacons, RSSI |
| **IR Remote** | 📺 | Record/send IR codes. Control TV, AC |
| **RF Scanner** | 📻 | CC1101 433MHz. Detect remotes, sensors. NOT a messenger |
| **GPS Tracker** | 🗺️ | Lat/Lon/Alt/Speed. Save GPX logs to SD |
| **SCFTOS** | 📡 | SiteControlForTobyOS - Optional remote control via phone |
| **Bootloader** | 🔄 | Update TOBYOS firmware via SD card or WiFi OTA |

**SCFTOS is OPTIONAL.** Device works 100% without phone. SCFTOS just lets you control/download via browser.

## 📖 USER MANUAL - How to Use TOBY MK1

### **1. Power On/Off**
- **Turn ON:** Long press power button 2 seconds → TOBYOS boots
- **Turn OFF:** Long press power button 3 seconds → Shutdown
- **Power button does NOTHING else.** All control is via touchscreen.

### **2. Main Menu Navigation**
After boot, you see 8 app icons. **Tap any icon to open.**

