# ESP32Marauder for ESP32-2432S024R with USB-C 🚀✨

ESP32 with 2.4-inch 240x320 LCD TFT Module and Touch 📺👆

![ESP32-2432S024R](https://github.com/b00mekk/ESP32-Marauder-ESP32-2432S024R/blob/main/ESP32-Arduino-LVGL-WIFI-Bluetooth-Development-Board-2-4-240-320-Smart-Display-Screen-2-4inch.jpg_.png?raw=true)

## Tested on:
- [Module 1](https://s.click.aliexpress.com/e/_DD5uQKp) 🛒🌟

## How to Setup

1. **Update TFT_eSPI/User_Setup.h**:
   - Replace the contents of `TFT_eSPI/User_Setup.h` with the [updated version](https://github.com/b00mekk/ESP32-Marauder-ESP32-2432S024R/blob/main/User_Setup.h). 📄🔄

2. **Download Files**:
   - Download the [esp32_marauder](https://github.com/b00mekk/ESP32-Marauder-ESP32-2432S024R/tree/main/esp32_marauder) files. 📁💾

3. **Upload to ESP32-2432S024R**:
   - Use USB-C to upload the files to your ESP32-2432S024R. 🔌💻

## Pre-built Binaries

1. **Visit the Flasher Page**:
   - Go to the flasher page: [esp.huhn.me](https://esp.huhn.me/). 🌐🔗

2. **Flash the Binaries**:
   - Flash the binaries included in the `esp32_marauder/build/esp32.esp32.d32_pro/` folder in the following order:

     1. **Bootloader** - Address: `0x1000` 🔑
     2. **Partitions** - Address: `0x8000` 🗄️
     3. **ESP32 Marauder Bin** - Address: `0x10000` 💽

3. **Alternative Flashing Method**:
   - You can also use the **ESP32 Flash Download Tool** to flash the binaries. 🛠️💻

![Flashing Process](https://github.com/user-attachments/assets/b1dead25-7606-485b-9831-5a0921b3bc0e)
