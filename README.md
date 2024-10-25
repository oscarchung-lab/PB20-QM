# PB20-QM
Our drug/inhibitor molecules downloaded from PDBbind v2020 dataset were used to set up a benchmark dataset (denoted as PB-20-QM), which contains 12,963 drug/inhibitor molecules after removing metal-containing systems. The protonation states of all these molecules remain preserved as those in the PDBbind v2020 dataset, except for minor corrections (to fix very poor or wrong positions of H atoms based on their corresponding PDB structures) to some molecules. Geometry optimization for all molecules in this PB-20-QM dataset in gas phase were conducted by the above-mentioned DFT (wB97X-D/6-31G(d)) and GFN2-xTB methods.

# two smaller sub-datasets
## PB20-QM-8k (8776 molecules containing, C, H, O, N, F, S, and/or Cl elements)
Geometry optimization for all molecules in this PB20-QM-8k dataset were conducted by the above-mentioned DFT (wB97X-D/6-31G(d)), GFN2-xTB and ANI-2x methods

## PB20-QM-3k (3125 molecules mainly containing, C, H, O, and/or N elements, 15 molecules containing F, Cl and/or S elements, 16 molecules containing B, P, Se, Br and/or I elements)
Geometry optimization for all molecules in this PB20-QM-3k dataset were performed by the above-mentioned DFT (wB97X-D/6-31G(d)), GFN2-xTB, AIQM1, and ANI-2x methods.


## Citation
YAN, Z. Y., Wei, D. C., Li, X., and Chung, L. W. Accelerating Reliable Multiscale Quantum Refinement of Protein–Drug Systems Enabled by Machine Learning. *Nat. Commun.* **2024**, 15, 4181. [DOI: 10.1038/s41467-024-48453-4](https://www.nature.com/articles/s41467-024-48453-4) 
