# Adaptive Perimeter Intrusion Detection System (PS5)

## Project Overview

This project implements an **Invisible Perimeter Tripwire** for defense and security applications.

Traditional laser tripwires are visible and can be detected using smoke or IR cameras. This system proposes a hidden intrusion detection mechanism using sensor-based detection and alarm activation.

The system detects intrusions near a secured perimeter and triggers an alarm when an object enters the detection range.

---

## Problem Statement

Build a perimeter defense system that can detect an intruder entering a protected region while remaining difficult to detect externally.

---

## Objective

* Detect intrusion near the perimeter
* Trigger an alert system
* Create a low-cost defense prototype
* Demonstrate concept using Tinkercad simulation

---

## Hardware Used

* Arduino Uno
* Ultrasonic Sensor (HC-SR04)
* Piezo Buzzer
* Breadboard
* Jumper Wires
* USB Power Supply

---

## Software Used

* Tinkercad
* Arduino IDE
* GitHub
* Markdown Documentation

---

## Working Principle

1. Ultrasonic sensor continuously measures distance.
2. If no object is near, system remains idle.
3. When an intruder enters the threshold range:

   * Sensor detects reduced distance
   * Arduino processes input
   * Alarm buzzer activates
4. Alert indicates perimeter breach.

---

## Circuit Connections

### HC-SR04

* VCC → 5V
* GND → GND
* TRIG → D3
* ECHO → D4

### Buzzer

* Positive → D2
* Negative → GND

---

## Algorithm

1. Start system
2. Send ultrasonic pulse
3. Measure echo time
4. Calculate distance
5. Compare with threshold
6. If intruder detected → Trigger buzzer
7. Else → Continue monitoring

---

## Results

### Normal State

No object in detection zone → Alarm OFF

### Intrusion State

Object enters detection zone → Alarm ON

Simulation successfully detected intrusions and triggered alert.

---

## Graceful Solution Strategy

Instead of using visible laser beams, this project uses hidden sensor-based perimeter detection.

Advantages:

* Low-cost
* Hidden setup
* Fast response
* Easy deployment
* Suitable for defense surveillance

Future improvements:

* GSM alert system
* Camera integration
* Wireless sensor network
* AI-based classification

---

## Applications

* Military perimeter security
* Border surveillance
* Restricted zones
* Smart home security
* Warehouse intrusion detection

---

## Author

Subhasree Dalai
25BEC10091

