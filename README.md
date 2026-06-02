# Interactive LED Hourglass

An embedded systems project that simulates a traditional sand hourglass using a custom-built 64-LED display, Arduino Nano, shift registers, and a tilt sensor.

## Features

- 64-LED custom display
- Real-time sand flow simulation
- Tilt-based direction reversal
- Buzzer feedback
- Battery-powered operation
- LED multiplexing for efficient GPIO usage

## Hardware Components

- Arduino Nano
- 64 LEDs
- 74HC595 Shift Registers
- BC548 Transistors
- SW-520D Tilt Sensor
- Buzzer
- 18650 Li-ion Battery
- TP4056 Charging Module
- MT3608 Boost Converter

## Working Principle

The system simulates sand particles falling through an hourglass. When the device is tilted, the tilt sensor detects the orientation change and reverses the gravity direction, causing the digital sand particles to flow in the opposite direction.

LED multiplexing and shift registers are used to control all LEDs while minimizing GPIO pin usage.

## Software

- Arduino IDE
- Embedded C/C++

Main functionalities:

- LED matrix control
- Particle simulation
- Sensor monitoring
- Debouncing
- Buzzer control
- Power-efficient scheduling using millis()

## Circuit Diagram

The complete circuit schematic is available in the Schematics folder.

## Demonstration

Images and videos of the working prototype are available in the Images folder.

## Future Improvements

- PCB implementation
- RGB LED support
- Adjustable timer modes
- Wireless control via Bluetooth

## Author

Aaryan
