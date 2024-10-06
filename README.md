# Genomics-ProjectsPortfolio
"A collection of genomics and bioinformatics projects demonstrating skills in Python programming, HPC cluster usage, Bash scripting, and genomic data analysis."

### Author: Naga Sai Sarada Priya Mandala

## Overview

Welcome to my Genomics Projects Portfolio! This repository showcases a variety of genomics and bioinformatics projects where I applied Python, Bash, HPC (High-Performance Computing), and other bioinformatics tools to process, analyze, and interpret genomic data. The projects include tasks such as sequence assembly, ORF identification, phylogenetic tree construction, codon usage modeling, sequence classification using Markov models, and quality control analysis using FastQC.

While the source code for these projects is kept private due to confidentiality reasons, this repository includes detailed descriptions, project highlights, the tools and programs used, and example outputs. If you're interested in viewing the code or discussing my work, please feel free to contact me.

### Key Skills Demonstrated:
- Python programming for genomics and bioinformatics
- Bash scripting and Linux environment for bioinformatics workflows
- High-Performance Computing (HPC) usage for large-scale genomic data processing
- Biological sequence analysis and assembly
- Gene data retrieval and annotation
- Automated testing and data validation for bioinformatics pipelines
- Statistical modeling of biological data

## Technologies, Programs, and Tools Used:
- **Python**: Core programming language for scripting and bioinformatics analysis.
- **Bash & Linux**: Utilized for scripting and managing bioinformatics workflows on HPC clusters.
- **HPC Cluster**: High-performance computing environment used for large-scale data processing and parallelization.
- **Bioinformatics Libraries/Tools**:
  - **Biopython**: For advanced biological sequence analysis.
  - **FASTA**: File format used for sequence data input and processing.
  - **FastQC**: For assessing the quality of sequencing data.
  - **Numpy**: For numerical data processing and matrix manipulation.
  - **Matplotlib**: For visualizing data and results.
  - **PyTest**: For automated testing of bioinformatics scripts.
- **Data Sources**: Public gene and protein databases, such as NCBI and UniProt, used for retrieving biological data.
- **Version Control**: Git for repository management.

## Projects Included

### 1. Sequence Assembly Script
- **Description**: This project performs sequence assembly by reading a file containing DNA sequences and assembling them into contigs based on sequence overlap. The script efficiently handles sequence manipulation and assembly using a deque structure for faster processing.
- **Technologies Used**: Python, Deque from `collections`, FASTA format.
- **Skills Applied**: Sequence assembly, efficient data handling using deque, Python scripting.
  
### 2. ORF Identification Script
- **Description**: This project identifies Open Reading Frames (ORFs) within genomic sequences. The script uses a motif scoring approach to find ORF start positions and scans the sequences for ORFs meeting specific criteria.
- **Technologies Used**: Python, motif scoring algorithm, FASTA format.
- **Skills Applied**: ORF identification, motif scoring, sequence analysis.

### 3. Random Read Generation and ORF Detection
- **Description**: This project generates random DNA reads and detects ORFs using a sliding window approach. The ORFs are written to an output file, and the length distribution of the ORFs is visualized using histograms.
- **Technologies Used**: Python, `matplotlib`, `random`, FASTA format.
- **Skills Applied**: Random sequence generation, ORF detection, data visualization using histograms.

### 4. UPGMA Phylogenetic Tree Construction
- **Description**: This project implements the UPGMA (Unweighted Pair Group Method with Arithmetic Mean) algorithm to construct phylogenetic trees from a distance matrix of species. The resulting species clustering is output as a phylogenetic tree.
- **Technologies Used**: Python, Numpy, distance matrices.
- **Skills Applied**: Phylogenetic tree construction, matrix manipulation, evolutionary biology.

### 5. Codon Usage Model Scoring
- **Description**: This project uses a codon-based model to score sequences for potential coding versus non-coding regions. Log-likelihood scores are computed to classify sequences as coding or non-coding.
- **Technologies Used**: Python, mathematical modeling, probability matrices.
- **Skills Applied**: Codon usage analysis, log-likelihood modeling, sequence classification.

### 6. Markov Chain Model for Sequence Classification
- **Description**: This project uses a Markov chain model to classify genomic sequences based on dinucleotide transition probabilities. It trains models on pathogen and non-pathogen sequences and classifies new sequences based on the likelihood scores.
- **Technologies Used**: Python, Markov chains, Matplotlib.
- **Skills Applied**: Sequence classification, Markov models, probabilistic modeling, data visualization.

### 7. FastQC Analysis 
- **Description**: In this project, I performed quality control analysis of sequencing data using the FastQC tool. I leveraged my university's HPC cluster to process large datasets in parallel. Using Bash scripting and the Linux environment, I automated FastQC jobs and processed the results.
- **Technologies Used**: FastQC, Bash scripting, HPC Cluster, Linux, HTML output for quality reports.
- **Skills Applied**: Quality control of sequencing data, HPC cluster management, Bash scripting, parallel job execution, sequencing data analysis.

---

## Confidentiality and Code Access

Due to confidentiality reasons, the source code for these projects is kept private. However, I am happy to provide access to the code upon request for review or collaboration purposes. If you're interested in viewing the code, learning more about the projects, or discussing potential opportunities, please feel free to contact me.

## Contact Information

- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/priya-mandala17/)

Thank you for taking the time to explore my Genomics Projects Portfolio! I look forward to connecting and discussing potential opportunities or collaborations.

---
