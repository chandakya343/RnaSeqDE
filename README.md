# RNA-Seq Data: Differential Expression Analysis

## Introduction
This project involves the differential expression analysis of RNA-seq data using the DESeq2 package in R. The analysis aims to identify significant changes in gene expression associated with specific conditions, such as diseases.

## Installation
To run this project, R must be installed along with the following R packages:
- DESeq2
- RColorBrewer
- pheatmap
- tidyverse

You can install these packages using the following commands in R:
```R
install.packages("BiocManager")
BiocManager::install("DESeq2")
install.packages(c("RColorBrewer", "pheatmap", "tidyverse"))
