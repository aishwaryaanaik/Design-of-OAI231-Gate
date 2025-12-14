
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


---

## 3. Clocked CMOS (C2MOS) Logic

Clocked CMOS, also known as C2MOS logic, is a dynamic logic style that uses clock signals
to control circuit operation.

The circuit operates in two phases:
- Precharge phase
- Evaluation phase

### Operation
- During the precharge phase, the output node is charged to a known value.
- During the evaluation phase, the output is conditionally discharged based on the
  input logic.

### Advantages of Clocked CMOS Logic
- Very low power consumption  
- No static current flow  
- Suitable for low-power applications  

### Disadvantages of Clocked CMOS Logic
- Requires clock signal  
- Higher transistor count  
- Slower switching speed  

---

## 4. Pseudo-NMOS Logic

Pseudo-NMOS is a ratioed logic style in which a single PMOS transistor is always ON, while
the NMOS network performs the logic function.

Unlike CMOS logic, Pseudo-NMOS does not use a complementary pull-up network.

### Operation
- The PMOS transistor continuously pulls the output high
- The NMOS network pulls the output low when the logic condition is satisfied

### Advantages of Pseudo-NMOS Logic
- Reduced transistor count  
- Smaller area  
- Faster switching speed  

### Disadvantages of Pseudo-NMOS Logic
- High static power dissipation  
- Lower noise margin  
- Output depends on transistor sizing  

---

## 5. Comparison Summary

Clocked CMOS logic provides excellent power efficiency but requires more area and has
slower operation. Pseudo-NMOS logic offers faster switching speed and compact design at
the cost of increased power consumption.

The choice of logic style depends on application requirements such as power, speed, and
area constraints.

