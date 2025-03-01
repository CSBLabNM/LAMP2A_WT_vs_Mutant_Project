# LAMP2A_WT_vs_Mutant_Project
# **Membrane Burial of Juxtamembrane Residues Weakens Oligomeric Interactions Leading to LAMP2A Inactivation**
# Overview
This repository contains molecular dynamics (MD) simulation data for both monomeric and homotrimeric assemblies of human Lysosome-Associated Membrane Protein 2A (LAMP2A). The dataset includes simulations for the wild-type (WT) and an inactive mutant variant within a biologically relevant lysosomal membrane environment. The simulations were conducted for 1000 ns using GROMACS to investigate the structural and dynamic consequences of the mutation.

# **Repository Contents**

#  1. PDB Files
Protein Data Bank files that contain the 3D structures of protein and lipids used in the simulations:

- **LAMP2A_WT_monomer_initial_1ns_centered.pdb**
-
- _Description_: The initial structure of the LAMP2A monomer embedded in a lipid bilayer, centered for simulation.

_**LAMP2A_WT_trimer_initial_1ns_centered.pdb**
Description: The initial structure of the homotrimeric LAMP2A assembly, centered in the lipid bilayer.

_**LAMP2A_AAAA_monomer_initial_1ns_centered.pdb**
Description: The initial structure of the mutant (401AAAA404) monomeric LAMP2A, centered in the lipid bilayer.

_**LAMP2A_AAAA_trimer_initial_1ns_centered.pdb**
Description: The initial structure of the mutant homotrimeric LAMP2A assembly, centered in the lipid bilayer.

_**LAMP2A_WT_monomer_final_1000ns_centered.pdb**
Description: The final structure of the WT monomeric LAMP2A after 1000 ns of simulation, centered in the lipid bilayer.

_**LAMP2A_WT_trimer_final_1000ns_centered.pdb**
Description: The final structure of the WT homotrimeric LAMP2A after 1000 ns of simulation, centered in the lipid bilayer.

_**LAMP2A_Mutant_monomer_final_1000ns_centered.pdb**
Description: The final structure of the mutant monomeric LAMP2A after 1000 ns of simulation, centered in the lipid bilayer.

_**LAMP2A_Mutant_trimer_final_1000ns_centered.pdb**
Description: The final structure of the mutant homotrimeric LAMP2A after 1000 ns of simulation, centered in the lipid bilayer.


Overview

This repository contains molecular dynamics (MD) simulation data for both monomeric and homotrimeric assemblies of human Lysosome-Associated Membrane Protein 2A (LAMP-2A). The dataset includes simulations for the wild-type (WT) and an inactive mutant variant within a biologically relevant lysosomal membrane environment. The simulations were conducted for 1000 ns using GROMACS to investigate the structural and dynamic consequences of the mutation.

Repository Contents

1. PDB Files

These Protein Data Bank (PDB) files provide the initial three-dimensional structures used in the simulations:

2. Simulation Files

GROMACS Input Files (.mdp, .top, .itp, .gro)These files define the force field parameters, system topology, and initial configurations used for the MD simulations.

Trajectory Files (.xtc, .trr)The recorded atomic coordinates over time for analyzing molecular motion and interactions.

LAMP2A_Mutant_trimer_dt50000_centered.xtcDescription: Processed trajectory data for the mutant homotrimeric LAMP-2A, saved at intervals of 50,000 steps, centered in the lipid bilayer.

LAMP2A_Mutant_monomer_dt50000_centered.xtcDescription: Processed trajectory data for the mutant monomeric LAMP-2A, saved at intervals of 50,000 steps, centered in the lipid bilayer.

LAMP2A_WT_trimer_dt50000_centered.xtcDescription: Processed trajectory data for the WT homotrimeric LAMP-2A, saved at intervals of 50,000 steps, centered in the lipid bilayer.

LAMP2A_WT_monomer_dt50000_centered.xtcDescription: Processed trajectory data for the WT monomeric LAMP-2A, saved at intervals of 50,000 steps, centered in the lipid bilayer.

Energy Files (.edr)Energy profile data obtained from simulations, useful for assessing system stability.

3. Analysis Data

This section contains post-simulation analyses for structural and dynamic characterization:

RMSD and RMSF DataRoot Mean Square Deviation (RMSD) and Root Mean Square Fluctuation (RMSF) analyses to assess structural stability and flexibility.

Protein-Lipid InteractionsQuantitative analysis of protein-lipid interactions to evaluate binding site stability.

Secondary Structure AnalysisStructural changes assessed using DSSP to compare WT and mutant behavior over the simulation timescale.

Methodology

Simulation Setup

Force Field: CHARMM36m

Water Model: TIP3P

Lipid Bilayer: Heterogeneous lysosomal membrane composition

Equilibration: NVT and NPT ensembles

Production Run: 1000 ns with a 2 fs time step

Analysis Tools

GROMACS 2023 (Trajectory and energy analysis)

PyMOL/ChimeraX (Structural visualization)

PyLipID (Lipid interaction analysis)

DSSP (Secondary structure analysis)

Objective and Significance

This study aims to elucidate the impact of the 401KHHH404 → 401AAAA404 mutation on LAMP-2A dynamics, structural stability, and membrane interactions. The findings contribute to understanding the role of LAMP-2A in chaperone-mediated autophagy and lysosomal function.




