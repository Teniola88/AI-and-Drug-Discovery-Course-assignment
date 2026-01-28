# Assignment 2: QSAR Data Curation Using ChEMBL

## Overview
This repository contains code and data for Assignment 2 of the AI and Drug Discovery course (2026).

## Target Selection
**Target:** NKX3  
**ChEMBL Target ID:** [CHEMBL3157]

## Dataset
- **File:** `bioactivity_preprocessed_data_nkx3.csv`
- **Records:** 395 compounds
- **Columns:** molecule_chembl_id, canonical_smiles, standard_value, bioactivity_class
- **Activity Classes:** Active (<1000 nM), Intermediate (1000-10000 nM), Inactive (≥10000 nM)

## Files
- `assignment_2_QSAR_data_curation.ipynb` - Main analysis notebook
- `bioactivity_preprocessed_data_nkx3.csv` - Curated dataset
- `README.md` - This file

## Workflow
1. Data retrieval from ChEMBL API
2. Data cleaning and preprocessing
3. Activity classification
4. Dataset export

## Author
Imoleayo T. Opajobi

## Course
AI and Drug Discovery, 2026
Important Not
