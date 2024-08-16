## **Computational Analysis of the Physical Properties of Water-in-Salt Electrolytes**
### Abstract
# README

## Overview

One of the main causes of hazards in battery operation is dendrite growth at the anodes, which can lead to short circuits and battery fires when combined with flammable electrolytes. One potential solution to mitigate fire risks is replacing flammable electrolytes with non-flammable ionic liquids. Unfortunately, the high costs associated with these liquids make commercialization unfeasible. Aqueous electrolytes are a promising alternative as they offer both non-flammability and excellent transport properties.

## Modeling Lithium-ion Water-in-Salt Electrolytes (WISE)

To model Lithium-ion water-in-salt electrolytes (WISE) using classical Molecular Dynamics (MD) simulations, we explore various force fields where atomic polarization is accounted for at two different levels:

1. **Non-polarizable all-atom force field**: Polarization is implicitly included in its Van-der-Waals interaction parameters.
2. **Explicit polarizable force field**: Polarization is modeled via Drude oscillators.

We also investigate combining different polarization levels for salt ions and water:
- When ion polarization is described by the Drude method, water is modeled by either the non-polarizable SPC/E model or the polarizable SWM4-NDP model.

## Objectives

The objective is to maintain simulation stability for diverse force fields and analyze the impact of force fields on electrolyte features. As a first step to reliably study the properties of WISE in Lithium-ion batteries, we have tested and compared various force fields, including:

1. **21 m LiTFSI in H2O**
2. **21 m LiTFSI and 7 m LiOTf in H2O**
3. **12 m (LiTFSI/EMC, H2O)**
4. **3.22 m (LiTFSI/NMA, H2O)**

Through a rigorous comparison of different force fields, we can accurately pinpoint the critical chemical and physical properties of electrolytes that are fundamental to the optimal functioning of Lithium-ion batteries.

## Conclusion

This computational study aims to provide insights into the selection of appropriate force fields for simulating WISE, ultimately guiding the design of safer and more efficient Lithium-ion batteries.
