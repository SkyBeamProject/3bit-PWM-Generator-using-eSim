# Overview

A 3-bit digitally controlled PWM generator designed as a mixed-signal circuit in eSim. A 3-bit input feeds a decoder and MOSFET array (acting as a DAC) whose output is compared against a triangular wave by an op-amp to produce PWM with one of eight duty cycles. The decoder is modeled in Verilog via Makerchip/NgVeri; the analog stage is simulated in NgSpice.
