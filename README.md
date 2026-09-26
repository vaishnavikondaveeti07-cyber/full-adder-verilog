# full-adder-verilog
Verilog HDL design and simulation of a Full Adder circuit with testbench.
## Overview
Implementation and testbench verification of a 1-Bit Full Adder circuit using Verilog HDL.

## Logic Equations
- **Sum** = A ^ B ^ Cin
- **Cout** = (A & B) | (B & Cin) | (A & Cin)

## Files Included
- `full_adder.v`: RTL module design
- `full_adder_tb.v`: Testbench for verification
