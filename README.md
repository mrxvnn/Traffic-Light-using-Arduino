# Traffic-Light-using-Arduino
This project is a Smart Automatic Toll Gate System built using Arduino, RFID technology, and basic sensors to simulate a real-world automated toll collection system. The system detects vehicles, verifies RFID cards, processes payments, and controls a servo-based gate all without human intervention.

**Features**
🚗 Vehicle Detection using IR sensors
💳 RFID Authentication for secure access
💰 Automated Toll Deduction Logic
🚧 Servo-Controlled Gate Mechanism
🔴🟢 LED Indicators for status feedback
🔁 Fully Automated Loop System (no manual reset needed)

**Working Principle**
The system operates in a sequence:
Vehicle Detection - An IR sensor detects the presence of a vehicle at the entry point.
RFID Verification - The driver taps an RFID card on the reader. The system reads the card’s UID.
Validation Logic - Valid card with balance → Access granted, Invalid / insufficient balance → Access denied
Gate Operation - On success → Gate opens using servo motor, On exit detection → Gate closes automatically

**Components Used**
Arduino Uno
RFID Module (RC522)
Servo Motor (SG90)
IR Sensors (Entry & Exit)
LEDs (Red & Green)
Jumper Wires & Breadboard

