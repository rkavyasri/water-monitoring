# Water Flow Monitoring Project for domestic purpose

This project monitors water flow using Arduino and displays data on an I2C LCD. It includes features for detecting leaks and sending notifications via SMS.

## Setup

### Hardware Requirements:
- Arduino Uno
- I2C LCD
- Flow sensors (two sensors connected)

### Libraries Used:
- Wire.h
- LiquidCrystal_I2C.h
- SoftwareSerial.h (for GSM communication)

## Usage

1. Upload the `WaterFlowMeter.ino` sketch to your Arduino board.
2. Connect the hardware as per the instructions in the code comments.
3. Ensure GSM module configuration (phone number and settings) is updated for SMS functionality.
4. Monitor water flow and leaks using the LCD display and SMS notifications.


