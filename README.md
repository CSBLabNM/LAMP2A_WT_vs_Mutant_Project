# LAMP2A_WT_vs_Mutant_Project
# **Membrane Burial of Juxtamembrane Residues Weakens Oligomeric Interactions Leading to LAMP2A Inactivation**
# Overview
This repository contains molecular dynamics (MD) simulation data for both monomeric and homotrimeric assemblies of human Lysosome-Associated Membrane Protein 2A (LAMP2A). The dataset includes simulations for the wild-type (WT) and an inactive mutant variant within a biologically relevant lysosomal membrane environment. The simulations were conducted for 1000 ns using GROMACS to investigate the structural and dynamic consequences of the mutation.

# **Repository Contents**

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




