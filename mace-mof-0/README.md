This repository contains the MACE-MP-MOF0 models and the data generated in the paper "Machine Learned Potential for High Throughput Phonon Calculations of Metal--organic Frameworks" (https://arxiv.org/abs/2412.02877)

The v1 and v2 folders contain the two versions of the model reported in the paper. They can be used direcly in ASE, they are compatible with mace 0.3.8 but we suggest using 0.3.9 or newer. The DFT dataset generated in this work (split into train, test and validation sets for the model) is provided in the v2 folder.  

The "127 Curated Dataset.zip" folder contains the the input cifs for the curated dataset in this work.

The "curated_test.zip" contains the 70 MOFs that were sampled from QMOF to test the out-of-sample predition of the model (Table 4 of the paper)

The "BulkModulus_data.zip" folder has the bulk modulus data used to generate Figures 6 a) and b) of the paper.

"NegativeThermalExpansion.csv" contains the coefficent of thermal expansion generated for MOF-5 and UiO-66 over a wide range of temperature.

"optimized_structures.zip" has the geometry optimized structures with all the methods reported in Figure 3 of the paper.

The folder "phonons" has all the data for DOS, Band structures and other thermal properties for the investiagted systems in the paper.
