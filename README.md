## VLSI SKILL ASSESSMENT-2

## RC oscillator Design and Implementation using Cadence EDA Tools

## Objective:
To design and implement an RC Oscillator circuit using Cadence EDA tools, simulate its functionality, and analyze key parameters like oscillation frequency, stability, and amplitude, helping to understand its behavior in signal generation and timing applications.

## Overview:
The RC Oscillator circuit is designed to generate a stable periodic waveform, making it useful in signal generation and timing applications. The goal of this assignment is to create the circuit schematic, perform simulations, and analyze its output characteristics, including oscillation frequency, waveform stability, and amplitude under varying circuit parameters.

## Circuit diagram:
![Screenshot (87)](https://github.com/user-attachments/assets/b33fee16-1d73-4999-9fb7-71a5861ff922)


Getting Started
Setting Up Cadence Virtuoso
Open Terminal:

Right-click and open the terminal window.
Enter the following commands:
sh
Copy code
csh
source /cadence/install/cshrc
virtuoso

## Creating New Library & Schematic:

Library: File -> New -> Library, name it (e.g., VLSILAB_EXP_2), and attach it to the technology library gpdk045.
Schematic Cell View: Go to File -> New -> Cell View, set up the library, cell, and view as follows:
Library: Select your created library.
Cell Name: E.g., RC oscillator.
View: Schematic.
Adding Components and Connections:

Use the instance tool to add components such as nmos1v and pmos1v.
Add input and output pins, and make all connections using the wire tool.
![Screenshot (46)](https://github.com/user-attachments/assets/5ad67088-5a10-4eed-a42b-e858638c9264)

## DC analysis:

Go to Create -> Cell View -> From Cell View to generate the symbol automatically.
Customize the symbol if needed.
Simulation with Spectre
Set Up Simulation:

Launch ADE L (Analog Design Environment).
Set the simulation to Spectre and configure settings in Setup -> Simulation Directory/Host.
Specify Analysis Type:

![Screenshot (85)](https://github.com/user-attachments/assets/f8023522-c6d6-482b-a1fe-91872f9c9456)


![Screenshot (84)](https://github.com/user-attachments/assets/09fcd3d3-18c4-4a3d-96bb-4e7fee2f9f69)

Use Analysis -> Choose to configure settings for DC sweep or transient analysis.
Choose output voltages/currents to be plotted.
Run Simulation:

Execute Simulation -> Netlist and Run to simulate the RC oscillator circuit.
## Results:
After simulation, verify the expected hysteresis characteristics of the RC oscillator. The simulation should show distinct oscillation frequency, with stable high and low states, demonstrating signal generation and timing.

![Screenshot 2024-11-15 184515](https://github.com/user-attachments/assets/82d55c26-cd0f-4d34-9012-8cbb1b8afa34)


## Conclusion:
The design and simulation of the RC Oscillator using Cadence EDA tools were successful, demonstrating its ability to generate stable periodic waveforms. The analysis confirmed its suitability for applications in signal generation and timing, with key parameters such as oscillation frequency and stability meeting design expectations.
