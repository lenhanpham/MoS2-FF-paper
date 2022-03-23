# Data used for fitting MoSu-CHARMM force field

This depository contains all crystal structure files (CIF) of several optimized
adsorption configurations used to calculate fitting and validation datasets of
energy which were empplyed to fit and validate the MoSu-CHARMM. All adsortion
energies in these two data sets can be found in the spread sheet (excel file).

Because the level of theory was meteculously benchmarked against
experimental data, the adsorption energy datasets are very accurate and are the
best adsorption energies of several orgarnic compounds on the MoS<sub>2</sub>
surface. The optmized geometrical structures and corresponding energies here can
be used for further purposes such as machine learning and method development.

Please cite this paper "**Pham, L. N.; Walsh, T.** *Predicting Biomolecule Adsorption
on MoS<sub>2</sub> Nanosheets with High Structural Fidelity.* **Chem. Sci.** ***2022***
[doi:10.1039/D1SC06814H](https://doi.org/10.1039/D1SC06814H)" if you are using
this set of data. 

# Usage of MoSu-CHARMM Force Field 

**MoSu-CHARMM** is a high-fidelity force field for simulation interaction
between biomolecules (peptides and proteins) & all possible organic commpounds
and the MoS<sub>2</sub> surface in aqueous media. MoSu-CHARMM can be used for
gas-phase simulation as well. In order to use MoSu-CHARMM in aqueous media, the
TIPS3P water model should be used. Parameters for description of interaction
between water and MoS<sub>2</sub> can be found in another publication "**Pham,
L. N.; Walsh, T. R.** *Force Fields for Water–Surface Interaction: Is
Reproduction of the Experimental Water Contact Angle Enough?* **Chem. Commun.**
***2021***, 57 (27), 3355–3358.
[doi:10.1039/d1cc00426c](https://doi.org/10.1039/D1CC00426C)". All paramters in
the Chem. Sci. paper, togetther with paramters in the Chem. Comm. one, make
MoSu-CHARMM complete. 

## Users need to pay attention to setting paramters such as vdw cutoff and rcoulomb when using MoSu-CHARRM. These paramters are mentioned in two papers above.
