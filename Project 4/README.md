# ELECENG 2EI4 – Design Project 4: MOSFET-Based XOR Gate
This repo captures the design, sizing, simulation, and bench validation of a 12-transistor CMOS XOR gate (PUN/PDN plus two input inverters). 
The Boolean derivation (via DeMorgan) drives the series/parallel structure; device sizing targets balanced pull-up/pull-down with a ~2.5 PMOS:NMOS width ratio for symmetric switching. 
Validation with an Analog Discovery 3 confirms the XOR truth table, static levels at VDD = 5 V (≈4.10 V high, ≈2.12 mV low), and timing under a 100 nF load (rise/fall ≈ 242 µs; propagation delays from 10–90% / 90–10%). 
The repo includes the schematic, sizing rationale, AD3 setup, oscilloscope captures, and a discussion of design trade-offs.
