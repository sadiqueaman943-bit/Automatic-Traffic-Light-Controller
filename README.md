# Automatic Traffic Light Controller

## Overview

A traffic light control system designed using two NE555 timer ICs
operating in astable mode and simulated in LTspice.

## Objective

To simulate an automatic traffic-light signal sequence using 555-based
timing circuits.

## Components Used

-   2 × NE555 Timer ICs
-   Red, Yellow and Green LEDs
-   100 µF capacitors
-   100 kΩ and 47 kΩ timing resistors
-   330 Ω and 180 Ω LED current-limiting resistors
-   9 V DC supply

## Working Principle

Two NE555 timers act as astable multivibrators to generate timing
pulses. RC networks determine the timing delays.

The traffic sequence follows:

**Red → Yellow → Green → Yellow → Repeat**

The LED outputs are driven through current-limiting resistors, and the
sequence repeats continuously.

## LTspice Simulation

The circuit was simulated using transient analysis in LTspice. The
simulation verifies the sequential operation of the red, green and
yellow light outputs over time.

### Files

-   `traffic light.asc` --- LTspice schematic
-   `traffic light.raw` --- simulation waveform data
-   `traffic light.op.raw` --- operating-point data
-   `traffic light.log` --- LTspice simulation log
-   `Circuit_Schematic.png` --- circuit schematic
-   `Simulation_Waveforms.png` --- simulated output waveforms
-   `Project_Report.pdf` --- project report

## Results

The LTspice waveforms show the three traffic-light outputs switching in
the intended sequence, demonstrating the operation of the automatic
traffic controller.

## Applications

-   Basic traffic automation model
-   Educational electronics laboratory demonstration
-   Demonstration of timer-based sequential control

## Tools

**LTspice**

## Reference

Project report: `Project_Report.pdf`
