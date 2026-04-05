# ESP32 Music Player

A high-performance music player built using **ESP-IDF** and **FreeRTOS**. 

## ✨ Features
- High-quality audio via **VS1053B** codec.
- Music storage on **SD Card** (SPI).
- UI display on **SSD1306 OLED** (I2C).
- Interactive control via **Rotary Encoder** and buttons.
- (Planned) WiFi/Bluetooth file transfer.

## 🛠️ Hardware Requirements
| Component | Connection Type |
|-----------|-----------------|
| ESP32     | MCU             |
| VS1053B   | SPI             |
| SSD1306   | I2C             |
| MicroSD   | SPI             |

## 🚀 Getting Started
1. Clone this repository.
2. Set up the ESP-IDF environment (v5.x recommended).
3. Run `idf.py menuconfig` to configure your GPIO pins under **Hardware Configuration**.
4. Run `idf.py build flash monitor`.

## 📌 Pinout
Configuration is handled via Kconfig. Open the menuconfig to view or change default pins.
