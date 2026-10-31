# EMMPRIN-assisted glycolysis interferes with myelin phagocytosis and contributes to pathology in a murine model of multiple sclerosis

## Overview

This repository contains the analysis code used in the study:

**EMMPRIN-assisted glycolysis interferes with myelin phagocytosis and contributes to pathology in a murine model of multiple sclerosis (Das et al)**

This study investigates the role of EMMPRIN/BSG in microglia in the context of multiple sclerosis (MS) by leveraging mouse models (experimental autoimmune encephalomyelitis) and human tissues.

This repository contains workflows for analysis of public single-nuclei transcriptome data from healthy controls and individuals with MS.

All analyses were performed using R and Quarto.

---

## Data Availability

Publicly available single-nuclei RNA-seq data were obtained from: https://cells.ucsc.edu/ms

These data were previously published in "Neuronal vulnerability and multilineage diversity in multiple sclerosis" (Schirmer et al.), Nature, 2019,  doi: 10.1038/s41586-019-1404-z

## Running the Analyses

This repository contains all code used to generate the analyses and figures presented in the manuscript.The analyses are provided as a Quarto workflow (EMMPRIN-microglia-MSsinglecell.qmd). The workflow automatically creates the necessary local directory structure for downloaded data, intermediate files, and generated outputs. 

To reproduce the results:

1. Download and open the `.qmd` file.
2. Download dependencies (use package versions specified in publication).
3. Execute all code chunks sequentially.

## Software Requirements

Analyses were performed using:

- R (version v4.5.2)
- Package versions specified in publication methods

## Citation

If you use code from this repository, please cite:

"EMMPRIN-assisted glycolysis interferes with myelin phagocytosis and contributes to pathology in a murine model of multiple sclerosis", Das et al

DOI: TBD

## Contact

Dr. Deepak Kaushik, dkaushik@mun.ca

Kaushik Laboratory

Memorial University of Newfoundland
