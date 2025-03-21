# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

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
![WhatsApp Image 2025-03-21 at 12 35 24_bb0d7dd6](https://github.com/user-attachments/assets/72348f56-a2c5-4ca8-9662-735b91458fad)
![WhatsApp Image 2025-03-21 at 12 35 23_e8a54d9d](https://github.com/user-attachments/assets/09cd1711-42c3-4fbf-b507-955e8709a85a)

### 2. Transient Response Setup
![WhatsApp Image 2025-03-21 at 12 35 23_25d5b72d](https://github.com/user-attachments/assets/7ca7b651-960f-4faa-b04f-555cb5ea39fd)
![WhatsApp Image 2025-03-21 at 12 35 24_ee82d344](https://github.com/user-attachments/assets/0228d1d0-833c-4dce-9eb2-06f37f0ee118)

## Output

### 1. Transient Analysis Output
![WhatsApp Image 2025-03-21 at 12 35 24_23480190](https://github.com/user-attachments/assets/d9ccfa2c-9ee5-4671-9a78-aa2bb973533a)

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
