# Car Speed Monitoring System

## Introduction
This Digital Electronics Design project demonstrates a Car Speed Monitoring System implemented in Logisim. Vehicle speed is represented using clock pulses that are counted digitally and continuously compared against predefined limits.

## Objective
Design and simulate a digital circuit capable of monitoring speed, displaying it on seven-segment displays, and preventing further counting when the configured threshold is exceeded.

## Construction
The system is built using a clock source, synchronous counters, magnitude comparators, OR logic, and seven-segment displays. The counter outputs are connected simultaneously to the display and comparison logic.

## Working
Clock pulses emulate vehicle speed. As pulses arrive, counters increment and the displayed value changes. Comparators evaluate the count against preset limits. If any limit is exceeded, their outputs are combined through an OR gate that disables the clock path, freezing the displayed value and indicating an over-speed condition.

## Applications
Traffic monitoring, educational demonstrations, digital logic laboratories, embedded control concepts, and safety monitoring systems.

## Advantages
Modular design, simple implementation, clear visualization, extensibility, and practical demonstration of counters and comparators.

## Repository Structure
- report/: project report
- circuit/: Logisim circuit
- Demo/: simulation video
- assets/: supporting image

## Author
Kartik S Shivshetty