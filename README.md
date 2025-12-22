# *TMEM175*, *SCARB2* and *CTSB* associations with Parkinson's disease risk across populations  

`GP2 ❤️ Open Science 😍`  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15799510.svg)](https://doi.org/10.5281/zenodo.15799510)  
**Last Updated:** November 2025

## Summary

This is the online repository for the manuscript titled **"*TMEM175, SCARB2* and *CTSB* associations with Parkinson's disease risk across populations"**. This study focuses on exploring the role of lysosomal related genes(*TMEM175, SCARB2, CTSB* and *GBA1*) in existing PD/control datasets from GP2 Neurobooster genotyping array.

## Data statement
All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson’s disease, and are available via application on the website (https://amp-pd.org/register-for-amp-pd). For up-to-date information on GP2 data acquisition, access, and policies, visit https://gp2.org/. 

All data was using GP2 release 10 ([10.5281/zenodo.15748014](https://doi.org/10.5281/zenodo.15748014)). Genotyping imputation, quality control, ancestry prediction, and processing were performed using GenoTools (v1.0.0), publicly available on GitHub.

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
 -  The `GP2/` directory includes 3 notebooks on processing and analyzing GP2 Neuobooster array data from release 10.

<pre> THIS_REPO/ 
  ├── LICENSE
  ├── README.md 
  └── analyses/ 
       └── GP2/ 
           ├── 00_TMEM175_ALL_GLM.ipynb 
           ├── 01_SCARB2_ALL_GLM.ipynb 
           ├── 02_CTSB_ALL_GLM.ipynb
           ├── 03_GBA1_exclusion_and_scree_plot.ipynb
           ├── 04_forest_plot_and_multiple_test.ipynb
           └── 05_coloc.ipynb </pre>

## Analysis Notebooks
### Languages: Python, bash, and R
| Directory | Notebooks   | Description | 
|-----------|----------------|--------|
|`GP2/`| `00_TMEM175_ALL_GLM.ipynb`         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of *TMEM175* with GP2 Neurobooster array|
|`GP2/`| `01_SCARB2_ALL_GLM.ipynb`         | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of *SCARB2* with GP2 Neurobooster array|
|`GP2/`| `02_CTSB_ALL_GLM.ipynb`        | Association analysis, GLM analysis, GCTA-COJO analysis, single variant based and gene based analysis of *CTSB* with GP2 Neurobooster array|
|`GP2/`| `03_GBA1_exclusion_and_scree_plot.ipynb`        | Exclude *GBA1* carriers and get a PCA scree plot in EUR ancestry |
|`GP2/`| `04_forest_plot_and_multiple_test.ipynb`        | Multiple test correction and plotting |
|`GP2/`| `05_coloc.ipynb`        | Colocalization analysis with eQTL public dataset |



## Software
| **Software** | **Version(s)** | **Resource URL** | **RRID** | **Notes** |
|--------------|----------------|------------------|----------|-----------|
| ANNOVAR         | 2020-06-08 | http://www.openbioinformatics.org/annovar/ | RRID:SCR_012821 | Used for variant annotation. |
| PLINK  | 1.9 and 2.0    | [http://www.cog-genomics.org/plink/](http://www.cog-genomics.org/plink/) | RRID:SCR_001757 | Used for association analyses. |
| GCTA | 1.94.1  | https://yanglab.westlake.edu.cn/software/gcta/#Overview         |-|Used for conditional analysis.
| RVTests | 2019-02-05  | http://zhanxw.github.io/rvtests/         |RRID:SCR_007639 | Used for burden tests.
| LDpair | Latest  | https://ldlink.nih.gov/?tab=ldpair         |-| Used for estimating linkage disequillibrium. 
| Python Programming Language | 3.10.15  | http://www.python.org/         |RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodel; Used for general data wrangling/plotting/analyses
| R Project for Statistical Computing | 4.3.3  | http://www.r-project.org/        |RRID:SCR_001905| forestplot (3.1.7), coloc(5.2.3); Used for data wrangling and visualization |
