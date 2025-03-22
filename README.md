# Exp_MG No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. Schematic of Full Custom 2:1 MUX
![WhatsApp Image 2025-03-22 at 11 24 31_d04b0624](https://github.com/user-attachments/assets/05a8cec9-8d9e-46a3-99da-9c247b80e3c7)
![WhatsApp Image 2025-03-22 at 11 24 31_c7163e37](https://github.com/user-attachments/assets/4938c0d3-e0b9-40d4-a686-15edfbca7e37)

### 2. Transient Response Setup
![WhatsApp Image 2025-03-22 at 11 24 32_2f071ed0](https://github.com/user-attachments/assets/e78614bf-a914-4d11-bc92-3cbe9d0faee1)


## Output

### 1. Transient Analysis Output
![WhatsApp Image 2025-03-22 at 11 24 31_703eeee1](https://github.com/user-attachments/assets/f1f35c57-8e9d-49af-b415-0644fd8869f6)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
