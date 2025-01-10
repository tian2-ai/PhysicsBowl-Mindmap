---
title: Circuit Analysis Mindmap
markmap:
  colorFreezeLevel: 2
---

## Physics Bowl Overview

- Number of Problems: 2 per exam
- Difficulty Level: Intermediate (<40)

## Introduction

- Circuit analysis focuses on applying Ohm’s Law, Kirchhoff's Laws, and power relationships.
- Topics include resistor and capacitor networks, RC and RL circuits, and dielectric effects on capacitance.

## Key Concepts

### Ohm's Law
- Relation:
  $$
  V = I R
  $$

### Power in Circuits
- Power Formulas:
  $$
  P = IV = I^2 R = \frac{V^2}{R}
  $$

### Capacitance
- Charge on a Capacitor:
  $$
  Q = C V
  $$
- Energy Stored:
  $$
  U = \frac{1}{2} C V^2
  $$

### Inductors
- Energy Stored:
  $$
  U_L = \frac{1}{2} L I^2
  $$

### Kirchhoff's Laws
- Voltage Law (KVL):
  - Sum of voltage changes in a closed loop equals zero.
- Current Law (KCL):
  - Sum of currents entering a node equals the sum of currents leaving.

### Resistors in Series and Parallel
- Series:
  $$
  R_{\text{series}} = R_1 + R_2 + \dots
  $$
- Parallel:
  $$
  \frac{1}{R_{\text{parallel}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots
  $$

### Time Constants
- RC Circuit:
  $$
  \tau = R C
  $$
- RL Circuit:
  $$
  \tau = \frac{L}{R}
  $$

### Dielectrics
- Effect on Capacitance:
  $$
  C' = \kappa C
  $$
  - $\kappa$: Dielectric constant.

## Question Types

### Capacitor and Resistor Problems
- Analyze charge, voltage, and energy for capacitors.
- Simplify resistor networks and compute voltage drops and currents.

### Power Consumption
- Use $P = IV$, $I^2 R$, or $\frac{V^2}{R}$ depending on available information.

### Kirchhoff’s Laws
- Solve multi-loop circuits for unknown currents and voltages.

### RC and RL Circuits
- Analyze exponential charging/discharging using:
  $$
  V_C(t) = V_{\infty}\left(1 - e^{-t/\tau}\right), \quad I_L(t) = I_{\infty}\left(1 - e^{-t/\tau}\right)
  $$

## Skills

- Series and Parallel Combinations:
  - Simplify complex resistor or capacitor networks systematically.
- Time-Dependent Circuits:
  - Understand transient behaviors in RC and RL circuits.
- Kirchhoff's Laws:
  - Set up consistent equations for voltage and current loops.

## Study Tips

1. Diagram First:
   - Label all circuit elements and directions for currents and voltages.
2. Systematic Approaches:
   - For Kirchhoff’s Laws, use consistent loop directions and distinct node voltages.
3. Unit Conversions:
   - Ensure correct use of $\Omega$, V, A, F, etc.
4. Transient vs. Steady-State:
   - Capacitors act as open circuits, and inductors as short circuits in steady-state DC.

