# Design and Implementation of OAI231 Gate using Clocked CMOS and Pseudo-NMOS Logic

## Project Overview
This project presents the **design, implementation, and performance comparison** of an  
**OAI231 (OR-AND-Invert)** logic gate using:

- **Clocked CMOS (C2MOS) Logic**
- **Pseudo-NMOS Logic**

The designs are implemented at the **transistor level** and evaluated based on
**power consumption, delay, and area**.

---

## Logic Function
The logic expression of the OAI231 gate is:

Y = ((A + B) · (C + D + E) · F)'

This gate performs OR operations at the input level, followed by AND operation, and finally an inversion.

---

## Tools & Technology
- CMOS VLSI Design
- Transistor-level implementation
- Simulation-based waveform analysis
- Standard CMOS technology
- Tool:Cadence 

---

## Design Methodology
1. Designed OAI231 gate using **Clocked CMOS (C2MOS)** logic
2. Designed the same logic using **Pseudo-NMOS** logic
3. Generated schematics and symbols
4. Simulated output waveforms
5. Compared designs based on:
   - Power consumption
   - Rise and fall time
   - Transistor count (area)

---

## Results & Comparison

| Parameter | Clocked CMOS (C2MOS) | Pseudo-NMOS |
|---------|----------------------|-------------|
| Power Consumption | 4.120 µW | 44.9 µW |
| PMOS Count | 7 | 1 |
| NMOS Count | 7 | 6 |
| Total Transistors | 14 | 7 |
| Rise Time | 13.75 ns | 3.63 ns |
| Fall Time | 2.461 ns | 975.1 ps |

---

## Observations
- Clocked CMOS logic consumes **significantly lower power**
- Pseudo-NMOS logic offers **faster switching speed**
- Pseudo-NMOS reduces **area by nearly 50%**
- Clocked CMOS is more suitable for **low-power applications**

---

## Conclusion
Clocked CMOS (C2MOS) logic is highly **power-efficient** but requires more area and has slower switching speed, making it ideal for **low-power designs**.  
Pseudo-NMOS logic provides **high-speed operation with reduced area** but suffers from **high static power dissipation**.

The choice between the two depends on application requirements such as **power, speed, and area constraints**.

---

