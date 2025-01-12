# CMOS Charge Pump Circuit Design

This repository contains the design and simulation of a five-stage CMOS charge pump circuit, aimed at efficient voltage boosting for embedded systems and power management applications. 

## Overview

The CMOS charge pump circuit is designed to step up a low input voltage to a significantly higher output voltage using capacitors, MOSFET switches, and dual-phase clock signals. It is scalable, compact, and consumes minimal power, making it suitable for a variety of low-power applications.

### Key Features
- **Voltage Boosting:** Achieves efficient stepping up of input voltage using a multi-stage design.
- **Low Power Consumption:** Optimized for power efficiency in embedded systems.
- **Scalable Design:** Easily adaptable for applications requiring higher voltage levels.
- **Compact Layout:** Designed for minimal space consumption on silicon.

## Tools Used
- **Microwind:** For layout design and testing.
- **NGSpice:** For circuit simulation and validation.

## Circuit Design and Simulation
The charge pump circuit utilizes:
- **Five Stages** for efficient voltage boosting.
- **Capacitors and MOSFET Switches** for charge storage and transfer.
- **Dual-Phase Clock Signals** to enable effective charge pumping.

### State Diagram
The design includes:
- Operation states for voltage boosting, charge storage, and transfer.
- Simulated transitions to validate efficiency and functionality.

## Applications
- Embedded systems power supply.
- Battery-powered devices.
- Low-power IoT systems.

## Repository Contents
- `schematic/`: Circuit schematics in SPICE format.
- `layout/`: CMOS layouts designed in Microwind.
- `simulation_results/`: Simulation outputs from NGSpice.
- `documentation/`: Design notes, reports, and specifications.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CMOS-Charge-Pump.git
