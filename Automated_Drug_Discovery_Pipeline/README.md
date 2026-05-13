# Fully Automated Molecular Docking & MD Simulation Pipeline
This repository contains an end-to-end Python pipeline for structure-based drug discovery, built entirely for Google Colab. 

## Workflow Overview
1. **Data Acquisition:** Fetching PDB and PubChem structures.
2. **Structure Prep:** Cleaning and converting to .pdbqt via OpenBabel.
3. **Docking:** High-throughput virtual screening using AutoDock Vina.
4. **ADMET:** Pharmacokinetics evaluation using Lipinski's Rule of 5 (RDKit).
5. **Analysis:** Automated data extraction and Matplotlib visualization.
6. **MD Simulation:** GPU-accelerated molecular dynamics using OpenMM.

## Getting Started
To use this pipeline, open the files in the `notebooks/` directory sequentially in Google Colab.
