# Reflow Oven Controller  

### KES – Kwas Engineering Solutions  

---

## Overview

This is a controller for a reflow oven.  

---

## System

The system has three parts:

- Measurement (temperature)  
- Control (microcontroller)  
- Power switching (heater)  

---

## Hardware

- Microcontroller  
- Thermocouple interface  
- Triac switching stage  
- Power supply (internal and external)  

---

## Firmware

- Runs the temperature profile  
- Handles faults  
- Communicates over custom RJ45 service port  

---

## Safety

- High and low voltage are separated  
- Layout respects clearance  
- Faults lead to shutdown  

---

## Structure

- `/KICAD reflow-oven` — KiCad files  
- `/firmware` — code  
- `/docs` — notes  

---


## License

See LICENSE file.