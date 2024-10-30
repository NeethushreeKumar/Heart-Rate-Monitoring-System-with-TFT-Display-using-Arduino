# Heart-Rate-Monitoring-System-with-TFT-Display-using-Arduino
This Arduino project is a heart rate monitoring system with real-time data display on a TFT screen. It uses a pulse sensor to measure heart rate and shows results in a user-friendly interface. With scripts for testing and final implementation, it serves as a practical tool for basic health monitoring.

## Project Overview
This project is a heart rate monitoring system built on the Arduino platform, featuring a TFT display for visual output. The system leverages a pulse sensor to capture heart rate data and displays it in real-time on a TFT screen, making it a simple yet effective tool for monitoring heart rate. With easy-to-follow code files, this project serves as a practical example of combining sensor data acquisition with visual feedback on embedded systems.

## Table of Contents
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Software Requirements](#software-requirements)
- [Project Structure](#project-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Features
- **Real-Time Heart Rate Monitoring**: Uses a pulse sensor to capture and display heart rate data in real time.
- **TFT Display Output**: Provides visual feedback with easy-to-read heart rate values on a TFT screen.
- **Modular Codebase**: Includes separate files for testing the heart rate sensor and TFT display individually before combining them into the final implementation.

## Hardware Components
- **Arduino Board**: Compatible with various Arduino models.
- **Pulse Sensor**: For measuring heart rate.
- **TFT Display**: For displaying heart rate data.

## Software Requirements
- **Arduino IDE**: To upload and manage code files on the Arduino board.
- **TFT and Pulse Sensor Libraries**: Necessary libraries for handling the TFT display and pulse sensor.

## Project Structure
```plaintext
├── med.ino                    # Main code file for the heart rate monitoring system
├── tft_display_test.ino       # Script to test TFT display functionality
├── heart_rate_test.ino        # Script to test heart rate sensor functionality
└── final_test_one.ino         # Final integrated test combining sensor and display
