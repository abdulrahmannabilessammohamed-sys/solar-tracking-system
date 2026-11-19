# Analog Solar Tracking System

A microcontroller-free, programming-free solar tracking system designed to automatically orient a solar panel toward the strongest light source using dual LDR sensors and a **TDA2822M** IC.

## Overview
Two photoresistors (LDRs) positioned on either side of a central shading plate form a voltage-divider bridge.
Light intensity differences create a resistance and voltage imbalance that is compared and amplified by the dual-channel **TDA2822M** IC to drive an **N20** micro gear motor clockwise or counter-clockwise.

## System Components
* **Solar Panel:** Monocrystalline Silicon ($55\text{mm} \times 55\text{mm}$)
* **Control IC:** TDA2822M (Dual Amplifier / Comparator & Driver stage)
* **Actuator:** N20 Micro Gear Motor (12V DC / Gearbox)
* **Sensors:** 2x 5mm LDR Photoresistors with central shading plate
* **Resistors:** 2x $10\text{k}\Omega$ fixed resistors
* **Power Source:** 2x 18650 Lithium-ion batteries in series (7.4V)
* **Control:** SPST ON/OFF slide switch

## Key Features & Advantages
* **Zero Programming:** Pure analog hardware logic with no microcontroller required.
* **Cost-Effective & Reliable:** Uses affordable components with durable, field-serviceable hardware.
* **Balanced Power Design:** A 7.4V supply balances motor torque requirements and IC thermal limits.

## Documentation
* Full project report available in [`Solar_Tracking_System_Report_v2.pdf`](./Solar_Tracking_System_Report_v2.pdf).
