# Octavia Carbon Challenge
# README: CM4 Carrier Board & Electrical Panel Design

## Overview

This project involves the design of a **Custom Carrier Board** for the **Raspberry Pi Compute Module 4 (CM4)** and an **Electrical Panel** layout for a 3-phase 415V 32A industrial supply.

### Key Features:

1. **CM4 Carrier Board**:

   * **Interfaces**: Ethernet, RS485 (2 independent channels), SPI, I2C, UART.
   * **Power Supply**: 12V-24V DC input with reverse polarity protection, ESD, and over-voltage protection.
   * **RS485 Protection**: High voltage protection (up to 24V) and termination resistor options with jumpers.
   * **Mezzanine Connector**: Used for CM4 interface with all required signals (Power, Ground, SPI, UART, etc.).
   * **Status LEDs**: Power and activity indicators.
   * **PCB Layout**: Impedance control for high-speed signals (RS485, SPI), grounding, and thermal management.

2. **Electrical Panel Design**:

   * **3-Phase 415V Supply** for a vacuum pump (BSC SRV300B) and a 24kW boiler (DM24-0.8).
   * **Protection Devices**: Proper fuses, breakers, and control components following industry standards for safety and reliability.

### Design Considerations:

* High-voltage protection, signal integrity for industrial communication, and ease of maintenance for the electrical panel.
* Test points and jumper pads for configuration and troubleshooting.

This design ensures a robust interface between industrial systems and the Raspberry Pi Compute Module 4 for automation tasks.
