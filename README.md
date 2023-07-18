# RTL to GDS Implementation of Low Power Configurable Multi Clock Digital System
This repository contains the project for the RTL to GDS implementation of a low power configurable multi-clock digital system. The system is designed to receive commands through a UART receiver, perform various functions such as register file reading/writing and processing using an ALU block, and transmit the results along with CRC bits using the UART transmitter communication protocol.

## Project Description
The main goal of this project is to design and implement a robust and efficient digital system that can handle multiple clocks and perform various operations. The system consists of several key components, including an ALU, Register File, Synchronous FIFO, Integer Clock Divider, Clock Gating, Synchronizers, Main Controller, UART TX, and UART RX.

## Project Phases
1- **RTL Design**: The system blocks are designed from scratch using RTL (Register Transfer Level) methodology. Each component is implemented with careful consideration of functionality and performance.<br /><br />
2- **Functional Verification**: The functionality of the system is verified using a self-checking testbench. This ensures that all components are functioning correctly and that the system as a whole performs as expected.<br /><br />
3- **Synthesis and Optimization**: The design is synthesized and optimized using the Design Compiler tool. Synthesis constraints are applied to achieve desired power, area, and timing goals.<br /><br />
4- **Timing Analysis and Optimization**: Timing paths are analyzed to identify and resolve setup and hold violations. Various techniques such as pipelining, retiming, and buffering are employed to meet timing requirements.<br /><br />
5- **Equivalence Checking**: The functionality equivalence of the synthesized design is verified using the Formality tool. This ensures that the optimized design still behaves equivalently to the original RTL design.<br /><br />
6- **Physical Implementation**: The system goes through the ASIC (Application-Specific Integrated Circuit) flow phases for physical implementation. This includes floorplanning, placement, clock tree synthesis, routing, and optimization to generate the final GDS (Graphic Data System) file.<br /><br />
7- **Post-layout Verification**: The functionality of the system is verified post-layout, taking into account actual delays introduced during the physical implementation process. This step ensures that the design performs as intended in real-world conditions.<br /><br />
