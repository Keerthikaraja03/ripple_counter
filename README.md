# ripple_counter


AIM:

To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

4 Bit Ripple Counter

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.


<img width="702" height="397" alt="image" src="https://github.com/user-attachments/assets/ce046b22-49d2-4aa3-a0cd-c51e9eb03327" />


In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.


<img width="313" height="243" alt="image" src="https://github.com/user-attachments/assets/226e3608-6db0-4fc3-8b6c-aa6f7701ec78" />


Procedure

/* write all the steps invloved */

PROGRAM

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

Developed by: Keerthika R


RegisterNumber: 25017601

RTL LOGIC FOR 4 Bit Ripple Counter

TIMING DIGRAMS FOR 4 Bit Ripple Counter

RESULTS
