# 🚦 3-LED Indicator Module

A compact, vertical 3-LED breakout board designed in KiCad. This module is built as a reusable hardware block for traffic light indicators, logic status signaling, or basic microcontroller prototyping.

---

## 🛠️ Hardware Specifications

| Component | Value / Type | Purpose |
| :--- | :--- | :--- |
| **LEDs (D1, D2, D3)** | 5mm Through-Hole | Visual Indicators (Red, Yellow, Green) |
| **Resistors (R1, R2, R3)** | 220Ω SMD | Current Limiting for 3.3V/5V Logic |
| **Connector (J1)** | 4-Pin 0.1" (2.54mm) Header | Power & Signal Interface |

---

## 📌 Pinout Diagram
<img width="932" height="1046" alt="image" src="https://github.com/user-attachments/assets/1f51bc13-c974-47ea-a7c7-707a90b6f309" />

The module utilizes a common-cathode configuration to minimize routing complexity:

* **Pin 1:** LED 1 Control Input (Red)
* **Pin 2:** LED 2 Control Input (Yellow)
* **Pin 3:** LED 3 Control Input (Green)
* **Pin 4:** **GND** (Shared Common Ground Plane)

---

## 🖼️ Design Preview

<img width="1022" height="1320" alt="image" src="https://github.com/user-attachments/assets/3e56be0e-6952-46cf-81ba-e03f02c4f1d6" />


---
<img width="1464" height="920" alt="image" src="https://github.com/user-attachments/assets/d5f8544a-97e9-4b9c-9b91-81760e815728" />


## 📦 Manufacturing & Production
* **Gerber Folder:** All production-ready fabrication data is exported to the `/Gerbers` directory.
* **Specifications:** Optimized for standard 2-layer FR4 fabrication (0.16mm minimum trace width, standard drill tolerances).
