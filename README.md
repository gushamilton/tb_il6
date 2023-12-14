# TB and IL-6

This repository contains harmonised summary statistics for the analyses performed in: 
https://www.medrxiv.org/content/10.1101/2023.02.07.23285472v1

Altered IL-6 signalling and risk of tuberculosis disease: a meta-analysis and Mendelian randomisation study

There are three files:
The harmonised_il6r_plasma_proteins.tsv file includes harmonised effects for each SNP on the exposure (IL6R plasma protein) and the outcome (each TB GWAS).
The harmonised_CRP.tsv include the same information for the analysis on CRP.
names_list.csv includes some useful demographic/study information to merge.

The analyses in this paper should be able to be performed simply by loading the data into R, and using the TSMR package (https://mrcieu.github.io/TwoSampleMR/) and e.g. filtering to include the appropriate exposure-outcome ancestry analysis.

For any problems, email fergus.hamilton@bristol.ac.uk
