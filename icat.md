---
layout: page
title: Saint Louis University Medical School: TCR Analysis
subtitle: Dr. Tae-Hyuk Ahn and Dr. Richard DiPaolo
cover-img: /assets/img/slu_research.png
share-img: /assets/img/slu_research.png
---

### iCAT: Diagnostic Assessment Tool of Immunological History using High-Throughput TCR Sequencing

The pathogen exposure history of an individual is recorded in their T-cell repertoire and can be accessed through the study of T-cell receptors (TCRs) if the tools to identify them were available. For each T-cell, the TCR loci undergoes genetic rearrangement that creates a unique DNA sequence. In theory these unique sequences can be used as biomarkers for tracking T-cell responses and cataloging immunological history. We developed the immune Cell Analysis Tool (iCAT), an R software package that analyzes TCR sequencing data from exposed (positive) and unexposed (negative) samples to identify TCR sequences statistically associated with positive samples. The presence and absence of associated sequences in samples trains a classifier to diagnose pathogen-specific exposure. We demonstrate the high accuracy of iCAT by testing on three TCR sequencing datasets. First, iCAT successfully diagnosed smallpox vaccinated versus naïve samples in an independent cohort of mice with 95% accuracy. Second, iCAT displayed 100% accuracy classifying naïve and monkeypox vaccinated mice. Finally, we demonstrate the use of iCAT on human samples before and after exposure to SARS-CoV-2, the virus behind the COVID-19 global pandemic. We were able to correctly classify the exposed samples with perfect accuracy. These experimental results show that iCAT capitalizes on the power of TCR sequencing to simplify infection diagnostics. iCAT provides the option of a graphical, user-friendly interface on top of usual R interface allowing it to reach a wider audience.

[PubMed](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8276190/)

### Tracking Antigen Exposure Using Deep Neural Networks

Because infection causes expansion of pathogen specific T cells that express pathogen specific unique receptors encoded in DNA,  exposure history of an individual can be accessed through examination of their T-cell receptors (TCRs). These unique sequences can be used as biomarkers for tracking T-cell responses and cataloging immunological history. 

The advent of high-throughput sequencing and analyses of immune cell receptor sequences has presented a unique opportunity to inform our understanding of immunological responses to infections. Following the body’s recovery, pathogen-specific immune cells and their receptor sequences remain present at higher frequencies, with their increase in frequency preventing subsequent infections. As a result of their persistence in the body, T-cells are a useful tool for diagnosing infections and evaluating vaccine efficacy as a stable biomarker. However, this process requires thorough analysis of massive datasets at an accuracy beyond the capabilities of traditional statistical tests. 

Here we utilize a Deep Neural Network to identify specific viral infections or vaccination statuses of 4 TCR sequenced cohorts: mouse monkeypox, mouse smallpox, human cytomegalovirus serostatus, and human smallpox. The success of our intensive experiments holds the potential for the speedy creation of low-cost, highly accurate diagnostic assays.

### Assessing Covid Severity Through Convolutional Neural Networks

The adaptive immune system responds to disease through highly variable coded receptors that identify pathogens and antigens. These receptors are encoded by unique DNA sequences that allow immune cells to express millions of different receptors. Analysis by high-throughput sequencing of these immune cell receptor sequences present a reliable indication of immune health, disease proliferation, and disease mutability. Even following infection, the diversity of pathogen-specific immune cells and their receptor sequences can serve as a lasting measure of patient health, disease efficacy, and rate of mutation. 
As such, binary classifications of publicly available samples would be possible through clustering graph convolutional networks. Forging predictive models capable of forecasting patient health through the acceptance of multi-vectored immune cell data. However, node classification in high vector space requires both the native preprocessing of sizable datasets and an established Graphical Neural Network framework.


