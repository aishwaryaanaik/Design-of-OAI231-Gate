# Pseudo-NMOS Logic

Pseudo-NMOS is a ratioed logic style in which a single PMOS transistor is always ON, while
the NMOS network performs the logic function.

Unlike CMOS logic, Pseudo-NMOS does not use a complementary pull-up network.

## Operation
- The PMOS transistor continuously pulls the output high
- The NMOS network pulls the output low when the logic condition is satisfied

## Advantages of Pseudo-NMOS Logic
- Reduced transistor count  
- Smaller area  
- Faster switching speed  

## Disadvantages of Pseudo-NMOS Logic
- High static power dissipation  
- Lower noise margin  
- Output depends on transistor sizing

## Schematic
The schematic shows the transistor-level implementation of the OAI321 gate using
Pseudo-NMOS logic. A single PMOS transistor is permanently ON, while the NMOS network
implements the logic function, resulting in reduced transistor count and faster
operation.

<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/775bd52a-2e62-47fc-82e3-367d915ced25" />

## Symbol: 
The symbol represents the OAI321 gate implemented using Pseudo-NMOS logic. It provides
a simplified block-level view of the circuit while hiding the internal ratioed
transistor structure.


<img width="725" height="375" alt="image" src="https://github.com/user-attachments/assets/dfa1672a-6c7d-4fea-be17-33006aa7674c" />

## Waveform:
The waveform illustrates the output behavior of the Pseudo-NMOS OAI321 gate for various
input combinations. It demonstrates faster switching speed compared to Clocked CMOS,
along with higher static power consumption.


<img width="725" height="300" alt="image" src="https://github.com/user-attachments/assets/c7cb045b-487b-469e-85a1-18da7c6dc7c7" />






