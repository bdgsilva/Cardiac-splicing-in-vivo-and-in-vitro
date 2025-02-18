# Transcriptomic analysis of cardiac development _in vivo_ and _in vitro_

**This Repository**
This repository contains the R scripts used in this study to perform differential gene expression with DESeq2 and single-cell analysis with Seurat. It also includes the scripts used to process the results of rMATS, MAJIQ, and vast-tools. 

**Single RNA-seq**
Single-cell RNA-seq analysis of cardiomyocytes derived from a female and a male iPSC cell line (iPSC-CMs) (E-MTAB-13850). 

**Bulk RNA-seq**
Differential gene expression analysis of RNA-seq data from 3 iPSC-CMs (E-MTAB-13757], 38 prenatal hearts and 12 postnatal hearts ([E-MTAB-6814](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-6814), [Cardoso-Moreira et al. 2019](https://www.nature.com/articles/s41586-019-1338-5))  

**Dependencies**
**R**: R v4.4.1, knitr 1.48, rmarkdown 2.28, Seurat v.5.1.0, DropletUtils v.1.24.0, DoubletFinder v.2.0.4, tximport v1.32.0, tidyverse 2.0.0, corrplot v0.94, DESeq2 1.44.0, pheatmap 1.0.12, RColorBrewer v.1.1-3, org.Hs.eg.db 3.19.1, pvclust 2.2.0, clusterProfiler v4.12.6 

**Bash**: FastQC v0.12.1, Trimgalore v0.6.10, Salmon v.1.10.2, STAR 2.7.10b, samtools v.1.7, rMATS 4.1.2, MAJIQ v2.5.1, vast-tools v2.5.1, ggashimi v1.1.5, Kallisto BUStools v.0.46.0

**Python**: Python 3.8.17, pandas 1.3.5, Nease 1.2.2
