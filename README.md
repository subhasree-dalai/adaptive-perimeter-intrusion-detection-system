# Adaptive Perimeter Intrusion Detection System (PS5)

## Project Overview
This project implements an Invisible Perimeter Tripwire for defense and surveillance applications.

Traditional tripwire systems like laser beams are visible and can be bypassed. This project demonstrates a hidden intrusion detection system using an ultrasonic sensor and Arduino.

When an object enters the defined perimeter range, the system triggers a buzzer alarm to indicate intrusion.

---

## Problem Statement
Build a perimeter defense system capable of detecting an intruder entering a protected region while remaining difficult to detect externally.

---

## Objective
- Detect intrusion near perimeter
- Trigger an alarm
- Build low-cost prototype
- Demonstrate concept using Tinkercad simulation

---

## Hardware Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Piezo Buzzer
- Breadboard
- Jumper Wires

---

## Software Used
- Tinkercad
- Arduino IDE
- GitHub

---

## Circuit Connections

### Ultrasonic Sensor (HC-SR04)
- VCC → 5V
- GND → GND
- TRIG → Digital Pin 3
- ECHO → Digital Pin 4

### Buzzer
- Positive Terminal → Digital Pin 2
- Negative Terminal → GND

---

## Working Principle
1. Ultrasonic sensor continuously emits sound pulses.
2. Echo signal is received back after hitting an object.
3. Arduino calculates distance using time-of-flight.
4. If object enters threshold distance (25 cm), alarm activates.
5. If no object is nearby, system stays idle.

---

## Algorithm
1. Start system  
2. Send ultrasonic pulse  
3. Receive echo  
4. Calculate distance  
5. Compare with threshold  
6. If distance ≤ 25 cm → Alarm ON  
7. Else → Alarm OFF  

---

## Results
### Normal State
- Object far from sensor
- Alarm OFF

### Intrusion State
- Object enters protected zone
- Alarm ON

Simulation successfully detected intrusion and activated buzzer.

---

## Graceful Solution Strategy
Instead of using visible laser tripwires, this project uses hidden ultrasonic sensing.

Advantages:
- Low cost
- Fast response
- Hidden detection
- Easy deployment
- Defense-friendly architecture

---

## Future Improvements
- GSM alerts
- Camera integration
- AI-based classification
- Wireless sensor network

---

## Applications
- Border security
- Military defense
- Smart surveillance
- Restricted area monitoring
- Smart home security

---

## Author
Subhasree Dalai  
25BEC10091
