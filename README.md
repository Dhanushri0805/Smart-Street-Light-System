# Smart Street Light System Using LDR

## Problem Statement

Street lights are often left ON during daylight hours, resulting in unnecessary power consumption and increased electricity costs. An automatic lighting system is required to control street lights based on ambient light conditions.

---

## Objective

- To automatically switch ON street lights during darkness.
- To automatically switch OFF street lights during daytime.
- To reduce power consumption.
- To improve energy efficiency.

---

## Components Required

1. Arduino Uno
2. LDR (Light Dependent Resistor)
3. LED
4. 220Ω Resistor
5. Breadboard
6. Connecting Wires
7. USB Cable

---

## Algorithm

1. Start the system.
2. Read the LDR sensor value.
3. Compare the value with the threshold.
4. If the value is below the threshold, turn ON the LED.
5. Otherwise, turn OFF the LED.
6. Repeat continuously.

---

## Flowchart

Start
|
Read LDR Value
|
Compare with Threshold
|
|-- Darkness --> LED ON
|
|-- Daylight --> LED OFF
|
Repeat

---

## Circuit Diagram

Upload the file named:

Circuit_Diagram.png

After uploading, add:

![Circuit Diagram](Circuit_Diagram.png)

---

## Source Code

See file:

street_light.ino

---

## Test Cases

| Test Case | LDR Value | Expected Output |
|------------|------------|----------------|
| 1 | 200 | LED ON |
| 2 | 350 | LED ON |
| 3 | 600 | LED OFF |
| 4 | 800 | LED OFF |

---

## Result

The system successfully turns ON the street light during darkness and turns it OFF during daylight conditions.

---

## Conclusion

The Smart Street Light System using LDR provides an energy-efficient and cost-effective solution for automatic street lighting. It reduces power wastage and can be implemented in smart city applications.

---

## Project Report

Project report is available in:

Report.pdf
Smart-Street-Light-System
│
├── README.md
├── street_light.ino
├── Circuit_Diagram.png
└── Report.pdf
