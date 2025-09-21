# Blinky - External LED

## Description
My first external circuit! Successfully controlled an LED on a breadboard using an Arduino Uno. Learned the critical lesson of using a current-limiting resistor in series.

## Hardware
- **Microcontroller:** Arduino Uno
- **Components:** 1x LED (Red), 1x 220Ω Resistor, Breadboard, Jumper Wires
- **Connections:**
  - Arduino Pin 8 → 220Ω Resistor
  - 220Ω Resistor → LED Anode (Long leg)
  - LED Cathode (Short leg) → Arduino GND

## Software
- **IDE:** Arduino IDE 2.x
- **Code:** Modified the built-in 'Blink' example to use `pinMode(8, OUTPUT)`.

## Lessons Learned
- The absolute necessity of a current-limiting resistor for an LED.
- The difference between the Arduino's built-in LED and controlling an external pin.
- How to create a simple series circuit on a breadboard.

## Media
*(We'll add a link to a picture or video later!)*
