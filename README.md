# ESP32-Projects
Tutorials and Example learning Projects from zero to hero  
Welcome to my **ESP32 Projects** repository!  
This collection showcases various experiments and real-world applications using the **ESP32 microcontroller** — from basic LED control to advanced IoT and cloud-connected systems.
Each project is designed to be simple, educational, and inspiring for developers interested in **IoT, embedded systems, and automation**.

## About ESP32
The **ESP32**, developed by **Espressif Systems**, is a powerful and versatile microcontroller featuring:
- Dual-core processor  
- Built-in Wi-Fi and Bluetooth  
- Low power consumption  
- Ideal for IoT, robotics, and automation projects

It allows you to connect everyday electronics to the internet — making smart systems easier than ever to build.

## Project List
🧠 ESP32 Project List — C / C++ / ESP-IDF / Arduino
| 🗂️ **Category**        | ⚙️ **Module**                | 💡 **Example Project** | 🧾 **Description**                              | 💻 **Language / Framework** |
| ----------------------- | ---------------------------- | ---------------------- | ----------------------------------------------- | --------------------------- |
| 🔌 **GPIOs**            | Input / Output               | `gpio_toggle`          | LED blink, button input, digital I/O            | C / Arduino / ESP-IDF       |
| 🧩 **System Core**      | Timer / RTC                  | `esp_timer_demo`       | High-resolution timer, wake-up, real-time clock | C / ESP-IDF                 |
|                         | Watchdog                     | `watchdog_demo`        | Task watchdog / main watchdog timer usage       | C / ESP-IDF                 |
| ⚡ **Analog**            | ADC                          | `adc_read`             | Read analog sensor values                       | C / ESP-IDF / Arduino       |
|                         | DAC                          | `dac_output`           | Generate analog waveforms                       | C / ESP-IDF                 |
| 🧮 **Computing**        | SPIFFS / Flash               | `spiffs_demo`          | File storage on internal flash                  | C / ESP-IDF                 |
| ⏱️ **Timers / PWM**     | LEDC / PWM                   | `pwm_led`              | LED brightness control, motor PWM               | C / ESP-IDF / Arduino       |
| 🔗 **Connectivity**     | Wi-Fi                        | `wifi_ap_sta`          | Wi-Fi access point + station mode example       | C / ESP-IDF / Arduino       |
|                         | BLE                          | `ble_server`           | Bluetooth Low Energy peripheral example         | C / ESP-IDF / Arduino       |
|                         | UART / Serial                | `uart_console`         | Serial communication, logging                   | C / ESP-IDF / Arduino       |
|                         | I2C                          | `i2c_sensor`           | Read/write I2C sensors                          | C / ESP-IDF / Arduino       |
|                         | SPI                          | `spi_lcd`              | Communicate with SPI devices (LCD, sensors)     | C / ESP-IDF / Arduino       |
|                         | CAN                          | `can_bus_demo`         | CAN communication (ESP32-CAN module)            | C / ESP-IDF                 |
| 🎧 **Multimedia**       | I2S                          | `i2s_audio`            | Audio streaming / playback                      | C / ESP-IDF                 |
| 🔒 **Security**         | RNG / Flash Encryption       | `rng_demo`             | Hardware RNG, secure boot / flash encryption    | C / ESP-IDF                 |
| 🖥️ **Displays**        | OLED / TFT / LCD             | `oled_display`         | Display sensor data, text, graphics             | C / Arduino / ESP-IDF       |
| 🌡️ **Sensors**         | Temperature / Humidity / IMU | `sensor_read`          | Read various sensors via I2C/SPI                | C / Arduino / ESP-IDF       |
| ⌨️ **Keyboard / Input** | Button / Touch               | `touch_sensor`         | Capacitive touch input or button scanning       | C / Arduino / ESP-IDF       |
| 📡 **Modules / IoT**    | MQTT / HTTP / WebSocket      | `mqtt_publish`         | IoT cloud connectivity example                  | C / ESP-IDF / Arduino       |
| 💾 **Storage**          | SD Card / SPIFFS / LittleFS  | `sdcard_demo`          | File logging on SD or internal flash            | C / ESP-IDF / Arduino       |
| 🧪 **Advanced**         | PWM Motor / Servo            | `servo_control`        | Motor / servo control with PWM                  | C / Arduino / ESP-IDF       |
| 🔋 **Power Management** | Deep Sleep / Wakeup          | `deep_sleep_demo`      | Low power modes and wakeup sources              | C / ESP-IDF                 |


> 🧠 New projects are added regularly — stay tuned!

---
## ⚙️ Getting Started

### Requirements
- ArduinoIED
- ESP-IDF and ESP-IDE
- PlatformIO
- ESP32 Module
- USB to USART TTL
- and so end

---
### 📝 ESP32 Project Requirements
1. 🖥️ Hardware
🟢 ESP32 board (examples: ESP32-WROOM-32, ESP32-WROVER, ESP32-S2, ESP32-C3)
🔌 Peripherals / Modules depending on the project:
💡 LEDs, 🔘 buttons, ⌨️ keypads, 🌡️ sensors (temperature, humidity, IMU)
🖥️ OLED / TFT / LCD displays
💾 SD card or SPI flash modules
🔗 I2C / SPI devices (EEPROM, ADC, DAC, etc.)
🏎️ Motors / Servos (PWM control)
📡 CAN / BLE / Wi-Fi connectivity modules (if not onboard)

3. 🛠️ Software / Toolchain
⚙️ ESP-IDF (Espressif IoT Development Framework)
Required for most advanced C projects, FreeRTOS support, Wi-Fi/BLE, peripherals
📝 Arduino IDE / PlatformIO (optional)
Simplified C/C++ development for GPIO, sensors, and displays
🖱️ Compiler / Toolchain
GCC for Xtensa or RISC-V (depending on ESP32 variant)
🐍 Python 3.x (required for ESP-IDF build system)

4. 📚 Libraries / Dependencies
Peripheral drivers (ADC, DAC, PWM, I2C, SPI, UART, I2S, CAN, etc.)
🖥️ Display libraries (U8g2, TFT_eSPI)
🌡️ Sensor libraries (Adafruit Sensor libraries, MPU6050, BME280, etc.)
🌐 Networking / IoT libraries (MQTT, HTTP client, WebSocket, BLE libraries)

5. 🧠 Knowledge / Skills
💻 C / C++ programming
🛠️ Embedded programming concepts:
🔌 GPIO control, 🌡️ ADC/DAC, 🏎️ PWM, ⏱️ Timers, ⚡ Interrupts
🕹️ FreeRTOS tasks and synchronization (optional but recommended)
🔋 Power management (deep sleep, wakeup)
🔗 Communication protocols: UART, SPI, I2C, CAN, BLE, Wi-Fi
⚡ Basic electronics for sensor interfacing and motor control

6. 🧰 Optional Tools
💬 Serial terminal (e.g., PuTTY, minicom) for debugging
📊 Oscilloscope / Logic analyzer (for advanced peripheral debugging)
🐙 Git / GitHub (to clone and manage open-source projects)
⚡ PlatformIO (for easier project management and library integration)
