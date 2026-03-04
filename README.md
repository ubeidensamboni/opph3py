# Raw Datas Calculations for OPPh_3py

## Description

This repository contains the output files from quantum chemical calculations performed on the OPPh_3py molecule at the ωB97XD level of theory.

The calculations include:

1. **Single-point energy calculation with NBO analysis**
2. **Nonlinear optical (NLO) property calculation**

All computations were carried out using Density Functional Theory (DFT) with the long-range corrected hybrid functional ωB97XD.

---

## Files Included

### 1. single point nbo opph3py.log
Output file from the single-point energy calculation including:

- Final electronic energy
- Molecular orbital information
- Natural Bond Orbital (NBO) analysis
- Donor–acceptor interactions
- Charge distribution and orbital occupancies

This file contains the complete raw output generated during the NBO analysis.

---

### 2. nlo wB97XD.log
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

- The files provided are raw Gaussian output files.
- All numerical values reported in the manuscript were extracted directly from these outputs.
- NLO properties were obtained from the frequency-dependent output section.

---

## Citation

If using these data, please cite the associated manuscript and the Zenodo DOI of this repository.

---

## Contact

For questions regarding the calculations, please contact the corresponding author.
