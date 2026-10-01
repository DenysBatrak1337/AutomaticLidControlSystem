# Automatic Trash Can 🗑️

Smart trash can that automatically opens its lid when you approach it. Built with Arduino, it uses an IR sensor to detect your hand and a servo motor to control the lid.

## What it does
- Opens automatically when you put your hand near
- Shows "Open" on the display
- Counts how many times it's been opened
- Closes automatically after 2 seconds
- Shows "Closed" on the display

## Parts needed
- Arduino Uno
- IR Sensor
- Servo Motor
- LCD Display
- Battery Pack

## How to connect

IR Sensor:
- VCC → Pin 8
- GND → GND
- OUT → Pin 4

Servo Motor:
- VCC → 5V
- GND → GND
- Signal → Pin 7

LCD Display:
- VCC → 5V
- GND → GND
- SDA → A4
- SCL → A5


## Libraries needed
- LowPower.h
- Servo.h
- rgb_lcd.h