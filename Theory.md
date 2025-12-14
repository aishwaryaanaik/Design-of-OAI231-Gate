
## 1. CMOS Logic

CMOS (Complementary Metal-Oxide-Semiconductor) is a widely used digital logic design
technology in VLSI systems. It uses both PMOS and NMOS transistors in a complementary
manner to implement logic functions.

<img width="200" height="214" alt="image" src="https://github.com/user-attachments/assets/c43bcf17-4c65-491c-a98b-c518a33bc42b" />

In CMOS logic:
- PMOS transistors form the Pull-Up Network (PUN)
- NMOS transistors form the Pull-Down Network (PDN)
- Only one network conducts at a time

This complementary operation results in very low static power dissipation. Power is
mainly consumed during switching activity.

### Advantages of CMOS Logic
- Low power consumption  
- High noise margin  
- Good reliability  
- Suitable for low-power VLSI designs  

### Disadvantages of CMOS Logic
- Higher transistor count  
- Larger area  
- Slightly slower compared to ratioed logic styles  

---

## 2. OAI321 Logic Gate

OAI stands for OR–AND–Invert logic. The OAI321 gate performs OR operations on input groups,
followed by an AND operation, and finally inverts the output.

### Logic Expression
Y = ((A+B).(C+D+E).F)’

### Functional Description
1. Inputs A, B, and C are ORed together  
2. Inputs D and E are ORed together  
3. The OR outputs are ANDed  
4. The final output is inverted  

OAI gates are commonly used in arithmetic circuits, control logic, and combinational
blocks to reduce logic depth and improve performance.
