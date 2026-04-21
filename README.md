# Pathogen Genomics Bioinformatics Training

This repository contains materials, exercises, and datasets for a hands-on training in pathogen genomics bioinformatics.

Modules progress from basic Linux skills to genomic epidemiology interpretation.

---

## Training Modules

| Module | Topic | Skills |
|--------|------|-------|
| 01 | Linux Command Line | file navigation, text processing |
| 02 | NGS Data QC | nanopore QC, trimming |
| 03 | Bioinformatics Workflows | metagenomics, alignment, consensus |
| 04 | Downstream Analysis | phylogenetics, clade interpretation |

---

## Repository Structure

pathogen-genomics-training/
│
├── module-01-linux/
│ ├── README.md
│ └── dataset/
│
├── module-02-ngs-qc/
│ ├── README.md
│ └── dataset/
│
├── module-03-workflows/
│ ├── README.md
│ └── dataset/
│
├── module-04-downstream-analysis/
│ ├── README.md
│ └── dataset/
│
└── environment-files/
├── qc-env.yml
├── kraken-env.yml
├── artic-env.yml


---

## Software Requirements

Most tools are installed using **conda**:

`conda create -n bioinfo-env`

`conda activate bioinfo-env`

`conda config --add channels defaults`

`conda config --add channels bioconda`

`conda config --add channels conda-forge`



---

## Expected Background

Participants should:

* know basic molecular biology
* be familiar with FASTA/FASTQ files
* have terminal access (Linux, Mac, WSL/Command Prompt for windows)

---

## Learning Outcomes

By the end of this training, participants should be able to:

* navigate Linux environments
* perform QC on sequencing data
* run pathogen genomics workflows
* interpret phylogenetic outputs for surveillance
