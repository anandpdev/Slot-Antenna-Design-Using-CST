# Design and Simulation of a Microstrip Slot Antenna for 2.4 GHz Wireless Communication Applications Using CST

## Project Overview
This project focuses on the design, modelling, and electromagnetic simulation of a microstrip-line-fed rectangular slot antenna operating in the 2.4 GHz ISM band.

The antenna was designed using an FR4 substrate and simulated using CST Studio Suite. The project explores antenna characteristics such as return loss, VSWR, surface current distribution, directivity, and radiation patterns.

## Objectives
- Design a rectangular microstrip slot antenna for 2.4 GHz applications.
- Calculate antenna dimensions using standard design equations.
- Model and simulate the antenna using CST Studio Suite.
- Analyse S11 response and VSWR.
- Study surface current distribution and far-field radiation patterns.

## Design Specifications

| Parameter | Value |
|---|---|
| Operating frequency | 2.4 GHz |
| Resonant frequency | 2.416 GHz |
| Substrate material | FR4 |
| Relative permittivity | 4.3 (final CST model) |
| Substrate thickness | 1.6 mm |
| Slot length | 57.5 mm |
| Slot width | 3 mm |
| Feed line width | 3 mm |
| Feed stub length | 14 mm |
| Board dimensions | 60 × 70 mm |

## Tools Used
- CST Studio Suite
- Electromagnetic Simulation
- Antenna Design and Modelling

## Simulation Results

| Performance Parameter | Result |
|---|---|
| Minimum S11 | -6.16 dB |
| Resonant frequency | 2.416 GHz |
| VSWR | Approximately 2.9 |
| Directivity | 4.98 dBi |
| Radiation efficiency | Approximately 82% |
| Total efficiency | Approximately 62% |
| Realised gain | Approximately 2.93 dBi |

## Key Observations
- The antenna resonates at 2.416 GHz, close to the 2.4 GHz design target.
- The radiation pattern exhibits bidirectional, dipole-like characteristics.
- Surface current is concentrated around the slot edges.
- The simulated S11 is -6.16 dB, so the design requires further impedance matching improvement.

## Future Improvements
- Optimise feed stub length and slot dimensions.
- Improve impedance matching to achieve S11 below -10 dB.
- Fabricate the antenna and validate its performance using a Vector Network Analyser (VNA).

## Learning Outcomes
- Practical experience in antenna design and modelling.
- Understanding of microstrip feeding techniques.
- Experience with electromagnetic simulation using CST.
- Analysis of antenna parameters and radiation characteristics.

## Project Details
- **Domain:** Electronics and Communication Engineering
- **Project Type:** Academic Team Project
- **Course:** Antenna Design Using EM Simulator
- **Simulation Software:** CST Studio Suite
- **Target Applications:** Wi-Fi and Bluetooth (2.4 GHz ISM Band)
