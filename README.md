Project Overview:

This project focuses on the design, simulation, and layout optimization of a two-stage CMOS operational amplifier (op-amp) using industry-standard tools like Cadence Virtuoso, Spectre. The two-stage op-amp is a fundamental building block in analog and mixed-signal circuits, widely used in applications such as data converters, filters, and sensor interfaces. The goal is to achieve high gain, bandwidth, phase margin, and low power consumption while meeting key performance specifications.

Key Design Objectives:

Supply voltage: 1.8 V 

High DC Gain: Achieve a gain > 60 dB to ensure precision amplification. 

Sufficient Bandwidth: Unity-gain Bandwith (UGB) of minimum 30MHz . 

Good Phase Margin: Maintain > 45° phase margin for stability. 

Low Power Consumption: Design for minimal power dissipation of 2 mW. 

Slew Rate & Output Swing: 20 V/µs to ensure fast transient response and adequate output voltage range. 

Laoad Capacitance: 2pF 

Design Methodology:

First Stage (Differential Amplifier): Provides high gain and common-mode rejection (CMRR).

Second Stage (Common-Source Amplifier): Boosts overall gain and drives the output.

Frequency Compensation (Miller Compensation): Ensures stability via pole-splitting (using compensation capacitor and nulling resistor).

Bias Circuitry: Uses current mirror for stable biasing.

Simulation & Verification:

DC Analysis: Check bias points and operating regions (saturation for MOSFETs).

AC Analysis: Measure gain, phase margin, and bandwidth.

Transient Analysis: Evaluate slew rate and settling time.

Corner Analysis: Assess robustness under process variations.



Learning Outcomes:

Hands-on experience in CMOS analog design/Layout.

Understanding of frequency compensation techniques.

Proficiency in EDA tools for circuit simulation/Layout.

Insight into trade-offs (speed vs. power, gain vs. bandwidth).

Tools & Technologies:

Schematic Design: Cadence Virtuoso / Spectre

Simulation: Spectre 

Layout: Virtuoso Layout XL 

Why This Project?

This project is ideal for me to enter in VLSI, analog IC design and layout, offering practical exposure to real-world op-amp design challenges. It also serves as a foundation for advanced topics like folded-cascode op-amps or low-noise amplifiers.
