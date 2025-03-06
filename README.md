# Mano Microprogram Computer

This document provides an overview of the Mano Microprogram Computer, an implementation of the Mano Computer architecture that utilizes microprogramming for its control unit. The Mano Computer, designed by Charles R. Mano, is a simple yet powerful educational tool for understanding the basics of computer architecture.

## Table of Contents

- [Introduction](#introduction)
- [Microprogramming](#microprogramming)
- [Architecture](#architecture)
- [Microprogram for Control Memory](#microprogram-for-control-memory)
- [Usage](#usage)

## Introduction

The Mano Computer is a conceptual model for a computer that includes a central processing unit (CPU), memory, and input/output devices. It is designed to illustrate the fundamental operations of a computer at the hardware level. The microprogrammed version of the Mano Computer introduces a control unit that is driven by a microprogram stored in control memory, offering a detailed view into the micro-operations and control signals that drive the CPU.

## Microprogramming

Microprogramming is a technique for implementing the control logic of a computer's CPU. Instead of hardwiring the control unit, microprogramming uses a sequence of microinstructions stored in a special memory called control memory. Each microinstruction specifies the control signals for one or more micro-operations, allowing for complex instruction execution sequences.

## Architecture

The architecture of the Microprogrammed Mano Computer includes the following components:

- **Arithmetic Logic Unit (ALU):** Performs arithmetic and logical operations.
- **Control Unit:** Utilizes microprogramming to control the sequence of operations.
- **Memory Unit:** Stores data and instructions.
- **Input/Output (I/O) Unit:** Manages data exchange with external devices.

## Microprogram for Control Memory

The control memory stores the microprogram that dictates the operation of the Mano Computer. Each entry in the control memory corresponds to a microinstruction that controls various parts of the computer for a single clock cycle. The microprogram for the Mano Computer includes sequences for basic operations such as ADD, STORE, BRANCH, and more.

## Usage

To simulate the Microprogrammed Mano Computer, follow these steps:

1. Clone the repository containing the project files.
2. Open the project in Proteus or a similar simulation software.
3. Run the simulation to observe the execution of microprogrammed instructions.
---
![image](https://github.com/user-attachments/assets/ed8d415f-b8b9-4bfc-bd92-65f4214190fb)





