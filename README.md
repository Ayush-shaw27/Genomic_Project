# 🧬 Distributed Genomic Sequencing for Rare Disease Identification

## Overview
Big Data + ML pipeline using Apache Spark to identify rare disease patterns
from 2M+ real genomic variants (NCBI ClinVar dataset).

## Tech Stack
PySpark | Scikit-learn | Pandas | Matplotlib | Seaborn | Google Colab

## Dataset
- **Source:** NCBI ClinVar — https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/
- **File:** variant_summary.txt.gz (~200MB)
- **Records:** 2,000,000+ genetic variants
- **Auto-downloads** inside Colab — no manual upload needed

## How to Run
1. Open `Genomic_Rare_Disease_Pipeline.ipynb` in Google Colab
2. Click Runtime → Run All
3. Allow Google Drive access when prompted
4. Dataset downloads automatically from NCBI

## Pipeline Modules
1. Data Ingestion
2. Data Preprocessing
3. Feature Engineering
4. Distributed Processing (Spark)
5. ML Modeling (K-Means + Random Forest)
6. Evaluation Metrics
7. Visualization
8. Final Output

## Results
See `/outputs/` folder for plots and evaluation scores.
