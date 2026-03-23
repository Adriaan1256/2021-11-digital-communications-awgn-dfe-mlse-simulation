# Digital Communications AWGN DFE and MLSE Simulation

Course – Practical Assignment  
University of Pretoria  
Completed: November 2021

---

## Project Overview

This project involves the design and implementation of a simulation platform for a digital communication system transmitting data over an additive white Gaussian noise (AWGN) multipath channel.

The simulation evaluates the performance of two equalisation techniques:
- Decision Feedback Equalisation (DFE)
- Maximum Likelihood Sequence Estimation (MLSE)

The system models the effects of intersymbol interference (ISI) caused by multipath propagation using a channel impulse response (CIR). Both static and dynamic CIR scenarios are considered.

The simulation supports multiple modulation schemes:
- BPSK
- 4QAM
- 8PSK

The platform generates and analyses Bit Error Rate (BER) versus Signal-to-Noise Ratio (SNR) for each modulation scheme and equalisation method. Results are averaged over multiple iterations and plotted across a range of SNR values.

👉 [View Full Project Report (PDF)](docs/EDC310_Practical_Assignment_2.pdf)

---

## Objectives

- Design and implement a simulation platform for a communication system over an AWGN multipath channel  
- Investigate the effects of intersymbol interference caused by multipath propagation  
- Implement Decision Feedback Equalisation (DFE) for symbol detection  
- Implement Maximum Likelihood Sequence Estimation (MLSE) using the Viterbi algorithm  
- Simulate both static and dynamic channel impulse responses (CIR)  
- Apply BPSK, 4QAM, and 8PSK modulation schemes  
- Generate BER vs SNR plots for each modulation scheme and equalisation technique  
- Compare the performance of DFE and MLSE under different channel conditions  

---

## Tools & Technologies

- Python  
- NumPy  
- Matplotlib  
- Wichmann-Hill random number generator  
- Marsaglia-Bray Gaussian random number generator  

---

## Notes

This repository contains the academic report for the project. The implementation code is included in the appendix section of the report.
