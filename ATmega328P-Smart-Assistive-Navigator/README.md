# ATmega328P Smart Assistive Navigator PCB

<p align="center">
<img src="images/SAN PCB 3d_Isometric.png" width="850">
</p>

![KiCad](https://img.shields.io/badge/KiCad-10-blue)
![PCB](https://img.shields.io/badge/PCB-2--Layer-success)
![Microcontroller](https://img.shields.io/badge/MCU-ATmega328P-green)
![DRC](https://img.shields.io/badge/DRC-Passed-brightgreen)

</p>
Designed as a personal learning project to understand the complete PCB development workflow from schematic capture to fabrication-ready outputs using KiCad.

---

# Project Overview

This project documents the complete design of a custom two-layer printed circuit board (PCB) for an ATmega328P-based obstacle detection system.

The primary objective was to gain practical experience with the complete PCB design workflow rather than relying on development boards such as the Arduino Uno. The design process included schematic capture, footprint assignment, PCB layout, routing, electrical verification, design rule checking (DRC), and fabrication file generation using KiCad.

Although the board has not been physically manufactured or tested, the project successfully demonstrates a complete PCB design workflow suitable for fabrication.

---

# Objectives

- Learn professional PCB design using KiCad
- Design a custom PCB around the ATmega328P microcontroller
- Understand schematic capture and PCB layout
- Learn component placement strategies
- Perform manual PCB routing
- Verify the design using Design Rule Checks (DRC)
- Generate fabrication-ready Gerber and drill files

---

# System Features

- ATmega328P microcontroller
- Dual HC-SR04 ultrasonic sensor interfaces
- I²C LCD display interface
- Piezo buzzer output
- PN2222A transistor-based vibration motor driver
- External 16 MHz crystal oscillator
- AVR ISP programming header
- Reset push button
- Decoupling capacitor
- Two-layer PCB layout

---

# Hardware Components

| Component | Purpose |
|------------|------------------------------|
| ATmega328P | Main microcontroller |
| HC-SR04 ×2 | Obstacle detection |
| 16 MHz Crystal | System clock |
| 22 pF Capacitors | Crystal load capacitors |
| 100 nF Capacitor | Power supply decoupling |
| PN2222A | Motor driver transistor |
| 1N4007 | Flyback protection diode |
| Piezo Buzzer | Audio feedback |
| I²C LCD Header | Display interface |
| AVR ISP Header | Programming interface |
| Push Button | Reset switch |

---

# PCB Design

Software Used:

- KiCad 10

Board Specifications:

- 2-layer PCB
- Through-hole components
- Manual routing
- Custom board outline
- DRC verified
- Gerber files generated

Design Workflow:

1. Schematic Capture
2. Footprint Assignment
3. PCB Placement
4. Manual Routing
5. Design Rule Check (DRC)
6. Gerber Generation
7. 3D PCB Visualization

---

# Design Validation

| Check | Status |
|---------|---------|
| Electrical Rule Check (ERC) | Completed |
| Design Rule Check (DRC) | Passed |
| PCB Routing | Completed |
| Gerber Files | Generated |
| Drill Files | Generated |
| Ready for Fabrication | Yes (Design Only) |
| Physical Assembly | Not Performed |

> **Note:** This project has not been physically manufactured or electrically validated. "Ready for Fabrication" indicates that the design files were successfully generated and verified using KiCad's design checks.

---

# Repository Structure

```
ATmega328P-Smart-Obstacle-Detection-System

├── README.md
├── LICENSE
│
├── images
│   ├── schematic.png
│   ├── pcb_front.png
│   ├── pcb_back.png
│   ├── pcb_isometric.png
│
├── hardware
│   ├── SAN PCB.kicad_pcb
│   ├── SAN PCB.kicad_sch
│   ├── SAN PCB.kicad_pro
│
├── firmware
│   └── obstacle_detection.ino
│
├── fabrication
│   └── ATmega328P_Obstacle_Detection_Gerbers.zip
│
├── bom
│   └── BOM.csv
│
└── docs
    ├── Schematic.pdf
    ├── PCB.pdf
```

---

# Gallery

## Schematic

<img width="588" height="804" alt="SANPCBSCHVIEW" src="https://github.com/user-attachments/assets/ea26a3a9-5395-465a-b804-276a71dc419c" />

---

## PCB Layout

<img width="740" height="824" alt="SANPCBVIEW" src="https://github.com/user-attachments/assets/a3d78648-1fde-4c67-b4df-9e771d0d86cd" />

---

## 3D View

<img width="1068" height="600" alt="SAN PCB 3d_Front" src="https://github.com/user-attachments/assets/c7f28d1a-4cb9-44df-b680-5b9e4f810696" />  <img width="1068" height="600" alt="SAN PCB 3d_Back" src="https://github.com/user-attachments/assets/25ba2ae3-7e90-4e43-8974-32839621373a" />  <img width="1068" height="600" alt="SAN PCB 3d_Isometric" src="https://github.com/user-attachments/assets/657fe181-6576-4f5e-8f6d-66e9ae553ad0" />


---

# Challenges Faced

During the development of this project I encountered several practical PCB design challenges including:

- Selecting appropriate footprints
- Crystal oscillator placement
- Decoupling capacitor positioning
- PCB routing optimization
- Managing trace intersections
- Using both copper layers effectively
- Resolving Design Rule Check (DRC) violations
- Preparing fabrication outputs

Working through these issues provided valuable hands-on experience with the PCB design process.

---

# Lessons Learned

Through this project I developed practical experience with:

- PCB schematic design
- Component footprint selection
- Two-layer PCB layout
- Manual routing techniques
- PCB design constraints
- Design verification
- Manufacturing file generation
- Professional engineering documentation

---

# Future Improvements

Future versions of this project could include:

- Physical PCB fabrication
- Hardware assembly and testing
- USB programming interface
- Improved component placement
- Reduced PCB dimensions
- Surface-mount (SMD) version
- Power supply optimization

---

# Author

**[Syed Ihteshamuddin]**

High School Student

Interested in:

- Electrical Engineering
- Embedded Systems
- PCB Design
- Hardware Development

GitHub: https://github.com/syedihteshamuddin

---

> This repository documents a personal learning project completed to develop practical skills in embedded hardware and PCB design.
