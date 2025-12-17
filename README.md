# Adaptive Street Light System 🌃💡

An Arduino-based adaptive street lighting system that automatically adjusts LED brightness based on ambient light intensity using an LDR.

## Features
- Automatic brightness control
- Energy-efficient lighting
- PWM-based LED dimming
- Real-time light sensing
- Serial monitor output for debugging

## Components Used
- Arduino UNO
- LDR (Light Dependent Resistor)
- LED
- 220Ω resistor
- Breadboard & jumper wires

## Working Principle
The LDR senses ambient light intensity.  
In low-light conditions (night), LED brightness increases.  
In high-light conditions (day), LED brightness decreases.  
PWM (Pulse Width Modulation) is used to smoothly control LED intensity.

## Simulation Note
The LED represents a street light.  
This system can be extended using multiple LEDs and motion sensors for smart city applications.
