# Hand Tracking Slider Control with Arduino

## Overview

This project demonstrates how to use hand tracking to control a slider and a servo motor with an Arduino. The hand tracking is performed using OpenCV and MediaPipe, and the servo motor is controlled via Arduino using the PyFirmata library.

## Features

- Real-time hand tracking using MediaPipe
- Slider control based on hand gestures
- Servo motor control with Arduino

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher
- OpenCV
- MediaPipe
- NumPy
- Math
- PyFirmata
- Arduino with a connected servo motor

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- Servo motor
- Jumper wires
- Breadboard (optional)
- USB cable to connect Arduino to your computer

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/omkarpawar201/Hand-tracking-control.git
    cd hand-tracking-servo-control
    ```

2. Install the required Python packages:
    ```sh
    pip install opencv-python mediapipe numpy pyfirmata
    ```

3. Set up the Arduino:
    - Connect the servo motors to the Arduino (signal to pin 6 and pin 10, and pin  power to 5V, ground to GND).
    - Upload the StandardFirmata sketch to the Arduino using the Arduino IDE (File > Examples > Firmata > StandardFirmata).

## Usage

To start the hand tracking and servo control system, run the following command:

```sh
python hand_tracking_servo_control.py
