

 1. Project Overview

This project focuses on the transistor-level design and simulation of single-stage and two-stage CMOS operational transconductance amplifiers (OTAs) using Cadence Virtuoso and Spectre.

The work explores MOSFET characterization, differential input stages, current-mirror biasing, active loads, Miller compensation, and AC and transient performance analysis.

2. Design Implementations

 A. Single-Stage CMOS OTA

- NMOS differential input pair
- PMOS active-load/current-mirror configuration
- Tail-current biasing
- Transistor-level implementation and simulation

Design focus: Understanding differential operation, bias conditions, voltage gain, bandwidth, and power consumption.

 B. Two-Stage CMOS OTA With Miller Compensation

- Differential input stage with active load
- Second gain stage
- Miller compensation capacitor for frequency compensation
- Load-capacitance-based simulation and performance evaluation

Design focus: Investigating the relationship between gain, bandwidth, stability, slew rate, and power consumption.

 3. Design and Simulation Methodology

1. MOSFET characterization: Examine transistor behaviour and operating conditions.
2. Building-block design: Implement and analyse differential-pair and current-mirror circuits.
3. OTA implementation:Construct single-stage and two-stage transistor-level schematics.
4. Bias and operating-point analysis: Inspect transistor operating conditions to assess circuit operation.
5. AC analysis: Evaluate gain and phase response across frequency.
6. Transient analysis: Observe input/output waveforms under applied test signals.
7. Performance evaluation:Compare the reported gain, bandwidth, slew rate, and power metrics.

 4. Simulation Environment

 Parameter - Description

 EDA tool - Cadence Virtuoso 
 
 Simulator -Spectre 
 
 Technology library - gpdk180
 
 Design level - Transistor-level CMOS
 
 Analyses - AC and transient 

 5. Reported Performance

The project evaluates the following metrics for the two OTA architectures:

- DC voltage gain
- Bandwidth / gain-bandwidth product
- Slew rate
- Power dissipation
- Phase margin and stability
- Common-mode rejection ratio (CMRR), where evaluated


 6. Key Technical Concepts

- MOSFET operating regions and biasing
- Differential amplifiers and active loads
- Current mirrors and bias-current generation
- Small-signal gain and frequency response
- Miller compensation and frequency stability
- Slew-rate limitations and capacitive loading
- Power–performance trade-offs in analog IC design

 7. Repository Contents

- `README.md` — Project overview, architecture, and methodology
- `CMOS_OTA_Portfolio_Report.pdf` — Detailed project summary, schematics, simulation plots, and reported results

