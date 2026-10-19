# CMOS OTA Design and Simulation

**Transistor-Level Analog IC Design | Cadence Virtuoso | Spectre | gpdk180**

---

## Project Overview

This project focuses on the design and simulation of single-stage and two-stage CMOS Operational Transconductance Amplifiers (OTAs) using Cadence Virtuoso.

The designs are implemented at the transistor level using the gpdk180 technology library. The project explores MOSFET characterization, differential-pair circuits, current mirrors, active loads, and Miller compensation.

## Circuit Architectures

### 1. Single-Stage CMOS OTA

- NMOS differential input pair
- PMOS active load
- Tail-current biasing
- Transistor-level implementation and simulation

**Objective:** Study voltage gain, bandwidth, biasing, and power consumption.

### 2. Two-Stage CMOS OTA

- Differential input stage with active load
- Second gain stage
- Miller compensation capacitor
- Capacitive-load simulation

**Objective:** Investigate gain, bandwidth, stability, slew rate, and power trade-offs.

## Design Methodology

1. MOSFET characterization and operating-point analysis
2. Differential-pair and current-mirror implementation
3. Single-stage and two-stage OTA design
4. Bias-condition verification
5. AC analysis of gain and phase response
6. Transient analysis of input and output waveforms
7. Evaluation of reported performance metrics

## Simulation Environment

| Parameter | Details |
|---|---|
| EDA Tool | Cadence Virtuoso |
| Circuit Simulator | Spectre |
| Technology Library | gpdk180 |
| Design Level | Transistor level |
| Analyses | AC and transient |

## Performance Evaluation

The designs are evaluated using the following metrics, where measured:

- DC voltage gain
- Bandwidth and gain-bandwidth product
- Slew rate
- Power dissipation
- Phase margin
- Common-mode rejection ratio (CMRR)


## Key Technical Concepts

- MOSFET biasing and operating regions
- Differential amplifiers
- Current mirrors and active loads
- Small-signal gain and frequency response
- Miller compensation
- Stability and phase response
- Slew-rate limitations
- Analog circuit power-performance trade-offs

## Tools and Technologies

- Cadence Virtuoso
- Spectre
- gpdk180 technology library

## Project Files

- `README.md` — Project overview and technical methodology
- `CMOS_OTA_Portfolio_Report.pdf` — Project report with circuit schematics, simulation plots, and reported results

---


