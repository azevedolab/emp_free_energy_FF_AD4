# emp_free_energy_FF_AD4

Empirical Free Energy Force Field for AutoDock 4

Overview

AutoDock 4 estimates free energy of binding for a receptor-ligand complex using a semi-empirical free energy force field. This force field has been calibrated against a dataset composed of crystallographic structures for which ligand-binding affinity data is known (Morris et al., 2009). The present Python code calculates the van der Waals, intermolecular hydrogen bond, electrostatic interaction, and desolvation potentials based on the atomic coordinates of the ligand and the receptor. This program reads atomic coordinates in the PDBQT format and prints the potential energy terms. It is not calibrated for a specific dataset, so it might be used to develop targeted-scoring functions, which may be used to explore the scoring function space (Heck et al. 2017). The zipped folder has the atomic coordinates for both, receptor (receptor.pdbqt) and ligand (lig.pdbqt) structures. I intend to use this code to develop a new tool in the SAnDReS program (Xavier et al., 2016)( https://github.com/azevedolab/sandres) to generate targeted-scoring functions.


References

Heck GS, Pintro VO, Pereira RR, de Ávila MB, Levin NMB, de Azevedo WF. Supervised Machine Learning Methods Applied to Predict Ligand-Binding Affinity. Curr Med Chem. 2017; 24(23): 2459–2470. 

Morris GM, Huey R, Lindstrom W, Sanner, MF, Belew RK, Goodsell DS, Olson AJ. Autodock4 and AutoDockTools4: automated docking with selective receptor flexibility. J Comput Chem 2009 30: 2785–2791.

Xavier MM, Heck GS, de Avila MB, Levin NM, Pintro VO, Carvalho NL, Azevedo WF Jr. SAnDReS a Computational Tool for Statistical Analysis of Docking Results and Development of Scoring Functions. Comb Chem High Throughput Screen. 2016; 19(10): 801–812.
