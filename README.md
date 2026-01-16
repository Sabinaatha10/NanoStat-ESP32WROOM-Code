# NanoStat Firmware – ESP32-WROOM-32E

## 1. Background
This project is based on the paper:

Shawn Chia-Hung Lee, Peter J. Burke  
“NanoStat: An open source, fully wireless potentiostat”  
Electrochimica Acta, 2022  
DOI: https://doi.org/10.1016/j.electacta.2022.140481

Original repository:
https://github.com/PeterJBurke/Nanostat

The original implementation uses ESP32-PICO hardware
and provides a fully wireless potentiostat system with
a web-based user interface.

## 2. Purpose of This Repository
This repository is created for academic purposes (Kerja Praktik).

The main focus of this work is:
- Studying the firmware architecture of NanoStat
- Adapting the firmware to a different ESP32 module
- Ensuring compatibility with existing web interface and communication flow

## 3. Hardware Adaptation
### ESP32-PICO → ESP32-WROOM-32E

Changes performed in this repository include:
- Board configuration updates in `platformio.ini`
- Pin remapping and minor compatibility adjustments in `main.cpp`
- Verification that the firmware builds successfully on ESP32-WROOM-32E

No physical hardware testing has been performed at this stage.

## 4. Current Project Status
- Hardware is not yet available
- Focus is on firmware structure and web interface
- Sensor integration and hardware validation will be done in a later phase

## 5. Build Environment
- PlatformIO
- ESP32-WROOM-32E
- Visual Studio Code

## 6. Web Interface
The web-based UI files are located in the `data/` directory
and are uploaded to the ESP32 filesystem (SPIFFS/LittleFS).

## 7. License and Acknowledgment
This project follows the original NanoStat license (MIT License).

All credit for the original design, concept, and implementation
belongs to the original authors.
