# JK-flipflop-CMOS-using-Synopsys
---
#### This repository is about JK Flip-Flop 28nm CMOS using Synopsys Custom Compiler tool.
---
## Table of Contents
---
* [Abstract](#Abstract)
* [Synopsys Custom Compiler Tool](#Synopsys-Custom-Compiler-Tool)
* [Reference Circuit Diagram](#Reference-Circuit-Diagram)
* [Reference Circuit Waveform](#Reference-Circuit-Waveform)
* [Synopsys Simulation]()
    * Schematic
    * Symbol
    * Test Bench
        * Circuit
        * Signal Parameters
        * Transient Settings
    * Netlist
    * Waveform
* Conclusion
* Author
* Acknowledgement
* References

## Abstract
---
Digital circuits are composed of logic functions which are then implemented using building blocks. AND, OR and NOT are basic building blocks of every digital logic. Many different modules are created using combination of these gates to achieve various functionality. One of such modules is JK flip-flop. This flip-flop is one of the most used flip-flop over every digital electronics. The inputs to this flip flop are ‘J’ and ‘K’. The JK flip flop work in the same way as the SR flip flop. The only difference between JK flip flop is that when both inputs of SR flip flop is set to 1, the circuit produces the invalid states as outputs, but in case of JK flip 
flop, there are no invalid states even if both ‘J’ and ‘K’ flip flop are set to 1. The JK flip flop is a gated SR flip flop having the addition of a clock input circuitry. The invalid or illegal output condition occurs when both of the inputs are set to 1 and are prevented by the addition of a clock input circuit. The JK flip flop is an improved clocked SR flip flop, but it still suffers from “race around” condition. We have to keep short timing pulse for avoiding this condition.

## Synopsys Custom Compiler Tool
---
<p align="center">
<img src="media/custom_compiler.png"></br>
  Figure : Synopsis Custom Compiler Tool
</p>

## Reference Circuit Diagram
---
<p align="center">
<img src="media/reference-circuit.png"></br>
  Figure : Synopsis Custom Compiler Tool
</p>

## Reference Circuit Waveform
---
<p align="center">
<img src="media/reference-waveform.png"></br>
  Figure : Synopsis Custom Compiler Tool
</p>
