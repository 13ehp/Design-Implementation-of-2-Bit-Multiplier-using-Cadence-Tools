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
<img width="1619" height="861" alt="Screenshot 2025-10-31 002544" src="https://github.com/user-attachments/assets/d7a18c0e-2cb1-41cb-b55b-09fea13c3e5d" />
<img width="1619" height="859" alt="Screenshot 2025-10-31 002602" src="https://github.com/user-attachments/assets/2a25e981-3488-4cb9-b212-7016838b7f48" />
<img width="1620" height="857" alt="Screenshot 2025-10-31 002642" src="https://github.com/user-attachments/assets/489e5ace-7897-4db4-b791-8b19f13e8de5" />

## Output

<img width="966" height="236" alt="image" src="https://github.com/user-attachments/assets/42b155e8-a415-4426-bdc8-3a696c699f2b" />

<img width="1620" height="862" alt="Screenshot 2025-10-31 002727" src="https://github.com/user-attachments/assets/00c91f00-d598-4e1d-90c7-16e54cd9a2c9" />


## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
