**Ripple Adder Using IP Block Design:-**

**Description:**

This project implements a ripple carry adder using IP (Intellectual Property) block design methodology. A ripple carry adder is a digital circuit that performs the addition of two binary numbers by cascading full adder modules. IP block design involves using pre-designed and pre-verified intellectual property blocks provided by FPGA (Field-Programmable Gate Array) vendors, such as Xilinx or Intel.

**Table of Contents:**

1. Introduction

2. Creating An IP Block

3. Implementation

4. Block Diagram

5. RTL Schematic

6. Waveforms


**Introduction:**

The ripple carry adder is a fundamental component in digital design and is often used in arithmetic circuits. It adds two binary numbers bit by bit, starting from the least significant bit (LSB) and propagating any carry to the next higher bit. This project aims to implement a ripple carry adder using IP block design techniques, leveraging pre-designed slice modules provided by FPGA vendors and own-designed full adder modules.

![Screenshot 2024-02-26 165407](https://github.com/krishnavenkatasudheer/Ripple_Adder_Using_IP_Block/assets/149562800/2e640b71-fa41-430e-986c-908930925115)

![Screenshot 2024-02-26 165621](https://github.com/krishnavenkatasudheer/Ripple_Adder_Using_IP_Block/assets/149562800/d8156b40-f91a-47b9-b245-57ba3854f77c)

Slice: Slice can be used to take single input value from the array of input values to give input to the single bit full adder circuit.

**Creatibg An IP Block:**

By Using the provided Full adder verilog code we need to create the IP Block Called Full_Adder, and we have to use it for creating the block diagram. To create an IP Block using Full adder code, Tools -> Create and package new IP -> Create with existing file -> check the parameters -> Package IP.

Now the new IP Block named Full_Adder was added to IP repository. By using that Full_Adder block and slice block which is provided by the xilinx vendor we need to create the block diagram of the Riiple_Carry_Adder.


**Implementation:**
1. Open the project in your FPGA vendor's development environment (e.g., Xilinx Vivado, Intel Quartus Prime).
2. Import the necessary IP blocks for full adders provided by the vendor.( i.e., Slice blocks)
3. Instantiate and interconnect the full adder IP blocks to form the ripple carry adder.
4. Create the HDL Wrapper file from the design file to simulate the diesign.
5. Simulate and verify the functionality of the ripple carry adder.
6. Synthesize and implement the design on your FPGA development board.
7. Test the implemented design by providing input binary numbers and observing the output sum.

**Block Diagram:**

![Block_Design](https://github.com/krishnavenkatasudheer/Ripple_Adder_Using_IP_Block/assets/149562800/3b42a2ed-f352-4d7c-9305-d08385f90e0f)

**RTL Schematic:**

![RTL_Schematic](https://github.com/krishnavenkatasudheer/Ripple_Adder_Using_IP_Block/assets/149562800/baa6a051-226f-4ca3-9d60-5d1792ff036e)

**Waveforms:**

![Screenshot 2024-02-26 171605](https://github.com/krishnavenkatasudheer/Ripple_Adder_Using_IP_Block/assets/149562800/ce6afed7-4e9c-444c-b220-04ebacf0e0e9)





