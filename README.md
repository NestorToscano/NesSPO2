# SpO₂ Interface Module PCB (KiCad 9)

This repository contains the hardware design for a simple **SpO₂ interface module PCB**, designed in **KiCad 9**. The board serves as a carrier and interconnect for an Arduino-compatible microcontroller, an **SSD1306 OLED display**, a **MAX30102 SpO₂/heart-rate sensor module**, and basic user input components.

The design focuses on clean signal routing, modular integration, and fabrication-ready layout rather than signal processing or firmware implementation.

## Project Overview

The purpose of this board is to provide a compact and organized way to connect common off-the-shelf modules used in SpO₂ prototyping. The PCB primarily functions as an interconnection and mounting platform, integrating passive components and connectors into a single, manufacturable design.

## Features

- Arduino-compatible header connections  
- Interface for **MAX30102 SpO₂ sensor module**  
- Interface for **SSD1306 I²C OLED display**  
- Compact, fabrication-ready PCB layout  

## Repository Contents

- KiCad 9 project files (schematic and PCB)
- PCB layout and routing
- Fabrication-ready Gerber and drill files

All sensing, processing, and display control are intended to be handled by the external microcontroller.

## Tools Used

- **KiCad 9** – schematic capture and PCB layout

## Manufacturing

The included Gerber and drill files are ready for submission to standard PCB fabrication services. The design follows typical clearance and trace-width rules compatible with low-cost fabs.
The design was intended to be used for JLCPCB.

## Intended Use

- SpO₂ and heart-rate prototyping
- Arduino-based biomedical projects
