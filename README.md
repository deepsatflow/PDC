# Adaptyv Bio: Protein Design Competition
Note: It is about competition, and is not affiliated with the company

Problem Statement:
https://design.adaptyvbio.com/
Protein Design Tools: 
https://design.adaptyvbio.com/tools

About EGFR:
Epidermal Growth Factor Receptor (EGFR) is a transmembrane protein that plays a critical role in cell growth, differentiation, and survival. It is frequently overexpressed or mutated in various cancers, including non-small cell lung cancer, colorectal cancer, and head and neck cancer. This makes EGFR a crucial target for cancer therapies such as Cetuximab, an antibody with more than 1B USD in annual revenue. (Taken from Adaptyv Bio page)

#### Submission process

Every protein designer can submit up to 10 designs.

Designs must adhere to the following criteria:

- Only natural amino acids
- Max 200 amino acids in length
- Single chain
- At least 10 amino acid edit distances from known binders

#### Evaluation criteria

Designs will be ranked based on PAE_interaction with AF2 as described here.
The top 100 designs will be selected for experimental testing.
Additional designs will be chosen for their novelty, creativity in the design process, or other interesting factors.

#### Lab evaluation

Selected designs will be tested in our Affinity Characterization workflow which includes protein expression and a high-quality kinetics assay to determine the binding affinity of the protein to the target.

You can find more information in our RFdiffusion case study: https://www.adaptyvbio.com/blog/rfdiff_il7ra


## References

PDB Protein link:
https://www.rcsb.org/sequence/6aru

RFDiffusion:
https://www.bakerlab.org/2023/07/11/diffusion-model-for-protein-design/

PyRosetta:
https://www.pyrosetta.org/home

Paper link:
https://www.nature.com/articles/s41586-023-06415-8

ColabDesign:
https://github.com/sokrypton/ColabDesign

ColabFold: 
https://github.com/sokrypton/ColabFold

Binder design verification:
https://github.com/nrbennet/dl_binder_design

paper link: https://www.nature.com/articles/s41467-023-38328-5

Peptide Binders With RFdiffusion:
https://www.youtube.com/watch?v=nqzr9rNHlxA

Faster AlphaFold protein structure predictions using ColabFold:
https://www.youtube.com/watch?v=gIbCAcMDM7E&t=2s

Convert PDB to FASTA:
https://zhanggroup.org/pdb2fasta/pdb2fasta.cgi

About plddt:
https://www.ebi.ac.uk/training/online/courses/alphafold/inputs-and-outputs/evaluating-alphafolds-predicted-structures-using-confidence-scores/plddt-understanding-local-confidence/

How to design a binder:
https://github.com/RosettaCommons/RFdiffusion#binder-design

Drug:
https://go.drugbank.com/drugs/DB00002

Protein Motifs:
https://bio.libretexts.org/Bookshelves/Cell_and_Molecular_Biology/Book%3A_Basic_Cell_and_Molecular_Biology_(Bergtrom)/03%3A_Details_of_Protein_Structure/3.06%3A_Protein_Domains_Motifs_and_Folds_in_Protein_Structure#:~:text=Protein%20motifs%20are%20small%20regions,unique%20chemical%20or%20biological%20function.
