This folder contains the output files generated during the WGS pipeline:

- **Quality Reports:**
  - `fastp_report.html`: Summary of trimmed reads
  - `*_fastqc.html`: Quality control 

  - **Variants:**
  - `variants.vcf`: Raw variants called by FreeBayes
  - `annotated_variants.vcf`: Functional annotation via SnpEff
  - `variants.tsv`: Tabular summary (CHROM, POS, REF, ALT, QUAL)
