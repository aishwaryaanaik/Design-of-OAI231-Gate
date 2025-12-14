# Clocked CMOS
Clocked CMOS, also known as C2MOS logic, is a dynamic logic style that uses clock signals
to control circuit operation.

The circuit operates in two phases:
- Precharge phase
- Evaluation phase

## Operation
- During the precharge phase, the output node is charged to a known value.
- During the evaluation phase, the output is conditionally discharged based on the
  input logic.

## Advantages of Clocked CMOS Logic
- Very low power consumption  
- No static current flow  
- Suitable for low-power applications  

## Disadvantages of Clocked CMOS Logic
- Requires clock signal  
- Higher transistor count  
- Slower switching speed  

## Schematic  
The schematic shows the transistor-level implementation of the OAI321 gate using
Clocked CMOS (C2MOS) logic. PMOS and NMOS transistors are controlled by clock signals
to enable precharge and evaluation phases, ensuring low static power dissipation.

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/0bc1005b-43c6-479c-8056-82d1b643ca81" />

<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/5a0e7709-7059-46fc-a7b6-cf17120b8ac8" />

## SYMBOL 
The symbol represents the functional block of the OAI321 gate implemented using
Clocked CMOS logic. It simplifies circuit understanding by abstracting the internal
transistor-level design into a single logic block with defined inputs and output.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/e32fed7f-6050-43ad-b3d0-e43a2873e159" />

## Waveform
The waveform illustrates the output response of the Clocked CMOS OAI321 gate for
different input combinations. It confirms correct logic operation during the
evaluation phase and demonstrates low power consumption with controlled switching.

<img width="600" height="550" alt="image" src="https://github.com/user-attachments/assets/9a1d7b23-649d-416c-b25c-cbf8f559a135" />



