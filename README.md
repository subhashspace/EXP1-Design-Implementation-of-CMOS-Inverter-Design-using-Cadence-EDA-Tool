# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image](https://github.com/user-attachments/assets/e3e06487-52b2-4b56-9dcd-03c5c9394a4c)


#### 2. Schematic of CMOS Inverter:

   <img width="1682" height="1011" alt="Screenshot 2025-08-28 162320" src="https://github.com/user-attachments/assets/790166f5-ea62-4a9c-af98-1109c7b72361" />


#### 3. Transient Response Setup:

!<img width="509" height="601" alt="Screenshot 2025-08-28 161849" src="https://github.com/user-attachments/assets/5ae466b3-08b0-4975-aaca-ce237da51be4" />
<img width="1920" height="1200" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/012c34c5-bef0-4ccf-b059-a0c1b5fa0b10" />

## Output
#### 1.Transient Analysis Output
  <img width="1919" height="1198" alt="Screenshot 2025-08-28 162531" src="https://github.com/user-attachments/assets/24b9d29b-dc7e-47f2-afb5-bb2024db5e1d" />

## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











