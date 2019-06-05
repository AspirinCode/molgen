# molgen
in-silico generation of molecules using fragments

# algorithm

1. standardize input dataset using standardizer (pip package chemo-standardizer)
2. fragment standardized dataset;
   choose one fragmentation scheme from the litterature
   (rdkit has both BRICS and RECAP)
3. assemble fragments until enough molecules have been generated
4. compute distribution of properties over the generated molecules

# Bibliography
1. Lewell, X. Q., Judd, D. B., Watson, S. P., & Hann, M. M. (1998). Recap retrosynthetic combinatorial analysis procedure: a powerful new technique for identifying privileged molecular fragments with useful applications in combinatorial chemistry. Journal of chemical information and computer sciences, 38(3), 511-522.
2. Degen, J., Wegscheid‐Gerlach, C., Zaliani, A., & Rarey, M. (2008). On the Art of Compiling and Using'Drug‐Like'Chemical Fragment Spaces. ChemMedChem: Chemistry Enabling Drug Discovery, 3(10), 1503-1507.
