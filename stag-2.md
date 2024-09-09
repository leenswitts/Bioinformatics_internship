# TCGAplot: an R package for integrative pan-cancer analysis and visualization of TCGA multi-omics data

Authors (@slack): Obibuogu Emmanuel Chidiebere (@Chiddo), Leens Witts (@leens), Faith Oluyinka Ayoade (@FaithAyo1), Maurice Godwin (@Maurice)
(@github): @leenswitts @Maurice31-prog @chidi03 @FaithAyo

## Introduction

Cancer research has advanced with multi-omics data, offering insights into molecular mechanisms like genomics, transcriptomics, and epigenomics. The Cancer Genome Atlas (TCGA) is a major source of comprehensive molecular profiles for various cancers. Existing tools for analyzing TCGA data often lack functionality or flexibility for user-defined analyses (Weinstein et al., 2013). To overcome these issues, TCGAplot, an R package, was developed to enable integrative pan-cancer analysis and visualization of TCGA multi-omics data (Liao & Wang, 2023).

## Overview of TCGAplot

TCGAplot provides researchers with built-in multi-omics data for over 20,000 samples from 33 cancer types, including data on gene expression, tumor mutational burden (TMB), microsatellite instability (MSI), immune cell ratios, promoter methylation, and immune scores. The data are readily accessible through functions within the package, allowing users to extract relevant information for their research (Liao and Wang, 2023).

## Pan-Cancer Analysis

Pan-cancer analysis aims to uncover patterns across multiple cancer types. TCGAplot allows for both paired and unpaired differential gene expression analysis, offering visualizations such as boxplots and heatmaps (Liao and Wang, 2023). The package offers correlation analysis to examine relationships between gene expression, TMB, MSI, and immune markers. Its visualization features, including radar charts and scatter plots, aid in identifying potential cancer treatment and prognosis biomarkers.

## Cancer-Specific Analysis

TCGAplot provides functions for cancer-type-specific analysis, allowing users to group samples by clinical factors such as age, gender, or cancer stage to examine gene expression, immune responses, and survival outcomes (Liao & Wang, 2023). It also enables the identification of differentially expressed genes (DEGs) between high and low expression groups, offering deeper insights into cancer progression.

## Visualization and User-Defined Functions

A major advantage of TCGA plot is its rich set of visualization tools, including survival plots, ROC curves, and forest plots, which allow researchers to present their findings in a clear and interpretable manner (Liao and Wang, 2023). Additionally, TCGA plot enables the extraction of pre-built data, allowing users to create custom analyses tailored to their specific research questions. This flexibility is crucial for researchers needing to extend standard analyses to novel hypotheses or datasets.

## Conclusion

TCGA plot offers a powerful, user-friendly platform for pan-cancer and cancer-specific analysis using multi-omics data from TCGA. With its extensive built-in datasets, flexible extraction options, and robust visualization capabilities, TCGA plot addresses the limitations of previous tools by allowing researchers to conduct integrative and custom analyses (Liao and Wang, 2023). 

## References

Weinstein, J. N., Collisson, E. A., Mills, G. B., Shaw, K. R., Ozenberger, B. A., Ellrott, K., ... & Stuart, J. M. (2013). The cancer genome atlas pan-cancer analysis project. Nature genetics, 45(10), 1113-1120.
Liao, C., & Wang, X. (2023). TCGAplot: an R package for integrative pan-cancer analysis and visualization of TCGA multi-omics data. Bmc Bioinformatics, 24(1), 483.

