# About

Code and data to reproduce figures in the FunGen-xQTL phase 1 manuscript.

## FunGen-xQTL Overview

This project focuses on functional genomics and expression quantitative trait loci (xQTL) analysis. The xQTL approach integrates multi-omics data to understand regulatory architecture and genetic influences on molecular phenotypes.

For a list of data and resources from our project please check out https://statfungen.github.io/xqtl-resources/#fungen-xqtl

## Repository Structure

This repository contains the codes and data used to generate all figures from our manuscript, available at: https://github.com/StatFunGen/xqtl-paper

The repository is organized as follows:

### Main Text Structure
```
main_text/
├── 1_project_overview/
│   ├── index.md (FunGen-xQTL atlas and companion projects)
│   └── figure_data/README.md (Data for figures)
├── 2_single_context_cis/
│   ├── index.md (Single context cis-xQTL fine-mapping)
│   └── figure_data/README.md (Data for figures)
├── 3_single_context_multigene_trans/
│   ├── index.md (Multi-gene and trans-xQTL fine-mapping)
│   └── figure_data/README.md (Data for figures)
├── 4_multi_context/
│   ├── index.md (Propagation of multi-context xQTL effects)
│   └── figure_data/README.md (Data for figures)
├── 5_AD_xQTL_integration/
│   ├── index.md (Alzheimer's disease loci integration)
│   ├── Figure_5a_AD_GWAS_loci_harmonized.ipynb
│   ├── Figure_5b_AD_GWAS_loci_properties.ipynb
│   ├── Figure_5c_AD_loci_xQTL_annotated.ipynb
│   └── figure_data/README.md (Data for figures)
└── 6_AD_xQTL_genes/
    ├── index.md (Insights into AD risk genes)
    └── figure_data/README.md (Data for figures)
```

### Additional Content
- **supplementary_tables/**: Supplementary data tables
- **website/**: Configuration files for the interactive Jupyter Book website
- **references.bib**: Bibliography file for citations
- **setting_up.md**: Setup instructions for the Jupyter Book environment

Each `figure_data` folder contains RDS format data files with the minimum information necessary to reproduce plot figures, allowing users to check numerical values.

## Website

https://statfungen.github.io/xqtl-paper 

To navigate this resource, use the table of contents in the left sidebar of the website. Each notebooks allow you to:

1. View the code used to generate analyses
2. Examine data associated with the figures
3. Reproduce visualizations

For detailed setup instructions and environment configuration to generate the website, see our [Website Setup Guide](setting_up.md).

## Computational Requirements

The analyses in this repository are performed using:
- Python 3.9 or higher
- R version 4.1 or higher
- Key packages: jupyter-book, ggplot2
## Citation

If you use resources from this repository in your research, please cite our manuscript (citation details will be added upon publication).
