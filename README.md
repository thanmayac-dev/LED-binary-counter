# LED-binary-counter

An Arduino project that counts from 0 to 15 in binary using 4 LEDs.
Each LED represents one binary digit — LED on = 1, LED off = 0.
Simulated on Wokwi without physical hardware.

## How It Works
The counter increments every 1000ms, displaying the binary
representation of each number (0000 to 1111) across 4 LEDs.
Resets back to 0 after reaching 15.

## Components
- Arduino Uno 
- 4x LEDs (any colour)
- 4x 330 ohm resistors
- Breadboard

- ## Pins Used
- Pin 2  
- Pin 4 
- Pin 5 
- Pin 6 

## Concepts Used
- Arrays
- For loops
- Bitwise shift operator (>>)
- Bitwise AND operator (&)

## Simulated on Wokwi
https://wokwi.com/projects/466247752606840833
