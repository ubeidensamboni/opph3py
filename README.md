# Raw Datas Calculations for OPPh_3py

## Description

This repository contains the output files from quantum chemical calculations performed on the OPPh_3py molecule at the ωB97XD level of theory.

The calculations include:

1. **Single-point energy calculation with NBO analysis**
2. **Nonlinear optical (NLO) property calculation**

All computations were carried out using Density Functional Theory (DFT) with the long-range corrected hybrid functional ωB97XD.

---

## Files Included

### 1. file.log
Output file from the single-point energy calculation including:

- Final electronic energy
- Molecular orbital information
- Natural Bond Orbital (NBO) analysis
- Donor–acceptor interactions
- Charge distribution and orbital occupancies

This file contains the complete raw output generated during the NBO analysis.

---

### 2. nlo.log
Output file containing raw data for nonlinear optical (NLO) properties, including:

- Dipole moment components
- Polarizability tensor elements
- First hyperpolarizability tensor components
- Derived scalar quantities (if present in output)

These values can be used to compute:

- Total dipole moment (μ)
- Mean polarizability (⟨α⟩)
- Total first hyperpolarizability (β_tot)

---

## Level of Theory

All calculations were performed at:

DFT / ωB97XD

(Include basis set here if applicable, e.g., 6-311++G(d,p))

---

## Software

Calculations were performed using:

Gaussian (specify version if known)

Example:
Gaussian 16, Revision C.01

---

## Notes for Reproducibility

- The files provided are raw Gaussian output files.
- All numerical values reported in the manuscript were extracted directly from these outputs.
- NLO properties were obtained from the frequency-dependent output section (if applicable).
- Units follow Gaussian default conventions (atomic units unless otherwise stated).

---

## How to Use the Files

To reproduce results:

1. Open `.log` files using:
   - Gaussian output viewer
   - GaussView
   - Multiwfn
   - Text editor for manual extraction

2. Extract:
   - NBO data from the NBO section in `file.log`
   - NLO tensor components from `nlo.log`

---

## Citation

If using these data, please cite the associated manuscript and the Zenodo DOI of this repository.

---

## Contact

For questions regarding the calculations, please contact the corresponding author.
