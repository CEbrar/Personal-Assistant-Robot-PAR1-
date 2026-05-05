# Personal-Assistant-Robot-PAR1-
# PAR1 - Personal Assistant Robot

PAR1 is an ESP32-S3-based personal assistant robot project. The robot is planned to support voice interaction, servo-based movement, speaker output, AI API integration, and a 3D-printed body.

## Project Goal

The goal of this project is to build a small conversational robot that can receive voice or command input, process it using an AI service, and respond through sound and simple physical movement.

## Main Features

- ESP32-S3 DevKitC-1 as the main controller
- Voice input using INMP441 I2S digital microphone modules
- Audio output using MAX98357 I2S amplifier and mini speaker
- Basic movement using SG90 mini servo motors
- Possible OLED screen for simple robot eye animations
- AI integration using an online AI API
- 3D-printed robot body

## Project Structure

```text
docs/
  project-plan.md
  components-list.md
  setup-notes.md
  development-log.md

code/
  servo-test/
  microphone-test/
  speaker-test/
  ai-integration/

circuit/
  wiring-notes.md
  diagrams/
  photos/

3d-design/
  models/
  print-notes.md

media/
  photos/
  videos/

logs/
