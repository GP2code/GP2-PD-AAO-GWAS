# Genetic Modifiers of Age at Onset for Parkinson's Disease in European Populations

`GP2 ❤️ Open Science 😍`

DOI for GitHub pending 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Last Updated:** September 2026

## Summary
This is the online repository for the manuscript titled ***"Genetic Modifiers of Age at Onset for Parkinson's Disease in European Populations"***. This study presents the largest genome-wide association study (GWAS) meta-analysis of Parkinson's disease (PD) age at onset (AAO) in European populations to date, incorporating 50,859 individuals with PD from the Global Parkinson's Genetics Program (GP2), the International Parkinson's Disease Genomics Consortium (IPDGC), the UK Biobank (UKB), the Fox Insight Genetics Study (FIGS), FinnGen, and deCODE Genetics across diverse European ancestries (Finnish, Icelandic, Ashkenazi Jewish, and broadly European).

We identified 5 genome-wide significant loci associated with PD AAO. We replicated the *SNCA* signal, report the first genome-wide significant association at *GBA1* (p.N409S, with an additional independent signal tagging p.E365K), and nominate two novel loci near *HIP1R* and *FSCB*. A significant signal at *APOE* was also observed, but a control GWAS on participant age suggests it likely reflects longevity rather than a PD-specific effect. Finally, a PD polygenic risk score (PRS) built from 157 European risk variants was associated with earlier onset.

Summary statistics will be available on NDKP (https://ndkp.hugeamp.org/) and as a part of the GP2 data. 
## Citation
If you use this repository or find it helpful for your research, please cite the corresponding manuscript:

> Genetic Modifiers of Age at Onset for Parkinson's Disease in European Populations (Global Parkinson's Genetics Program, 2026)
>> Manuscript DOI: coming soon
>> GitHub DOI: 10.5281/zenodo.XXXXXXXX 

### Data Statement
* All GP2 data are hosted in collaboration with the Accelerating Medicines Partnership in Parkinson's Disease (AMP-PD) and are available via application on the website. The GP2 PD case data are available via the GP2 analysis platform (https://gp2.org; Release 11: https://doi.org/10.5281/zenodo.17753486). Tier 1 data can be accessed by completing a form on the AMP-PD website (https://amp-pd.org/register-for-amp-pd); Tier 2 data access requires approval and a Data Use Agreement signed by your institution.
* Genotyping quality control, ancestry prediction, and processing were performed using GenoTools, publicly available on GitHub. Imputation was performed per ancestry using the TOPMed-r3 reference panel.
* Analyses conducted on the UK Biobank were performed on the DNAnexus platform, apply for access here: https://www.ukbiobank.ac.uk/use-our-data/apply-for-access/
* Fox Insight data can be accessed here: https://foxinsight.michaeljfox.org/register
* FinnGen summary statistics were made available through a collaboration, apply for access here: https://www.finngen.fi/en/researchers/accessing
* deCODE summary statistics were made available through a collaboration, more information here: https://www.decode.com/research/

### Helpful Links
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

# Repository Orientation
- The `analyses/` directory includes all analyses discussed in the manuscript


---
### Analysis Notebooks
* Languages: Python, bash, and R

To be added 

---

# Software
|               Software              |                               Resource URL                              |       RRID      |                                               Notes                                               |
|:-----------------------------------:|:----------------------------------------------------------------------:|:---------------:|:-------------------------------------------------------------------------------------------------:|
|     Python Programming Language     |                        http://www.python.org/                         | RRID:SCR_008394 | pandas; numpy; seaborn; matplotlib; statsmodels; used for general data wrangling/plotting/analyses |
| R Project for Statistical Computing |                          http://www.r-project.org/                       | RRID:SCR_001905 |   tidyverse; dplyr; tidyr; ggplot; data.table; used for general data wrangling/plotting/analyses  |
|              GenoTools              |               https://github.com/dvitale199/GenoTools                  |       N/A       |                 used for genotype quality control and ancestry prediction                         |
|                PLINK                |        http://www.nitrc.org/projects/plink          | RRID:SCR_001757 |                   used for GWAS, meta-analysis, and PRS calculation                               |
|               REGENIE               |                   https://github.com/rgcgithub/regenie                  | RRID:SCR_022479 |                            used for FinnGen GWAS                                                  |
|                 KING                |                https://www.kingrelatedness.com/                         | RRID:SCR_009251 |                   used for duplicate/relatedness assessment between IPDGC and GP2                 |
|        TOPMed Imputation Server     |                https://imputation.biodatacatalyst.nhlbi.nih.gov/        |       N/A       |                            used for genotype imputation                                           |
|                 FUMA                |                        https://fuma.ctglab.nl/                          | RRID:SCR_017521 |                   used for locus definition, LD clumping, and annotation                          |
|              GCTA-COJO              |              https://yanglab.westlake.edu.cn/software/gcta/            | RRID:SCR_025348 |                   used for conditional and joint analysis                                         |
|                 LDSC                |                   https://github.com/bulik/ldsc                         | RRID:SCR_022801 |                   used for heritability estimation (implemented via GWASlab)                      |
|               GWASlab               |                  https://github.com/Cloufield/gwaslab                   |       N/A       |                   used for summary statistics handling and LDSC                                   |
|                LDlink               |                     https://ldlink.nih.gov/                              | RRID:SCR_024745 |                   used for LD estimation between GBA1 variants (1000 Genomes)                     |
