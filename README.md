# Paper: Nonlinear Eddy Current Technique for Characterizing Case Hardening Profiles

## Overview

This repository provides an overview of the paper nonlinear eddy current technique for assessing case hardening profiles. The method uses a custom electromagnetic excitation-sensor array to measure nonlinear responses at multiple frequencies, enabling nondestructive characterization of case depth profiles.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)
- [References](#references)

## Introduction

Industrial components, such as automotive bearing assemblies, are often case-hardened for durability. Traditional case-depth evaluation methods are destructive and time-consuming. This project introduces a novel nonlinear eddy current technique for nondestructive testing (NDT) by leveraging differences in magnetic properties between case-hardened and untreated regions.

“Nonlinear Eddy Current Technique for Characterizing Case Hardening Profiles”
Published in IEEE Transactions on Magnetics, VOL. 46, NO. 6, JUNE 2010.

## Methodology

The system excites the bearing core with a strong sinusoidal magnetic field, causing nonlinear magnetization responses. Sinusoidal excitations at different frequencies allow comparison between reference and test components. An array of excitation and detection coils ensures proper field penetration, and harmonic ratios extracted from the frequency spectrum are analyzed using artificial neural networks and the ID3 algorithm.

### Machine Learning Focus:
- Applied artificial neural networks and the ID3 algorithm for classification with high accuracy.
- Designed a custom excitation-sensor array for ML model training and validation.
- Used a multilayer perceptron model with backpropagation for optimal classification.
- Employed decision tree techniques to enhance classification reliability.
- Demonstrated ML effectiveness in industrial nondestructive evaluation.

## Results
The system was tested on bearing assemblies with known case depth profiles. The neural network achieved an accuracy of **95.77%**, while the ID3 algorithm achieved **95.65%**.

## References
- S. C. Chan, R. Grimberg, J. A. Hejase, et al., "Nonlinear Eddy Current Technique for Characterizing Case Hardening Profiles," *IEEE Transactions on Magnetics*, vol. 46, no. 6, pp. 1821-1824, 2010.

