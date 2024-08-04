# **RuFEnTroFo**

### **Overview**

Welcome to RuFEnTroFo (Rubiaceae-Associated Fungal Endophytes in Tropical Forests) repository! This repository houses scripts and tools for analyzing ecological data and assigning taxonomy to Amplified Sequence Variants (ASVs) identified as fungi from BioProject PRJNA889378. Additionally, it includes functionality for analyzing associated functional traits sourced from the FunTraits database.

This repository is primarily intended for the audience of our associated paper "Exploring biodiversity dynamics and taxonomy of Rubiaceae fungal endophytes in tropical regions". It provides access to the code used to reproduce the results presented in the paper and allows users to explore and verify the analyses conducted in the study.

### **Contents**

#### 1. Taxa_Inference
This directory hosts scripts for taxa inference using a modified DADA2 pipeline. This customized pipeline is optimized for accurately assigning taxonomy to fungal Amplified Sequence Variants (ASVs) from the Rubiaceae-associated fungal endophytes dataset (BioProject PRJNA889378).

#### 2. Data Curation
This directory focuses on data quality control and filtering. It manipulates the phyloseq object from the Taxa_Inference directory, prunes taxa and samples based on specified thresholds, and performs prevalence analysis, including visualization.

#### 3. Ecological_Analyses
This directory contains scripts for conducting various ecological analyses, including:

Alpha diversity analysis
Beta diversity analysis (Non-metric Multidimensional Scaling (NMDS), PERMANOVA)
Species accumulation curves

#### 4. Ecological_Analyses_2
Here you'll find scripts for more advanced ecological analyses, including:

Identification of top families based on overall abundance
Taxonomy plotted
Fungal traits analysis
Clam test for classifying generalists and specialists in two distinct habitats
Indicator species and prevalence analyses

### **Additional Files**
TaxaFuncT.xlsx: Contains full taxonomic classification and functional traits based on primary lifestyle of all ASVs.

### **Usage**
To utilize the scripts and tools provided in this repository, follow these steps:

Clone the repository to your local machine.
Navigate to the desired directory for your analysis.
Execute the scripts using an appropriate environment (R, Rstudio) and provide the necessary input data.
Refer to this README file for detailed information on where to find specific scripts.

### **About**
This repository serves as a resource for researchers interested in the ecological dynamics of Rubiaceae-associated fungal endophytes in tropical forests. It provides a suite of tools for analyzing and interpreting ecological data, as well as assigning taxonomy and exploring functional traits associated with these fungi.

### **Contributors**
Humberto Castillo González

### **Contact**
For questions or inquiries about this repository, please contact hmbrto.cg@gmail.com
