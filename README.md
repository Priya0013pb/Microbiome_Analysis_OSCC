# From Bacteria to Biomarkers: Oral Microbiome Exploration for Early Oral Cancer Diagnosis

## Overview
This project examines the potential microbial features in saliva samples that can serve as biomarker for early detection of Oral Squamous Cell Carcinoma (OSCC) through 16S rRNA sequencing. 
## Data
Source: NCBI SRA BioProject (PRJNA1150391)
## Data Processing
16S rRNA sequences quality assessment with FastQC, QIIME2 and DADA2
Taxonomic Classification and Microbiome diversity analysis among OSCC and Healthy groups
Statistical analysis for differential abundance testing
Random Forest-based machine learning for biomarker discovery

## Packages and Tools Used
FASTQC and Trimmomatic for quality assessment and trimming
QIIME2 and DADA2 for microbiome analysis
Python 3.10 for statistical analysis, visualization and machine learning model with libraries: Pandas NumPy Matplotlib Plotly Seaborn Scikit-learn Statsmodels

### Microbial Composition
•	High abundance of Fusobacterium (5.5%) and Prevotella (2.5%) in OSCC group in terms of control 
•	Both groups are dominated by Streptococcus (about 33%), but with greater abundance in control group
•	Presence of Rothia (4.7%) and abundance of Neisseria (7.1%) in the control group
•	Bacterial profiles compared to controls

### Statistical Analysis
-	Statistical significance was not seen due to the presence of small dataset
-	OSCC group indicates greater diversity than healthy control
-	Random Forest ML model achieved AUC=1.00
-	A loss of microbial evolutionary richness is detected

### Results

-	Potential Biomarker groups identified among the OSCC and Healthy control groups
-	Machine Learning Model shows potential for future diagnostic application
-	Identified key biomarkers:
o	Porphyromonas and Fusobacterium: Upregulated in OSCC group
o	Streptococcus and Gamella: Downregulated in Control group


