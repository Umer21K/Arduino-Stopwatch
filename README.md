# Arduino-Stopwatch
This is my project for Digital Logic Design

## Overview
This project involves creating a simple stopwatch using an Arduino, a button, a small LCD, LEDs, and a breadboard. The stopwatch allows you to start and stop time with visual indicators: a green LED for starting the time and a red LED for stopping the time.

## Features
- Start and Stop Functionality: Use a button to start and stop the stopwatch.
- LCD Display: Shows the elapsed time.
- LED Indicators:
1. Green LED indicates that the stopwatch is running.
2. Red LED indicates that the stopwatch is stopped.
-User-Friendly Interface: Simple and intuitive control with visual feedback.

## Components
- Arduino Board ( Arduino Uno)
- Small LCD ( 16x2 character LCD)
- Push Button
- Green LED
- Red LED
- Breadboard
- Jumper Wires
- Resistors (for LEDs and button)

## Circuit Diagram

- Connect the LCD to the Arduino according to its specifications .
- Connect the button to a digital input pin, with a pull-down resistor.
- Connect the green LED to another digital output pin with an appropriate resistor.
- Connect the red LED to another digital output pin with an appropriate resistor.

## Operating the Stopwatch:
- Press the button to start the stopwatch. The green LED will light up, and the LCD will display the elapsed time.
- Press the button again to stop the stopwatch. The green LED will turn off, the red LED will light up, and the LCD will hold the elapsed time.
