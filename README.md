# LAMP2A_WT_vs_Mutant_Project
# **Mechanistic insights into how juxtamembrane residue modulation leads to LAMP2A inactivation in chaperone-mediated autophagy**
# Overview
This repository contains molecular dynamics (MD) simulation datasets for both monomeric and homotrimeric assemblies of the human Lysosome-Associated Membrane Protein 2A (LAMP2A). The simulations encompass wild-type (WT) systems in which histidine residues at positions 402–404 were modeled in either their neutral (0) or protonated (+1) states, yielding five distinct protonation combinations: 1000, 1100, 1010, 1001, and 1111. In addition, an inactive mutant variant of LAMP2A was simulated within a biologically relevant lysosomal membrane environment.
Each system was subjected to microsecond-scale MD simulations: three replicas for the trimeric assemblies and two replicas for the monomeric systems, with trajectories extending to 1000 ns per replica. All simulations were performed using GROMACS, enabling detailed investigation of the structural and dynamical consequences of the protonation states and the mutation on LAMP2A stability and function.

# **Repository Contents**

# File Description

#  1. PDB Files
Protein Data Bank files that contain the 3D structures of protein and lipids used in the simulations:

- **LAMP2A_WT_monomer_initial_1ns_centered.pdb** (The initial structure of the LAMP2A monomer embedded in a lipid bilayer, used for simulation.)

- **LAMP2A_WT_trimer_initial_1ns_centered.pdb** (The initial structure of the homotrimeric LAMP2A assembly embedded in a lipid bilayer, used for simulation.)

- **LAMP2A_Mutant_monomer_initial_1ns_centered.pdb** (The initial structure of the mutant (<sup>401</sup>AAAA<sup>404</sup>) monomeric LAMP2A embedded in a lipid bilayer, used for simulation.)

- **LAMP2A_Mutant_trimer_initial_1ns_centered.pdb** (The initial structure of the mutant (<sup>401</sup>AAAA<sup>404</sup>) homotrimeric LAMP2A assembly embedded in a lipid bilayer, used for simulation.)

- **LAMP2A_WT_monomer_final_1000ns_centered.pdb** (The final structure of the WT monomeric LAMP2A obtained after 1000 ns simulation.)

- **LAMP2A_WT_trimer_final_1000ns_centered.pdb** (The final structure of the WT homotrimeric LAMP2A obtained after 1000 ns simulation.)

- **LAMP2A_Mutant_monomer_final_1000ns_centered.pdb** (The final structure of the mutant (<sup>401</sup>AAAA<sup>404</sup>) monomeric LAMP2A obtained after 1000 ns simulation.)

- **LAMP2A_Mutant_trimer_final_1000ns_centered.pdb** (The final structure of the mutant (<sup>401</sup>AAAA<sup>404</sup>) homotrimeric LAMP2A obtained after 1000 ns simulation.)

# 2. Trajectory Files (.xtc)
The recorded atomic coordinates over time for analyzing molecular motion and interactions.

- **LAMP2A_WT_monomer_dt50000_centered.xtc** (Processed trajectory data for the WT monomeric LAMP2A, saved at intervals of 50,000 steps.)

- **LAMP2A_WT_trimer_dt50000_centered.xtc** (Processed trajectory data for the WT homotrimeric LAMP2A, saved at intervals of 50,000 steps.)

- **LAMP2A_Mutant_trimer_dt50000_centered.xtc** (Processed trajectory data for the mutant homotrimeric LAMP2A, saved at intervals of 50,000 steps.)

- **LAMP2A_Mutant_monomer_dt50000_centered.xtc** (Processed trajectory data for the mutant monomeric LAMP2A, saved at intervals of 50,000 steps.)

# 3. Analysis Tools

- **GROMACS** (Trajectory and energy analysis)

- **VMD/ChimeraX/PyMOL** (Structural visualization)

- **PyLipID** (Lipid interaction analysis)

- **DSSP** (Secondary structure analysis)

# 4. Objective and Significance
This study aims to elucidate the impact of the (<sup>401</sup>KHHH<sup>404</sup>) → (<sup>401</sup>AAAA<sup>404</sup>) mutation on LAMP2A dynamics, structural stability, and membrane interactions. The findings contribute to understanding the role of LAMP2A in chaperone-mediated autophagy and lysosomal function.




