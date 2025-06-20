## WGS-ngs-analysis
Pipeline for variant calling and annotation using whole genome sequencing (WGS) data

## WGS Variant Analysis - Escherichia coli K12

This project performs whole-genome sequencing (WGS) variant calling and annotation on *E. coli* K12.

## Folder Structure

- `data/` – Raw FASTQ and reference genome files.
- `scripts/` – Bash scripts for each processing step.
- `results/` – Filtered/annotated VCFs, BAM files, and FastQC reports.
- `docs/` – SNP annotation summary HTML and supporting documentation.

## Tools Used
- FastQC
- BWA
- SAMtools
- BCFtools
- SnpEff

## Pipeline Overview

1. Quality check with FastQC
2. Alignment using BWA
3. BAM conversion and sorting with SAMtools
4. Variant calling with BCFtools
5. Variant filtering
6. Annotation with SnpEff
