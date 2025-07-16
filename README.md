# BuscoAutomation
BuscoAutomation is a simple Bash script to simplify and scale BUSCO analyses across multiple genomes.

It automates the execution of BUSCO for several genome files and generates:
1. A .cvs table summarizing the completeness scores.
2. a buscoPlot directory with your buscoPlot.

## Features
* Batch execution of BUSCO for multiple genomes
* Automatic extraction of summary metrics.
* Output table (.csv) ready for further analysis or visualization.
* Optional generation of summary plots for quick assessment.

## Limitations
* This script was optimized for ~60 genomes.
* It may work with larger datasets, but performance can drop significantly without parallelization.
* For datasets with >1000 genomes, consider combining it with tools like Open MPI.

## Repository Structure

BuscoAutomation/  
├── busco_automation.sh    # Main script  
├── genomes/               # Input genome FASTA files  
├── busco/                 # Output folder with BUSCO results  
├── busco_plot/            # Folder with summary plots  
├── busco_summaries.csv    # Final output table  
└── README.md              # This file  

## Citation
Coming soon.

## Requirements
* BUSCO v5+
* Dependencies:
* A set of genome FASTA files in a */genomes* folder.  
**Atention: Make sure all genome filenames use the same extension (e.g., .fna or .fasta) to ensure consistency and compatibility.**

## How to use




## About the author

Dáfne de Oliveira Vianei  
Biological Sciences, Universidade Federal de Minas Gerais  
E-mail vianeidafne@gmail.com  
LinkedIn www.linkedin.com/in/dafnevianei
