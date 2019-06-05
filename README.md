# molgen
in-silico generation of molecules using fragments

# algorithm

1. standardize input dataset using standardizer (pip package chemo-standardizer)
2. fragment standardized dataset
  * choose one fragmentation scheme from the litterature
    (there is one in rdkit, another one I know in open-source)
3. assemble fragments until enough molecules have been generated
4. compute distribution of properties over the generated molecules
