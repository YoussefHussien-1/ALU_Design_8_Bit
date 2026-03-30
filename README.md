# 8-bit Arithmetic Logic Unit (ALU) Design & Simulation

## 📌 Project Overview

This project features the design and simulation of an **8-bit Arithmetic Logic Unit (ALU)**, built from fundamental digital logic gates. This ALU serves as the computational core of a micro-architecture, capable of performing arithmetic and bitwise logical operations on two 8-bit inputs.

## 🛠️ Supported Operations

The ALU supports **5 core operations**, selected via a control unit and a **4x1 Multiplexer (MUX)** network:

1.  **ADD (Addition):** Performed using an 8-bit Full Adder chain.
2.  **SUB (Subtraction):** Implemented using 2's complement logic.
3.  **AND:** Bitwise logical AND operation.
4.  **OR:** Bitwise logical OR operation.
5.  **XOR:** Bitwise logical XOR operation.

## 🏗️ Hardware Architecture

  * **8-bit Data Path:** All internal buses and logic gates are optimized for 8-bit parallel processing.
  * **Multiplexer (MUX) Logic:** A custom **4x1 MUX** (and 2x1 stages) is used to select the desired operation based on the Control Unit signals.
  * **Full Adder Circuitry:** Designed using XOR, AND, and OR gates to handle carry-in and carry-out logic.
  * **Control Unit:** Decodes the operation selection bits to enable the specific logic path.

## 🖥️ Simulation (Proteus)

The design was fully simulated and verified in **Proteus**:

  * **Input Handling:** Used Logic States/Toggles to provide 8-bit binary inputs (A & B).
  * **Output Visualization:** 8-bit Logic Probes/LEDs to display the result in real-time.
  * **Verification:** Tested all operations with various edge cases (e.g., zero result, maximum 8-bit value, carry propagation).


-----

## 👨‍💻 Author

**Youssef**

  * **Nile University** | Computer Science Sophomore.
  * Passionate about Digital Logic, Computer Architecture, and Embedded Systems.
