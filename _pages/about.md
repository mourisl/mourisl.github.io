---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! My name is Li Song, a research fellow in [Shirley Liu](https://liulab-dfci.github.io/)'s lab at Department of Data Science in Dana-Farber Cancer Insitute. My research interest is to design algorithms and developing methods to analyze sequencing data. I obtained my Ph.D degree in Computer Science from Johns Hopkins University. 

Projects
======
**TRUST4**: TCR/BCR assembler for RNA-seq data. TRUST4 can be applied on either bulk or single-cell RNA-seq data. In addition to report CDR3s, TRUST4 also assembles full-length TCRs/BCRs. \[[Github](https://github.com/liulab-dfci/TRUST4)\]

**CLASS/CLASS2**: Efficient and accurate transcript assemblers for RNA-seq data that detect more fine-grained alternative splice variants. The programs combine linear programming algorithms to detect exons from read coverage levels, with splice graph representations of genes and their splice variants, and memory efficient optimization algorithms for transcript selection. \[[SourceForge](https://sourceforge.net/projects/splicebox/)\]\[[Github](https://github.com/mourisl/CLASS)\]

**PsiCLASS**: Simultaneous multi-sample transcript assembler for RNA-seq data. It builds a global data structure representing the structure of the transcripts, from which each sample generates its expressed transcripts. The global information allows accurate sample-wise assemblies and final meta-assembly. \[[Github](https://github.com/splicebox/PsiCLASS)\]

**Lighter**: Fast and memory-efficient k-mer-based software to correct the sequencing errors from whole genome sequencing data without counting. It samples the k-mers in the data set and uses two memory-efficient Bloom filters to obtain solid k-mers. \[[Github](https://github.com/mourisl/Lighter)\]

**Rcorrector**: Efficient and accurate k-mer-based error correction software for Illumina RNA-seq reads. It can also be applied to data sets where the read coverage is non-uniform, such as single-cell sequencing. \[[Github](https://github.com/mourisl/Rcorrector)\]

**Rascaf**: Scaffolding with RNA-seq read alignment. It uses information from paired-end and split reads to improve the completeness and contiguity of a draft genome assembly, particularly in the gene regions. \[[Github](https://github.com/mourisl/Rascaf)\]

**Centrifuge**: Fast and memory-efficient classifier for metagenomics sequences using an FM-index. It requires only 4.2 Gb memory for a database containing ~4300 prokaryotic genomes. \[[Github](https://github.com/DaehwanKimLab/centrifuge)\]

**Chromap**: Ultrafast alignment and preprocessing for chromatin profiling sequencing data, including ChIP-seq, ATAC-seq and Hi-C. It supports both bulk and single-cell platforms, and is more than 10 times faster than traditional workflows without sacrificing alignment accuracy. \[[Github](https://github.com/haowenz/chromap)\]

Publications
======
**Song, L**,  Cohen, D, Ouyang, Z, Cao, Y, Hu, X, and Liu, XS, *TRUST4: immune repertoire reconstruction from bulk and single-cell RNA-seq data*. Nat Methods. 2021 Jun;18(6):627-630. \[[PubMed](https://pubmed.ncbi.nlm.nih.gov/33986545/)\]

**Song, L**, Sabunciyan, S, Yang, G and Florea, L, *A multi-sample approach increases the accuracy of transcript assembly*. Nat Commun. 2019; 10: 5000 \[[PubMed](https://pubmed.ncbi.nlm.nih.gov/31676772/)\]

Zhang, J, Hu, X, …, **Song, L**, …, Liu, XS, *Immune receptor repertoires in pediatric and adult acute myeloid leukemia*. Genome Med. 2019 Nov 26;11(1):73. \[[PubMed](https://pubmed.ncbi.nlm.nih.gov/31771646/)\]

You, Y, **Song, L**, Nonyane, BAS, Price, LB, Silbergeld EK, *Genomic differences between nasal Staphylococcus aureus from hog slaughterhouse workers and their communities*, PLoS One. 2018 Mar 6;13(3):e0193820. \[[PubMed](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5839586/)\]

Miller, JR, Zhou, P, Mudge, J, …, **Song, L**, ..., Silverstein, KAT, *Hybrid assembly with long and short reads improves discovery of gene family expansions*, BMC Genomics. 2017;18(1):541. \[[PubMed](https://pubmed.ncbi.nlm.nih.gov/28724409/)\]

**Song, L**, Sabunciyan, S and Florea, L, *CLASS2: accurate and efficient splice variant annotation from RNA-seq reads*, Nucleic Acids Res. 2016;44(10):e98. \[[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/26975657)\]

**Song, L**, Shankar, D and Florea, L, *Rascaf: improving genome assembly with RNA-seq data*, Plant Genome. 2016;9(3). \[[PubMed](https://www.ncbi.nlm.nih.gov/pubmed/27902792)\]

Kim, D, **Song, L** \*, Breitweiser, FP and Salzberg, SL, *Centrifuge: rapid and sensitive classification of metagenomic sequences*, Genome Res. 2016; 26(12): 1721–1729. \[[PubMed](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5131823/)\] (\*co-first author) 

**Song, L** and Florea, L, *Rcorrector: efficient and accurate error correction for Illumina RNA-seq reads*, Gigascience. 2015;4:48. \[[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/26500767)\]

**Song, L**, Florea, L and Langmead, B, *Lighter: fast and memory-efficient sequencing error correction without Counting*, Genome Biol. 2014;15(11):509. \[[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/25398208)\]

**Song, L** and Florea, L, *CLASS: constrained transcript assembly of RNA-seq reads*, Third Annual RECOMB Satellite Workshop on Massively Parallel Sequencing - RECOMB-SEQ 2013, BMC Bioinformatics 14(Suppl 5):S14. \[[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/23734605)\]

Florea, L, **Song, L** and Salzberg, SL, *Thousands of exon skipping events differentiate among splicing patterns in sixteen human tissues*, F1000 Research 2013, 2:188. \[[Full text](http://f1000research.com/articles/2-188/v1)\]

Preprints
======
Zhang, H, **Song, L** \*, …, Liu, XS, Li, H, *Fast alignment and preprocessing of chromatin profiles with Chromap*. bioRxiv 2021.06.18.448995. \[[Full text](https://www.biorxiv.org/content/10.1101/2021.06.18.448995v1)\] (\*co-first author)
