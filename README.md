# Zero-Voltage Switching Evaluation for Dual Active Bridge Converters

This project presents mathematical approaches for accurately evaluating zero-voltage switching (ZVS) in Dual Active Bridge (DAB) converters.

The work focuses on developing both a detailed ZVS evaluator and a computationally reduced evaluator, and validating their predictions against detailed switching simulation.

---

## Problem

Zero-voltage switching is an important operating condition in high-frequency power converters because it can significantly reduce switching losses and improve converter efficiency.

For Dual Active Bridge converters, evaluating ZVS across a large operating and modulation space can become computationally expensive when detailed switching simulations are used repeatedly.

The objective of this work is therefore to develop mathematical ZVS evaluation methods that retain high prediction accuracy while reducing the computational burden associated with detailed switching simulation.

---

## Method

Two mathematical ZVS evaluators were investigated:

### Detailed ZVS Evaluator

A physics-based mathematical model was developed to evaluate the switching transition and determine whether the semiconductor devices achieve ZVS under a given converter operating condition.

### Reduced ZVS Evaluator

A computationally reduced formulation was then developed to simplify the ZVS evaluation while retaining the essential physical behavior required for accurate prediction.

The two approaches allow the trade-off between **physical fidelity, computational complexity, and prediction accuracy** to be investigated.

---

## Validation

Both mathematical evaluators were validated against a detailed switching model implemented in Simulink.

The comparison evaluates whether the proposed models correctly reproduce the ZVS behavior predicted by the switching simulation across the investigated converter operating conditions.

### Validation workflow

**Converter operating point**

↓  

**Detailed mathematical ZVS evaluator**

**Reduced ZVS evaluator**

↓  

**Comparison against switching simulation**

↓  

**Accuracy and computational-performance assessment**

---

## Results

The developed evaluators showed strong agreement with the detailed switching simulation in predicting the ZVS operating region.

The reduced formulation provides a lower-complexity alternative for applications where ZVS must be evaluated repeatedly, such as:

- modulation optimization;
- operating-region analysis;
- lookup-table generation;
- converter design studies;
- control-oriented optimization.

Detailed quantitative results and selected validation figures will be added as the research progresses.

---

## Skills and Tools

`Power Electronics` `Dual Active Bridge` `Zero-Voltage Switching` `MATLAB` `Simulink` `Mathematical Modeling` `Numerical Analysis` `Converter Modeling`

---

## My Contribution

- Developed mathematical models for evaluating ZVS in DAB converters.
- Investigated a reduced-complexity ZVS evaluation approach.
- Implemented the evaluation framework in MATLAB.
- Developed detailed switching simulations for validation.
- Compared the mathematical evaluators against switching-model results.
- Analyzed prediction accuracy and computational trade-offs.

---

## Research Status

**Ongoing / unpublished research**

Source code, detailed mathematical implementation, and unpublished research data are currently kept private.
