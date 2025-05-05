Genomic Health Navigator Pipeline

This repository contains a Snakemake-based pipeline for DNA processing, variant calling, annotation, polygenic risk scoring with TensorFlow models, and automated report generation via Jinja2/LaTeX.

Features

FastQC (optional): Quality control of raw sequencing reads.

Alignment: BWA-MEM alignment to reference genome.

Sorting & MarkDuplicates: SAMtools sorting and GATK MarkDuplicates.

Variant Calling: GATK HaplotypeCaller for genomic variants.

Annotation: SnpEff annotation of raw VCFs.

Polygenic Risk Scoring: TensorFlow-based scoring per trait.

Report Generation: Jinja2 template rendering and LaTeX compilation to PDF

Prerequisites

Conda (recommended) or Python 3.10+

Snakemake

BWA, SAMtools, GATK, SnpEff

LaTeX (e.g., TeX Live) for PDF compilation
