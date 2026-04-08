# Identification of High-Impact BRCA2 and TP53-Pathway Variants from Human NGS Data

This project performs an end-to-end cancer variant calling workflow from raw FASTQ files to biologically meaningful variant interpretation.

## Workflow
- FASTQ quality control using fastp
- Alignment to GRCh38 using BWA
- BAM sorting and indexing using samtools
- Variant calling using bcftools
- Functional annotation using SnpEff
- Extraction of high-impact cancer-related variants

## Key Findings
- Processed 85M paired-end reads
- Identified 17,442 potentially functional variants
- Detected 26 variants in cancer-associated genes
- Found missense variant in BRCA2: p.Val2466Ala
- Found frameshift variant in TP53I11: p.Ala140fs
- Found variants in TP53AIP1 and TP53BP1
