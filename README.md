# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

![Screenshot 2025-05-10 160454](https://github.com/user-attachments/assets/7a700f59-c4b4-4006-b791-0a4edf7d1e57)

![Screenshot 2025-05-10 160505](https://github.com/user-attachments/assets/4031c7a7-7c0f-4397-a936-ac4f90c4f402)

### Schematicand Symbol of 2-Input EX-OR Gate:

![Screenshot 2025-05-10 160515](https://github.com/user-attachments/assets/880ad1be-e8b3-4111-b2ea-2b2c7eb1fd14)

![Screenshot 2025-05-10 160523](https://github.com/user-attachments/assets/4230854b-5f8e-43d0-9875-258b457660e3)

### Schematicand Symbol of Half Adder:
![Screenshot 2025-05-10 160535](https://github.com/user-attachments/assets/5d98f983-d6b7-42b9-8f16-17407b2010b2)

![Screenshot 2025-05-10 161100](https://github.com/user-attachments/assets/bfaa7af0-6785-46e4-b434-87d677af5807)

### Schematic of 2-Bit Multiplier:
![Screenshot 2025-05-20 213344](https://github.com/user-attachments/assets/2774c741-62f6-4664-a56b-bb6c1e8de90d)


## Output
### Transient Analysis Output:
![Screenshot 2025-05-20 213459](https://github.com/user-attachments/assets/866cb2bb-50d5-4d63-bbaa-f242be97b926)
![Screenshot 2025-05-20 213558](https://github.com/user-attachments/assets/6deaa1bc-5d4e-4dc0-aa1e-bdd8854adadc)
![Screenshot 2025-05-20 213904](https://github.com/user-attachments/assets/1ddb6ae0-d30a-4205-862a-728e71422e22)
![Screenshot 2025-05-20 213650](https://github.com/user-attachments/assets/5544bee2-4fec-4993-b95c-bef7558b7826)






Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
