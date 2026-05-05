# Setup Notes

This file documents the digital setup process for the PAR1 project.

## Coding Environment

The project will use Arduino IDE or Visual Studio Code with PlatformIO for ESP32-S3 development.

Current status:

- Arduino IDE / PlatformIO setup: Completed or in progress
- ESP32-S3 board support: Completed or in progress
- Required libraries: In progress

## Planned Libraries

Possible libraries for this project:

- ESP32Servo for SG90 servo motor control
- WiFi library for ESP32-S3 internet connection
- HTTPClient library for API requests
- I2S-related libraries for INMP441 microphone input
- I2S-related libraries for MAX98357 speaker amplifier output
- Adafruit SSD1306 or U8g2 library for the 0.96 inch I2C OLED screen

## API Key Preparation

The project may use an AI API such as Gemini.

Important security note:

Real API keys, Wi-Fi passwords, and private configuration files must not be uploaded to GitHub.

Files such as the following should be ignored:

- config.h
- secrets.h
- .env

Instead, an example file should be uploaded:

- config.example.h

## Hardware Notes

The current planned hardware includes:

- ESP32-S3 DevKitC-1
- 2 x INMP441 I2S digital microphone modules
- MAX98357 I2S mono speaker amplifier
- 8 Ohm 1W-2W mini speaker
- 2 x SG90 mini servo motors
- Mini pan-tilt bracket kit
- 0.96 inch I2C OLED screen
- 1200mAh LiPo battery
- TP4056 lithium battery charging module
- MT3608 DC-DC step-up voltage booster
- Male-female jumper cable set

## GitHub Repository

A GitHub repository has been created for the PAR1 project.

Initial files:

- README.md
- LICENSE
- .gitignore
- docs/project-plan.md
- docs/components-list.md
- docs/setup-notes.md
- docs/development-log.md
