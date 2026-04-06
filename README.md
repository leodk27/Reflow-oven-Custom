# Reflow Oven Controller  
## KES – Kwas Engineering Solutions  

---

## Overview

This is a controller for a reflow oven.  
It reads temperature, drives a heater, and follows a profile.  

It is built to work, not to impress.

---

## Purpose

- Run repeatable reflow profiles  
- Control heat with feedback  
- Provide a simple service interface  
- Keep low voltage and mains separate  

---

## System

The system has three parts:

- Measurement (temperature)  
- Control (microcontroller)  
- Power switching (heater)  

Temperature is measured.  
The controller decides.  
The heater follows.

---

## Hardware

- Microcontroller  
- Thermocouple interface  
- Triac switching stage  
- Power supply (internal and external)  

Protection is included where needed.  
Nothing is added without reason.

---

## Firmware

The firmware:

- Runs the temperature profile  
- Handles faults  
- Communicates over custom RJ45 service port  

---

## Safety

This system switches mains voltage.

- High and low voltage are separated  
- Layout respects clearance  
- Faults lead to shutdown  

---

## Structure

- `/KICAD reflow-oven` — KiCad files  
- `/firmware` — code  
- `/docs` — notes  

---

## Use

---

## License

See LICENSE file.