# High-Performance-Isolated-Stepper-Motor-Driver
DRV8825-Based Bipolar Driver with Optical Isolation and DIP-Selectable  Microstepping

<img width="660" height="513" alt="image" src="https://github.com/user-attachments/assets/725ad809-0b69-4dbc-9665-ec68ed187696" />

---

## Overview

This project implements a high-performance bipolar stepper motor driver designed for industrial automation, motion control, CNC systems, robotics, and embedded applications.

The design is based on the DRV8825 stepper motor driver and incorporates optical isolation on the control interface to improve noise immunity and protect external controllers from ground loops and electrical transients.

The module supports standard STEP/DIR control signals, adjustable motor current, and DIP-selectable microstepping configurations.

---

## Features

- DRV8825 stepper motor driver
- Bipolar stepper motor support
- Motor supply voltage: 12 V to 24 V
- Up to 2.5 A peak current per phase
- Adjustable current limit
- Optically isolated STEP input
- Optically isolated DIR input
- 5 V to 24 V compatible control interface
- DIP switch microstepping selection
- Full-step to 1/32-step operation
- On-board 5 V regulator
- Integrated protection
- Screw terminal connections

---

## Applications

- CNC machines
- Motion control systems
- Industrial automation
- PLC-controlled systems
- Robotics
- Embedded motion platforms
- Laboratory automation
- Educational motor control platforms

---

## Technical Specifications

| Parameter | Value |
|------------|------------|
| Driver IC | DRV8825 |
| Motor Supply Voltage | 12 V – 24 V |
| Logic Voltage | 5 V |
| Peak Current per Phase | 2.5 A |
| Continuous Current per Phase | 2.0 A |
| Input Voltage (STEP/DIR) | 5 V – 24 V |
| Microstepping | Full to 1/32 |
| Isolation Voltage | 2.5 kVrms |

---

## Design Highlights

### Optical Isolation

The STEP and DIR inputs are isolated using high-speed 6N137 optocouplers.

Benefits include:

- Improved noise immunity
- Protection against ground loops
- Reduced EMI susceptibility
- Direct PLC compatibility

### Adjustable Current Control

Motor current is adjusted using an onboard precision trimmer.

Current regulation is handled by the DRV8825 internal control loop and external sense resistors.

### Microstepping Configuration

Supported microstepping modes:

| Mode |
|--------|
| Full Step |
| 1/2 Step |
| 1/4 Step |
| 1/8 Step |
| 1/16 Step |
| 1/32 Step |

Selection is performed through an onboard DIP switch.

---

## System Architecture

<img width="781" height="476" alt="image" src="https://github.com/user-attachments/assets/005f8f3f-3cd9-44e6-9f69-056149133619" />

---

## Main Components

| Component | Function |
|------------|------------|
| DRV8825 | Stepper motor controller |
| 6N137 | High-speed optocoupler |
| KIA7805 | Logic regulator |
| 0.1 Ω Sense Resistors | Current measurement |
| Trimmer Potentiometer | Current adjustment |

---

## Hardware Images

### PCB Top Side

<img width="531" height="695" alt="image" src="https://github.com/user-attachments/assets/599a69d9-2767-4240-b56d-074f4ef03ae6" />

### PCB Bottom Side

<img width="519" height="690" alt="image" src="https://github.com/user-attachments/assets/cce11522-75a1-48be-bd2f-db2fac5d1b34" />

### 3D

<img width="375" height="486" alt="image" src="https://github.com/user-attachments/assets/de01e45d-cfad-47a3-831a-275134fb1636" />
