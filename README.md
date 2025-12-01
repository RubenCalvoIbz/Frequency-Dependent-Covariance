# Frequency-Dependent Covariance (FDC / FDPCA)

Code accompanying:

> Rubén Calvo, Carles Martorell, Guillermo B. Morales, Serena Di Santo, Miguel A. Muñoz  
> *Frequency-Dependent Covariance Reveals Critical Spatiotemporal Patterns of Synchronized Activity in the Human Brain*,  
> Phys. Rev. Lett. 133, 208401 (2024).  
> doi:10.1103/PhysRevLett.133.208401

This repository provides reference implementations of the **frequency-dependent covariance / principal component analysis (FDC/FDPCA)** framework introduced in the paper, including:

- computation of frequency-dependent covariance matrices from multivariate time series,
- inference of effective coupling and distance to criticality,
- extraction of complex eigenmodes and spatiotemporal waves,

## Repository structure 

- `src/fdc/` – core Python package
- `examples/` – small scripts for toy models / MEG pipelines
- `data/` – synthetic data 

## Installation

Clone this repository:

```bash
git clone https://github.com/RubenCalvoIbz/Frequency-Dependent-Covariance.git
cd Frequency-Dependent-Covariance
