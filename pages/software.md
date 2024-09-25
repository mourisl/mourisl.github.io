---
layout: default
title: Software
subtitle: Softwares in Song Lab
permalink: /software/
---
# Software

### Repositories
- [**GitHub**](https://github.com/mourisl) &nbsp;

### Immunology
- [**TRUST4**](https://github.com/liulab-dfci/TRUST4): TCR/BCR assembler for RNA-seq data. TRUST4 can be applied on either bulk or single-cell RNA-seq data. In addition to report CDR3s, TRUST4 also assembles full-length TCRs/BCRs. 
[![](https://img.shields.io/static/v1?label=AIRR-C%20sw-tools%20v1&message=compliant&color=008AFF&labelColor=000000&style=plastic)](https://docs.airr-community.org/en/stable/swtools/airr_swtools_standard.html)
[![GitHub Repo stars](https://img.shields.io/github/stars/liulab-dfci/TRUST4)](https://github.com/liulab-dfci/TRUST4)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/trust4/badges/downloads.svg)](https://anaconda.org/bioconda/trust4) 
- [**T1K**](https://github.com/mourisl/T1K): Genotyper for highly polymorphic genes including KIR and HLA. T1K is verstile and works with RNA-seq, WGS and WES data. T1K also identifies novel SNPs and is compatible with single-cell RNA-seq data. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/T1K)](https://github.com/mourisl/T1K)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/t1k/badges/downloads.svg)](https://anaconda.org/bioconda/t1k)

### Microbiome
- [**Centrifuger**](https://github.com/mourisl/centrifuger): Fast and memory-efficient classifier for metagenomics sequences using a lossless compressed FM-index with run-block compressed BWT. It can assign the taxonomy IDs to each sequencing read by comparing it against a database containing 34,190 prokaryotic genomes with 140 Gbp sequences using about 43 Gb memory. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/centrifuger)](https://github.com/mourisl/centrifuger)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/centrifuger/badges/downloads.svg)](https://anaconda.org/bioconda/centrifuger) 
- [**Centrifuge**](https://github.com/DaehwanKimLab/centrifuge): Fast and memory-efficient classifier for metagenomics sequences using an FM-index. It requires only 4.2 Gb memory for a database containing ~4300 prokaryotic genomes using lossy representations. 
[![GitHub Repo stars](https://img.shields.io/github/stars/DaehwanKimLab/centrifuge)](https://github.com/DaehwanKimLab/centrifuge)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/centrifuge/badges/downloads.svg)](https://anaconda.org/bioconda/centrifuge)

### RNA-seq 
- [**CLASS/CLASS2**](https://github.com/mourisl/CLASS): Efficient and accurate transcript assemblers for RNA-seq data that detect more fine-grained alternative splice variants. The programs combine linear programming algorithms to detect exons from read coverage levels, with splice graph representations of genes and their splice variants, and memory efficient optimization algorithms for transcript selection. \[Also on [SourceForge](https://sourceforge.net/projects/splicebox/)\]
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/CLASS)](https://github.com/mourisl/CLASS)
- [**PsiCLASS**](https://github.com/splicebox/PsiCLASS): Simultaneous multi-sample transcript assembler for RNA-seq data. It builds a global data structure representing the structure of the transcripts, from which each sample generates its expressed transcripts. The global information allows accurate sample-wise assemblies and final meta-assembly. 
[![GitHub Repo stars](https://img.shields.io/github/stars/splicebox/PsiCLASS)](https://github.com/splicebox/PsiCLASS)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/psiclass/badges/downloads.svg)](https://anaconda.org/bioconda/psiclass)
- [**Rcorrector**](https://github.com/mourisl/Rcorrector): Efficient and accurate k-mer-based error correction software for Illumina RNA-seq reads. It can also be applied to data sets where the read coverage is non-uniform, such as single-cell sequencing. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/rcorrector)](https://github.com/mourisl/rcorrector)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/rcorrector/badges/downloads.svg)](https://anaconda.org/bioconda/rcorrector) 
- [**Rascaf**](https://github.com/mourisl/Rascaf): Scaffolding with RNA-seq read alignment. It uses information from paired-end and split reads to improve the completeness and contiguity of a draft genome assembly, particularly in the gene regions. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/rascaf)](https://github.com/mourisl/rascaf)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/rascaf/badges/downloads.svg)](https://anaconda.org/bioconda/rascaf) 

### Next-generation sequencing
- [**Chromap**](https://github.com/haowenz/chromap): Ultrafast alignment and preprocessing for chromatin profiling sequencing data, including ChIP-seq, ATAC-seq and Hi-C. It supports both bulk and single-cell platforms, and is more than 10 times faster than traditional workflows without sacrificing alignment accuracy. 
[![GitHub Repo stars](https://img.shields.io/github/stars/haowenz/chromap)](https://github.com/haowenz/chromap)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/chromap/badges/downloads.svg)](https://anaconda.org/bioconda/chromap)
- [**Lighter**](https://github.com/mourisl/Lighter): Fast and memory-efficient k-mer-based software to correct the sequencing errors from whole genome sequencing data without counting. It samples the k-mers in the data set and uses two memory-efficient Bloom filters to obtain solid k-mers. 
[![GitHub Repo stars](https://img.shields.io/github/stars/mourisl/lighter)](https://github.com/mourisl/Lighter)
[![Anaconda-Server Badge](https://anaconda.org/bioconda/lighter/badges/downloads.svg)](https://anaconda.org/bioconda/lighter)

### Figure plotting
##### Python libraries to help with plotting figures
- [**MSAplot**](https://github.com/mourisl/msaplot): visualize multiple sequence alignment 
- [**pvalannot**](https://github.com/mourisl/pvalannot): add p-value annotation to box plots generated by Seaborn.
- [**heatmapannot**](https://github.com/mourisl/heatmapannot): add color annotation in the axes to heatmap or dot plot generated by Seaborn.
