# 🚗 Car Speed Monitoring System

> A digital speed monitoring system designed and simulated in **Logisim** using counters, comparators, logic gates and digital displays.

<p align="center">
  <img src="assets/circuit-diagram.png" width="850" alt="Car Speed Monitoring System circuit">
</p>

---

## 💡 What is this?

This project simulates a simple **car speed monitoring system** where clock pulses represent the vehicle-speed input.

The system:

- Counts incoming pulses
- Displays the measured value
- Compares the counter output against predefined thresholds
- Detects over-speed conditions
- Stops further counting when a violation is detected

Built as part of the **Digital Electronics Design (25ECSF101)** course activity, 2025–26.

---

## ⚙️ How It Works

<p align="center">
  <img src="assets/system-architecture.png" width="900" alt="System architecture">
</p>

### The basic idea

**Clock → Count → Compare → Detect → Stop**

Clock pulses are used as the simulated speed input. The counter tracks these pulses while the display shows the current value.

The counter output is continuously checked against predefined thresholds. When a limit violation is detected, the control logic disables further clock pulses, stopping the count and activating the alert indication.
