# Lung Squamous Cell Carcinoma Dataset Analysis Project

### Project Overview
This project focuses on the bioinformatics analysis of Lung Squamous Cell Carcinoma (LUSC), leveraging RNA sequencing data. The aim is to uncover gene expression profiles and identify key biomarkers and therapeutic targets for better understanding and treatment of LUSC.

### Dataset
The project uses publicly available RNA-seq data from LUSC patients, representing gene expression levels across tumor and normal lung tissue samples.

### Methods
Use of bioinformatics tools for:
- Gene expression analysis
- Differential expression analysis
- Network-based gene interaction analysis

### Setup & Requirements

Python 3.8+ \
Required libraries: pandas, numpy, matplotlib, seaborn, scipy, networkx, biopython \
Install via ```pip install -r requirements.txt``` 

R 4.0+ \
Required packages: DESeq2, edgeR, limma, WGCNA, CIBERSORT \
Install in R with ```BiocManager::install()``` 

### Results
Gene Expression Results: List of upregulated and downregulated genes in LUSC. \
Network Analysis: Identification of key hub genes that may serve as therapeutic targets. \
Immune Infiltration Profiles: Insights into immune cell populations and potential for immunotherapy interventions. 

### How to Contribute
Fork the repository.
Create a new branch with 
```
git checkout -b feature-branch
```
Make changes and test them.
Submit a pull request explaining your changes.

### Authors
Sara Baldinelli, Letizia De Pietri, Roan Spadazzi
