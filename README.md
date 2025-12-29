# Code-Mates

## Problem Statement
Women often feel unsafe while traveling alone at night, and elderly people may not be able to use mobile safety apps during emergencies. In panic situations, unlocking a phone and opening an app is not practical.

## Proposed Solution
A smart safety keychain integrated with a mobile app.  
The keychain acts as a physical SOS trigger, allowing users to send emergency alerts without interacting with their phone.

## How It Works
- The keychain uses an ESP32 with built-in Bluetooth
- A slide switch acts as the SOS trigger
- When the switch is activated:
  - SOS signal is sent to the mobile app via Bluetooth
  - The app shares live location
  - Emergency alerts are sent to trusted contacts
- One-time Bluetooth pairing is required

## Hardware Prototype
- ESP32
- Slide switch (SOS trigger)
- LED (status indicator)

https://wokwi.com/projects/451524758139437057


