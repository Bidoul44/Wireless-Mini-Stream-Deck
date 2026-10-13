# Wireless Mini Stream Deck

A compact wireless macro pad designed and built during Hack Club's Half-Life / PCB Week.

## Project

The goal of this project is to create a small and reusable wireless controller for a computer.

The device will feature:

* 6 programmable buttons
* 3 analog potentiometers
* Bluetooth connectivity
* ESP32-S3 microcontroller
* Rechargeable LiPo battery
* USB-C charging
* Physical power switch
* Status LED
* Custom 2-layer PCB
* Custom 3D-printed enclosure

The ESP32-S3 will be mounted as a removable module so it can be reprogrammed and reused in future projects.

## How it works

The ESP32-S3 reads the six physical buttons and the three potentiometers.

The buttons can be assigned to custom keyboard shortcuts or macros, while the potentiometers can be used as analog controls.

The ESP32-S3 communicates wirelessly with the computer using Bluetooth.

The PCB integrates the controls, power system, battery connection, USB-C charging and the ESP32-S3 module.

## Hardware

The PCB is designed as a compact 2-layer board.

Main components:

* ESP32-S3 module
* 6 tactile push buttons
* 3 × 10 kΩ potentiometers
* LiPo battery
* USB-C charging circuit
* Power switch
* Status LED
* Supporting resistors and capacitors

## Firmware

The firmware is written for the ESP32-S3.

It will handle:

* Button inputs
* Potentiometer readings
* Bluetooth communication
* Custom macros
* Power management

The firmware is designed to remain reprogrammable so the functions of the controls can be changed later.

## PCB Design

The PCB and schematic are designed using KiCad.

### 3D Preview

### Schematic

## Project Status

* [x] Project concept
* [x] Component architecture
* [x] Schematic
* [x] PCB layout
* [x] PCB routing
* [x] Electrical checks
* [x] Manufacturing files
* [ ] PCB manufacturing
* [ ] Assembly
* [ ] Firmware
* [ ] Testing
* [ ] 3D printed enclosure

## Repository Structure

```text
hardware/      → KiCad schematic and PCB
firmware/      → ESP32-S3 firmware
BOM.md
JOURNAL.md
README.md
```

# Some photos :
<img width="3024" height="4032" alt="IMG_3111" src="https://github.com/user-attachments/assets/e0f62cb7-705b-4291-adc2-8368c31354a5" />
<img width="3024" height="4032" alt="IMG_3110" src="https://github.com/user-attachments/assets/37e2b6a0-b11f-43e8-9185-6cbb54f2a5f8" />
<img width="3024" height="4032" alt="IMG_3109" src="https://github.com/user-attachments/assets/b867da55-3685-41da-8b41-281f99bf17e1" />
