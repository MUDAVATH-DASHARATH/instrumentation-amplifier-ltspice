# Three-Op-Amp Instrumentation Amplifier

## Overview

This project focuses on the design and simulation of a three-op-amp instrumentation amplifier using LTspice.

The amplifier is designed to accurately amplify low-level differential signals while rejecting common-mode noise. The performance of the circuit is evaluated through simulation.

## Objectives

- Design a three-op-amp instrumentation amplifier.
- Amplify low-level differential signals.
- Achieve high common-mode rejection.
- Analyze differential gain and common-mode gain.
- Evaluate input impedance and bandwidth.
- Verify circuit performance using LTspice.

## Software and Tools

- LTspice
- Operational Amplifiers
- Analog Circuit Design
- Differential Signal Analysis

## Circuit Configuration

The instrumentation amplifier consists of three operational amplifiers.

The first two op-amps provide input buffering and amplification, while the third op-amp performs differential subtraction.

The differential output is given by:

Vout = G(V1 - V2)

where:

- V1 and V2 are the input signals.
- G is the differential voltage gain.

## Performance Parameters

The circuit is analyzed based on:

- Differential Gain
- Common-Mode Gain
- Common-Mode Rejection Ratio (CMRR)
- Input Impedance
- Bandwidth
- Output Response

## CMRR

The Common-Mode Rejection Ratio is calculated as:

CMRR = 20 log10(Ad / Ac)

where:

- Ad = Differential Gain
- Ac = Common-Mode Gain

A high CMRR indicates better rejection of unwanted common-mode signals.

## Simulation

The circuit was designed and simulated using LTspice.

![Circuit Diagram](Images/Circuit_Diagram.png)

## Results

The simulation results are analyzed for:

- Differential signal amplification
- Common-mode signal rejection
- Gain response
- Frequency response
- Output waveform

## Applications

Instrumentation amplifiers are commonly used in:

- Biomedical instrumentation
- ECG systems
- Strain gauge measurement
- Temperature sensing
- Pressure sensing
- Industrial measurement
- Data acquisition systems

## Future Scope

- Hardware implementation
- PCB design
- Low-noise optimization
- Improved CMRR
- Sensor interfacing
- Low-power implementation
