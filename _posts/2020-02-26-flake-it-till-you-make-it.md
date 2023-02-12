---
layout: post
title: VIPER
subtitle: Identification of high-impact structural variants in tomato leaves
#cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/gungir_picture1.png
#share-img: /assets/img/path.jpg
tags: [structural variants, leaflet morphology, RNA-seq]
---

### Abstract

  Structural variants (SV) are recognized as a prominent source of genetic variation, with single variants manifesting significant influence over phenotypic expression. However, their effects remain poorly understood due to computational limitations and a continued focus on SNPs. Addressing this need, we introduce the Variant Identification Pipeline with Expression Realization (VIPER), a robust computational pipeline created to identify and annotate structural variants with significant impact on gene expression. Using a publicly available structural variant collection as reference (Alonge et al., 2020), VIPER accepts processed RNA sequence data and constructs a list of SV-gene pairs based on genetic position. These SV-gene pairs are then evaluated by their differential expression values, with pairs expressing significant RPKM differentials concatenated to form a library of high-impact SV-gene pairs. Finally, the library is enriched by annotating genes for function, allowing for the identification and selection of candidate variants with desirable phenotypic influences.

To evaluate the efficacy of VIPER, we constructed a causal genomic library from a collection of 108 tomato leaf samples. A candidate insertion from this library, which we labelled GUNGIR, affirmed VIPER by expressing a  significant influence over leaflet morphology as quantified by a fivefold principal component system. 

### RNA Data Preparation

![Figure_1](/assets/img/viper_fig1.png)

*Figure 1. A visualization of the pipeline created to process our raw RNA sequence data. The data originated from the leaf material of 36 tomato accessions with 3 biological replicates per accession, culminating in 108 total samples. Each sample was trimmed for various contaminants and subsequently aligned with the Heinz tomato genome to generate RPKM data. The RPKM values were normalized and merged by accession using homebrew scripts in conjunction with the Fei lab to generate single RPKM values for each accession.*  

