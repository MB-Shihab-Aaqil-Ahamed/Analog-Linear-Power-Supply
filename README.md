# Analog Linear Power Supply

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This repository contains the design files and documentation for the Analog Linear Power Supply project, developed as part of a project at [Your Institution Name]. The Analog Linear Power Supply is designed to provide a stable voltage and current output for driving high-power loads under constant conditions.

## Table of Contents

- [Abstract](#abstract)
- [Introduction](#introduction)
- [Methodology](#methodology)
- [PCB Design](#pcb-design)
- [Enclosure Design](#enclosure-design)
- [Discussion](#discussion)
- [Acknowledgement](#acknowledgement)
- [Appendices](#appendices)
- [Data Sheet of Linear Power Supply](#data-sheet-of-linear-power-supply)

## Abstract

The Analog Linear Power Supply project focuses on designing a 10V linear power supply capable of delivering up to 10A of current. The project involves multiple stages, including step-down transformation, full-wave rectification, smoothing, voltage regulation, and current limiting. The design also incorporates protection mechanisms for overload and short circuit conditions.

## Introduction

The Analog Linear Power Supply project aims to provide a reliable and stable voltage and current output for high-power loads. This is achieved through a multi-stage process that involves transforming the input voltage, rectification, voltage smoothing, regulation, and current limiting. The project addresses challenges associated with handling high current while minimizing current error.

## Methodology

The methodology of the project involves the following key stages:

1. Step Down Transformer: A step-down transformer is used to reduce the 230V input voltage to a more manageable level.

2. Full-Wave Rectification: The GBPC3506W Bridge rectifier is used to rectify the voltage, converting it into pulsating DC.

3. Smoothing Stage: A 10mF capacitor is employed to smooth the rectified output, reducing voltage ripples.

4. Regulating Stage: The regulated voltage is achieved using two transistors (MJ4502 and BC547A as Sziklai pair), a 10V Zener diode, a 150Ω resistor, and a diode.

5. Current Limiting Stage: The circuit incorporates a current limiting mechanism to restrict the maximum current output to 10A.

## NI Multisim Simulation

<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/NIMultisim Simulation.png"></p>
<br>

## PCB Design

The PCB design is optimized for the specific requirements of the Analog Linear Power Supply. The layout ensures proper heat dissipation through the use of a heat sink with the MJ4502 transistor and the bridge rectifier.

## Schemetic of the PCB
<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Schematic.jpg" ></p>
<br>

## PCB Layout
<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/PCB Layout.png" ></p>
<br>

## PCB Design

Top Layer                  |  Bottom Layer               
:-------------------------:|:-------------------------:
<img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Top PCB Design.png" width="500" height="400"> | <img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Bottom PCB Design.png" width="500" height="400"> 
<br>

## PCB Design

<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/PCB Design.png" ></p>
<br>


## Enclosure Design

The enclosure for the Analog Linear Power Supply is designed to accommodate the components while ensuring proper ventilation for heat dissipation. The enclosure includes a 12V DC fan to enhance cooling.

## Enclosure Hand Sketch Design

<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Enclosure Design.jpg" ></p>
<br>
<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Product Design.jpg" ></p>
<br>

## Bill of Material

<p align="center"><img src="https://github.com/MB-Shihab-Aaqil-Ahamed/Analog-Linear-Power-Supply/blob/master/Images/Bill_of_Matrials.png" ></p>
<br>

## Acknowledgement

The project was developed as part of a project at [Your Institution Name]. Special thanks to the faculty, mentors, and contributors for their guidance and support throughout the development process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
