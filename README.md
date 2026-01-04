# Radiation to Organ Dose Calculator

The Mathematica notebook is a health physics calculator that calculates the Effective Dose for an individual based on preset data of radiation exposure to the lungs, stomach, bladder, thyroid, and whole body.

## Data

| Organ | Radiation Type | Energy | Absorbed Dose |
| :--- | :--- | :--- | :--- |
| Lungs | Alpha (α) | --- keV | --- cGy |
| Stomach | Beta (β) | --- MeV | --- cGy |
| Bladder | Neutron (n) | --- MeV | --- cGy |
| Thyroid | Gamma (γ) | --- keV | --- cGy |
| Whole Body | Gamma (γ) | --- keV | --- cGy |

ICRP Publication 103 standards are implemented to determine the Radiation Weighting Factors ($W_R$) from input energies, and in turn, combining them with the Tissue Weighting Factors ($W_T$) to convert absorbed doses (cGy) into biological equivalent doses in mSv.
