Analog Design of Digital Circuits
This repository contains designs and simulations of digital circuits, primarily implemented using Xschem for schematic design and Ngspice for simulations. The project explores various digital logic circuits with an emphasis on the analog characteristics of their behavior.

Table of Contents
Introduction
Main Project: 8-bit SRAM
Tools Used
Simulations
License
Introduction
The purpose of this project is to analyze and simulate digital circuits with a focus on their analog design aspects. This is done using Xschem, a tool for schematic capture, and Ngspice, a powerful simulator for analog and digital circuits.

This repository includes:

Digital circuit designs (gates, flip-flops, counters, etc.)
Post-layout analysis with analog insights
Test benches for circuit validation
Simulation results showcasing delay, power, and performance
Main Project: 8-bit SRAM
The core project of this repository is the 8-bit SRAM, designed with both read and write circuitry, found in the file digital_circuits/circuits/8RAMF.sch. This project demonstrates the design and simulation of a static random-access memory (SRAM) cell array and its corresponding control logic for read and write operations.

Tools Used
Xschem: Schematic capture tool used to design digital circuits.
Ngspice: Open-source simulation tool used for analog and mixed-signal circuit simulation.
GTKWave (optional): For viewing waveform simulations.
Installation and Usage Resources
For detailed steps on installation and basic usage of Xschem and Ngspice, refer to the Whyrd YouTube Channel:

Installation and Basic Usage Guide for Xschem and Ngspice
This video provides a comprehensive guide on setting up these tools and running basic simulations.

Simulations
Each circuit in this repository includes Ngspice simulation files. These simulations provide:

Delay Analysis: Time delays introduced due to parasitics.
Power Consumption: Analog power measurements during switching.
Performance Metrics: Circuit behavior under various load conditions.
Example Simulation: 8-bit SRAM
Schematic: 8RAMF.sch
Simulation File: 8RAMF.spice
Simulation Result: 8RAMF_waveform.vcd
The 8-bit SRAM schematic simulates the read and write operations, analyzing its performance through Ngspice, and the waveform results can be visualized using GTKWave.

License
This project is licensed under the MIT License. See the LICENSE file for details.
