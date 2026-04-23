# Overview

A 3-bit digitally controlled Pulse Width Modulation (PWM) generator designed as a mixed-signal circuit in eSim, with digital logic simulated via NgVeri/Makerchip (Verilog) and the analog portion simulated in NgSpice.

How it works:

- A 3-bit binary input feeds a 3x8 decoder (Verilog).
- The decoder switches an array of MOSFETs connected to the taps of a resistor divider, acting as a DAC.
- The DAC output is compared against a triangular wave through an op-amp (LM741) to produce a PWM signal whose duty cycle is controlled by the digital input (8 levels).

See `README.md` for the full circuit diagrams, netlist, simulation plots, and run instructions.
