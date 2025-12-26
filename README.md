# CMOS Inverter Design & Layout

## Project Overview
This project presents the full-custom design of a CMOS inverter, including schematic capture, physical layout, and post-layout verification. The design is optimized for a 68nm process node with matched transistor widths for specific timing requirements.

## Design Specifications
* **Process Node:** 68nm
* **Supply Voltage (VDD):** 1.2V
* **Transistor Dimensions:**
    * **PMOS Width (Wp):** 1.4 μm
    * **NMOS Width (Wn):** 1.4 μm
    * **Channel Length (L):** 68 nm
* **Output Load (Cload):** 28 fF

## Performance Summary
| Parameter | Value |
|-----------|-------|
| Rise Delay ($t_{LH}$) | 79.9 ps |
| Fall Delay ($t_{HL}$) | 44.5 ps |
| Output Rise Edge Rate | 90.6 ps |
| Output Fall Edge Rate | 40.3 ps |
| **Total Layout Area** | **7.5582 μm²** |

## Physical Layout Details
* **Dimensions:** 1.56 μm x 4.845 μm
* **Pin Pitch:** 0.52 μm
* **Verification:** Passed DRC (Design Rule Check) and LVS (Layout Vs Schematic) using Calibre.
* **Extraction:** Parasitics extracted via Calibre xRC for accurate post-layout simulation.

## Simulation Setup
The transient analysis was performed using HSPICE. Measurements include propagation delays at the 0.6V threshold and Energy-Delay Product (EDP) calculations to evaluate power efficiency.

---
**Authors:** Ganesh Manjunath & Aryan Verma  
**Course:** EECT / CE 6325 – VLSI Design  
**Instructor:** Prof. Carl Sechen
