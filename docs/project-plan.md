# PAR1 Project Plan

PAR1 stands for "Personal Assistant Robot". It is an ESP32-S3-based personal assistant robot project. The goal of this project is to build a working robot prototype that combines voice interaction, AI-generated responses, servo motor movement, speaker output, and a 3D-printed body.

## Main Goals

- Build a working ESP32-S3-based robot prototype.
- Receive voice or sound input through INMP441 I2S digital microphone modules.
- Generate responses using an AI API.
- Provide audio output through a MAX98357 I2S amplifier and a mini speaker.
- Add basic movement using SG90 mini servo motors and a pan-tilt bracket.
- Design and build a 3D-printed robot body.
- Document the entire development process on GitHub.
- Display simple robot eye animations or status information using a 0.96 inch I2C OLED screen.

## Project Steps

### Step 1: Digital Preparation

In this stage, the development environment is prepared, the required libraries are installed, the API key setup is planned, and the GitHub repository is created.

### Step 2: Circuit and Connection

Electronic components are connected to the ESP32 for basic circuit testing. Power connections, pin connections, and wiring notes are documented.

### Step 3: Individual Tests

The servo motor, microphone, speaker/amplifier, and other components are tested separately. Each test includes code, wiring notes, test results, and evidence such as photos or videos.

### Step 4: Artificial Intelligence Integration

The ESP32 is connected to Wi-Fi. AI API integration is developed to process user input and generate responses. Text-to-speech functionality may also be added.

### Step 5: Body Design and 3D Printing

The robot body is designed based on the size of the ESP32, servo motors, microphone, speaker, and other modules. 3D model files and assembly documentation are added to the repository.

### Step 6: Final Settings and Calibration

Servo calibration, audio response calibration, optional OLED eye animations, final testing, and the demo video are completed.

## Proof of Progress

This project follows a proof-of-progress approach. Every important step will be documented on GitHub, including code, test results, wiring notes, photos, videos, circuit diagrams, 3D model files, and development logs.
