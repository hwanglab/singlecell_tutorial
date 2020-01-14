# Introduction to Single-cell Sequencing Data Analysis

## Hwang Lab
### Changjin Hong, Sunho Park, and Tae Hyun Hwang
### Cleveland Clinic Foundation
### January 16, 2020

This tutorial is an introductory single cell sequencing data analysis. We will cover both theory and experiment with public data set. Bring your laptop and there are no prerequisites.

## Index
1. Machine learning ideas in Suerat Package
    1. [Machine learning theory under scRNA data](00_references/SCdata_ML_slides.pdf)
1. Introduction of single cell sequencing
    1. [10x_chromium](01_singlecell_intro/01_intro.Rmd)
1. Cellranger
    1. [bcl to FASTQ](02_cellranger/01_bcl_to_fastq.Rmd)
    1. [FATQ to BAM](02_cellranger/02_fastq_to_bam.Rmd)
1. Experiment Setup
    1. [Rstudio and R libraries](03_experiment_setup/01_r_setup.Rmd)
1. Break (15 min)
1. Single sample analysis
    1. [Normalization](04_single_sample/01_pbmc3k_sctf.Rmd)
    1. [Clustering](04_single_sample/02_pbmc3k_cluster.Rmd)
    1. [Cluster Analysis](04_single_sample/03_pbmc3k_clusterAnalysis.Rmd)
    1. [Cell Identification](04_single_sample/04_pbmc3k_cellid.Rmd)
1. Break (15 min)
1. Comparing two samples
    1. [integration](05_ctrl_vs_expr/01_immune_integration.Rmd)
    1. [conserved markers](05_ctrl_vs_expr/02_immune_cons.Rmd)
    1. [differential gene-expression analysis](05_ctrl_vs_expr/03_immune_dge.Rmd)

### Common Linux Commands:
General syntax:
`<command> -<option> <input1>`

- pwd - Print Working Directory 
- ls - List items in directory
- cd - Change directory
- mkdir - Make Directory
- export - Set environment variable
- echo - Print contents of variable
- tar - Compress or Extract files

---------
Brought to you by the Dr. Hwang lab in Department of Quantitative Health Science, LRI, Cleveland Clinic

#### Clone github codes:
1. Click "Clone or download" and click "Download Zip".
1. Save the zip file into your home directory and unzip.


