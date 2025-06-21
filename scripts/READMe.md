## Whole Genome Sequencing Analysis Scripts

The following scripts perform key steps in a bacterial whole genome sequencing (WGS) analysis pipeline using Illumina paired-end data. Specifically, they cover:
- Uploading the reference FASTA genome
- Quality control (QC) of raw reads
- Trimming low-quality bases and adapters using Fastp
- Indexing the reference genome
- Mapping reads to the reference using BWA
- Variant calling and filtering
- Functional variant annotation using SnpEff
