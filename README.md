# RTL to GDS Implementation of Low Power Configurable Multi Clock Digital System
This repository contains the project for the RTL to GDS implementation of a low power configurable multi-clock digital system. The system is designed to receive commands through a UART receiver, perform various functions such as register file reading/writing and processing using an ALU block, and transmit the results along with CRC bits using the UART transmitter communication protocol.

## Project Description
The main goal of this project is to design and implement a robust and efficient digital system that can handle multiple clocks and perform various operations. The system consists of several key components, including an ALU, Register File, Synchronous FIFO, Integer Clock Divider, Clock Gating, Synchronizers, Main Controller, UART TX, and UART RX.

## Project Phases
Project Phases
1- **RTL Design**: The system blocks are designed from scratch using RTL (Register Transfer Level) methodology. Each component is implemented with careful consideration of functionality and performance.<br />
2- **Functional Verification**: The functionality of the system is verified using a self-checking testbench. This ensures that all components are functioning correctly and that the system as a whole performs as expected.<br />
