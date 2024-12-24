# Three-Phase Half-Wave Rectifier Simulation

This repository contains a simulation of a three-phase half-wave rectifier created in MATLAB Simulink. The project showcases the working of the rectifier with thyristors, allowing for firing angle control and analysis of the system under different types of loads.

## Project Overview

The three-phase half-wave rectifier is a crucial component in power electronics, converting AC to DC while enabling control over the output by adjusting the firing angle of the thyristors. This project simulates:

- The output voltage and current waveforms for multiple firing angles.
- The voltage across the thyristors during operation.
- System behavior under various load types (e.g., resistive, inductive, and mixed loads).

## Circuit Design

Below is the schematic of the three-phase half-wave rectifier designed in Simulink:

![Three Phase Circuit](https://github.com/user-attachments/assets/bc54854c-1952-4af1-8c83-e340c6a1f5e9)

## Features

- **Firing Angle Control:** Analyze the effects of varying firing angles on output parameters.
- **Load Configurations:** Simulate with resistive (R), inductive (RL), and resistive-inductive (RLE) loads.
- **Thyristor Voltage Monitoring:** Observe thyristor voltage waveforms and understand their conduction and blocking behavior.
- **Output Visualization:** Display and analyze waveforms of output voltage and current.

## How to Use

1. Clone this repository to your local machine.
2. Open MATLAB and navigate to the project folder.
3. Open the Simulink model file (ThreePhase.slx).
4. Configure simulation parameters:
   - Set the firing angle as desired.
   - Choose the load type for the simulation.
5. Run the simulation to view results.

## Results

The simulation generates waveforms for:

- **Output Voltage and Current:**
  - The rectified DC waveform for different firing angles and load types.
  
- **Voltage Across Thyristors:**
  - Behavior of thyristors during conduction and blocking phases.

(Include any insights or notable observations you’ve gathered from the results here.)

## Applications

This project is a practical tool for:

- Understanding the fundamentals of controlled rectifiers in power electronics.
- Analyzing how load and firing angle influence the rectifier's output.
- Studying the behavior of thyristors in AC-DC conversion systems.

## Acknowledgments

Special thanks to MATLAB Simulink for providing the tools required to model and simulate the circuit.
