# Epigenetic Analysis of Glioma Sample

## Overview
This workflow focuses on epigenetic analysis of glioma samples using sequencing data to identify methylation patterns and regulatory regions associated with tumor progression.

## Objectives
- Identify DNA methylation patterns in glioma
- Detect hypermethylated genes and regions
- Understand epigenetic regulation in cancer

## Workflow
1. Basecalling using Oxford Nanopore (Dorado)
## Basecalling

Basecalling of raw FAST5 files was performed using Dorado with the high-accuracy model (dna_r9.4.1_e8_sup@v3.3).
This enabled accurate detection of nucleotide sequences and supported downstream methylation analysis.

dna_r9.4.1_e8_sup@v3.3_5mCG_5hmCG@v0
This model enables the identification of 5-methylcytosine (5mC) and 5-hydroxymethylcytosine (5hmC) modifications directly from Nanopore sequencing data.

Note: The model files are not included due to size and availability from official Oxford Nanopore sources.

3. Quality control of sequencing data
4. Alignment to reference genome
5. Methylation calling and extraction
6. Identification of differentially methylated regions
7. Downstream analysis and visualization

## Tools & Technologies
- Oxford Nanopore Sequencing
- Dorado Basecaller
- samtools, bedtools
- Python, R
- High-Performance Computing (HPC)

## Key Results
- Identified hypermethylated genes in glioma samples
- Generated methylation profiles for downstream analysis
- Produced processed datasets for further biological interpretation

## Repository Structure
