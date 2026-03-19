# Project Configuration: LOLIN-ESP32-OLED

## Hardware Configuration
- **Board:** WEMOS LOLIN32 (ESP32)
- **OLED Display:** SSD1306 (I2C)
  - **Address:** `0x3C`
  - **SDA Pin:** `5`
  - **SCL Pin:** `4`
- **Serial Baud Rate:** `115200`

## Software Environment
- **Platform:** `espressif32`
- **Framework:** `arduino`
- **Library Dependencies:**
  - `thingpulse/ESP8266 and ESP32 OLED driver for SSD1306 displays @ ^4.4.0`

## Development Workflow
- **Build & Flash:** Use `pio run --target upload`
- **Serial Monitor:** Use `pio device monitor`
- **Boot Mode:** If flashing fails, hold the **BOOT** button on the board during the "Connecting..." phase.
