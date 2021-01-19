# ESP-WROOM-32 (30P)

48 pins with different functions come with the ESP32 chip. However, not all pins are suitable for use in Devkit. There are also concerns about how to use the GPIOs for the ESP32. What pins are you going to use? What pins in your projects can you avoid using? The goal of this repo is to be a quick and easy reference guide for the ESP32 GPIOs to follow. If you're familiar with ESP8266, its successor is ESP32. ESP32 is a low-cost, low-power 32-bit dual-core microcontroller incorporates wireless WiFi and Bluetooth capabilities created by Espressif Systems. The ESP32 has developed a reputation as the ultimate chip or module for hobbyists and IoT developers, most frequently designed for handheld devices, wearable technology, and IoT applications.

Here’s a high-level summary of the features and specifications of the ESP32:
| ESP32  | Specifications |
| ------------- | ------------- |
| Core  | 2  |
| Architecture  | 32-bit  |
| Clock  | 160MHZ, up to 240MHz  |
| Bluetooth  | classic & BLE 4.2  |
| Wi-Fi  | TCP/IP, full 802.11 b/g/n/e/i WLAN MAC protocol  |
| RAM  | 512 KB  |
| Flash  | 4MB, up to 16MB  |
| Peripherals  | ADC,DAC,PWM,UART,SPI,I2C,I2S,CAN,Capacitive GPIO...  |

We're going to use the ESP32 DEVKIT DOIT board as shown in the figure below, as a guide for this repo. But the information on this page is also compatible with the ESP-WROOM-32 chip for other ESP32 development boards. The ESP32 devkit uses the module ESP-WROOM-32. But across all ESP32 development boards, the functionality of all GPIO pins is the same.

![alt text](https://startingelectronics.org/articles/ESP32-WROOM-testing/doit-esp-wroom-32-devkit.jpg)

About this development board, I see many people searching online. Are there several individuals asking questions about how to use their GPIO pins? What GPIO pin is a digital input-output pin that can be used? What GPIO pin is an analog pin that can be used? And which pin should not be used in order to safely use this board? In this post, you will get the answer to these questions. You will get the answer to these questions in this repo.

