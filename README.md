# Identification of environmental chemicals targeting miscarriage genes and pathways using the comparative toxicogenomics database
## Citation Information
Harris SM, Jin Y, Loch-Caruso R, Padilla IY, Meeker JD, Bakulski KM. 2020. Identification of environmental chemicals targeting miscarriage genes and pathways using the comparative toxicogenomics database. Environmental Research. PMID: 32143025, PMCID: PMC7103533. DOI: 10.1016/j.envres.2020.109259

This Github repository contains the data management and analytic scripts to produce the following manuscript: [Identification of environmental chemicals targeting miscarriage genes and pathways using the comparative toxicogenomics database](https://pubmed.ncbi.nlm.nih.gov/32143025/)

## Abstract
**Background**: Miscarriage is a prevalent public health issue and many events occur before women are aware of their pregnancy, complicating research design. Thus, risk factors for miscarriage are critically understudied. Our goal was to identify environmental chemicals with a high number of interactions with miscarriage genes, based on known toxicogenomic responses.
**Methods**: We used miscarriage (MeSH: D000022) and chemical gene lists from the Comparative Toxicogenomics Database in human, mouse, and rat. We assessed enrichment for gene ontology biological processes among the miscarriage genes. We prioritized chemicals (n = 25) found at Superfund sites or in the blood or urine pregnant women. For chemical-disease gene sets of sufficient size (n = 13 chemicals, n = 20 comparisons), chi-squared enrichment tests and proportional reporting ratios (PRR) were calculated. We cross-validated enrichment results.
**Results**: Miscarriage was annotated with 121 genes and overrepresented in inflammatory response (q = 0.001), collagen metabolic process (q = 1 × 10-13), cell death (q = 0.02), and vasculature development (q = 0.005) pathways. The number of unique genes annotated to a chemical ranged from 2 (bromacil) to 5607 (atrazine). In humans, all chemicals tested were highly enriched for miscarriage gene overlap (all p < 0.001; parathion PRR = 7, cadmium PRR = 6.5, lead PRR = 3.9, arsenic PRR = 3.5, atrazine PRR = 2.8). In mice, highest enrichment (p < 0.001) was observed for naphthalene (PRR = 16.1), cadmium (PRR = 12.8), arsenic (PRR = 11.6), and carbon tetrachloride (PRR = 7.7). In rats, we observed highest enrichment (p < 0.001) for cadmium (PRR = 8.7), carbon tetrachloride (PRR = 8.3), and dieldrin (PRR = 5.3). Our findings were robust to 1000 permutations each of variable gene set sizes.
**Conclusion**: We observed chemical gene sets (parathion, cadmium, naphthalene, carbon tetrachloride, arsenic, lead, dieldrin, and atrazine) were highly enriched for miscarriage genes. Exposures to chemicals linked to miscarriage, and thus linked to decreased probability of live birth, may limit the inclusion of fetuses susceptible to adverse birth outcomes in epidemiology studies. Our findings have critical public health implications for successful pregnancies and the interpretation of adverse impacts of environmental chemical exposures on pregnancy.

## Funding
This research was supported by the Michigan Center on Lifestage Environmental Exposures and Disease (P30 ES017885). Drs. Harris, Meeker, Padilla, and Loch-Caruso were supported by a research grant from the National Institute of Environmental Health Sciences (NIEHS), National Institutes of Health (P42 ES017198). Dr. Bakulski was supported by research grants from the NIEHS (R01 ES025531; R01 ES025574), National Institute of Aging, NIH (R01 AG055406) and National Institute on Minority Health and Health Disparities, NIH (R01 MD013299). Additional funding for Dr. Harris was provided by the National Center for Advancing Translational Sciences (UL1TR002240). The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIEHS, NIH or the University of Michigan.

## Script Files
This is a [workflowr](https://github.com/jdblischak/workflowr) project

*analysis* folder contains codes producing this project

Pipeline_with_comment_kmb.Rmd: data cleaning, data analysis, producing plots and tables

*docs* folder contains the relative libraryies and html file of code and plots output in the code
