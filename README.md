# ANI and SNP distance matrices

![Example Plot](figures/Ecoli_example_ANI_matrix.png)

## Quick start

Here is my [code for producing ANI and SNP distance matrices](https://rngoodman.github.io/ANI-and-SNP-distances/ANI_and_SNP_distance_matrices.html) for *n* genomes. 

## About 

This tutorial will take *n* genome sequences and run algorithms to determine average nucleotide idenitities (ANI) and core genome single nucleotide polymorphisms (SNPs), visualising the distances as heatmaps in python.

This workflow uses [fastANI](https://github.com/ParBLiSS/FastANI?tab=readme-ov-file) for ANI, [snippy](https://github.com/tseemann/snippy) and [snp-dists](https://github.com/tseemann/snp-dists) for SNP distances, and seaborn and matplotlib in python to visualise the distances as heatmaps. For any analysis in bash it uses the conda package manager so make sure you have that installed. 



