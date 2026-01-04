# Radiation to Organ Dose Calculator

The Mathematica notebook is a health physics calculator that calculates the Effective Dose for an individual based on preset data of radiation exposure to the lungs, stomach, bladder, thyroid, and whole body.

## Data

| Organ | Radiation Type | Energy | Absorbed Dose |
| :--- | :--- | :--- | :--- |
| Lungs | Alpha (α) | 770 keV | 0.13 cGy |
| Stomach | Beta (β) | 1.1 MeV | 0.24 cGy |
| Bladder | Neutron (n) | 1.1 MeV | 0.15 cGy |
| Thyroid | Gamma (γ) | 662 keV | 0.70 cGy |
| Whole Body | Gamma (γ) | 662 keV | 1.90 cGy |

ICRP Publication 103 standards are implemented to determine the Radiation Weighting Factors ($W_R$) from input energies, and in turn, combining them with the Tissue Weighting Factors ($W_T$) to convert absorbed doses (cGy) into biological equivalent doses in mSv.
