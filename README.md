# TMEM175, SCARB2 and CTSB associations with Parkinson's disease risk across populations

`GP2 ❤️ Open Science 😍`

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15799510.svg)](https://doi.org/10.5281/zenodo.15799510) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

**Last Updated:** June 2025

## Summary

This is the online repository for the manuscript titled **"*TMEM175, SCARB2* and *CTSB* associations with Parkinson's disease risk across populations"**. This study focuses on exploring the role of lysosomal related genes(*TMEM175, SCARB2, CTSB* and *GBA1*) in existing PD/control datasets from the AMP-PD and GP2 Neurobooster genotyping array.

## Data statement
All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. 

All data was using GP2 release 8 ([10.5281/zenodo.13755496](https://doi.org/10.5281/zenodo.13755496)) and AMP-PD release 4 ([10.5281/zenodo.13830696](https://doi.org/10.5281/zenodo.13830696)). Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub.

### Helpful Links

- [GP2 Website](https://gp2.org/)
  - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
  - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Citation
*(pending publication)*

## Tables
*(pending publication)*

## Figures
*(pending publication)*

## Repository Orientation
- The `analyses/` directory includes all analyses discussed in the manuscript.
 -  The `GP2/` directory includes 3 notebooks on processing and analyzing GP2 Neuobooster array data from release 8.
 -  The `AMP-PD/` directory includes 1 notebook on processing and analyzing whole genome sequencing data from release 4.

<pre> THIS_REPO/ 
  ├── LICENSE
  ├── README.md 
  └── analyses/ 
       ├── AMP-PD/ 
       │     └── 00_GBA1_AMPPD.ipynb 
       └── GP2/ 
           ├── 00_TMEM175_ALL_GLM.ipynb 
           ├── 01_SCARB2_ALL_GLM.ipynb 
           └── 02_CTSB_ALL_GLM.ipynb </pre>

## Analysis Notebooks
### Languages: Python, bash, and R
| Directory | Notebooks   | Description | 
|-----------|----------------|--------|
|`AMP-PD/`| `00_GBA1_AMPPD.ipynb`         | Single variant based and gene based analysis of GBA1 with AMP-PD|
|`GP2/`| `00_TMEM175_ALL_GLM.ipynb`         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of TMEM175 with GP2 Neurobooster array|
|`GP2/`| `01_SCARB2_ALL_GLM.ipynb`         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of SCARB2 with GP2 Neurobooster array|
|`GP2/`| `02_CTSB_ALL_GLM.ipynb`        | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of CTSB with GP2 Neurobooster array|



## Software
| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
| ANNOVAR         | 2020-06-08 | http://www.openbioinformatics.org/annovar/ | RRID:SCR_012821 | Used for variant annotation. |
| PLINK  | 1.9 and 2.0    | [http://www.cog-genomics.org/plink/](http://www.cog-genomics.org/plink/) | RRID:SCR_001757 | Used for association analyses. |
| GCTA | 1.94.1  | https://yanglab.westlake.edu.cn/software/gcta/#Overview         |-|Used for conditional analysis.
| RVTests | 2019-02-05  | http://zhanxw.github.io/rvtests/         |RRID:SCR_007639 | Used for burden tests.
| LDpair | Latest  | https://ldlink.nih.gov/?tab=ldpair         |-| Used for estimating linkage disequillibrium. 
| Python Programming Language | 3.10.15  | http://www.python.org/         |RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodel; Used for general data wrangling/plotting/analyses
| R Project for Statistical Computing | 4.3.3  | http://www.r-project.org/        |RRID:SCR_001905|tidyverse; dplyr; tidyr; ggplot; data.table; Used for general data wrangling/plotting/analyses
