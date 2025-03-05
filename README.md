**Project Name** - Differential Expression Analysis using edgeR  

## Overview  

The project involves multiple steps, including:  

1. **Setting Up the Environment**  
   - Installing and loading required libraries (e.g., `edgeR`, `ComplexHeatmap`, `ggplot2`, `dplyr`).  
   - Reading raw gene expression count data (`GSE205748_read_counts_PsA.csv`).  
   - Importing metadata containing sample information (`GSE205748_series_matrix_edit.txt`).  

2. **Data Cleaning and Preparation**  
   - Checking for missing values and ensuring sample orders match.  
   - Filtering lowly expressed genes by setting a threshold.  
   - Normalizing counts using `calcNormFactors()`.  
   - Exporting processed count data (`GSE205748_cpm.txt`, `GSE205748_logcpm.txt`).  

3. **Exploratory Data Analysis (EDA)**  
   - Creating **boxplots** to visualize count distributions before and after normalization.  
   - Performing **Principal Component Analysis (PCA)** to explore variance in the dataset.  
   - Generating and exporting PCA plots.  

4. **Differential Expression Analysis (DEA)**  
   - Setting up the **design matrix** for comparisons.  
   - Creating a `DGEList` object and estimating dispersion.  
   - Performing statistical tests to identify differentially expressed genes.  

## Results & Output  
- Normalized expression values (`cpm` and `logCPM`).  
- Boxplots for count distribution.  
- PCA visualization of sample variance.  
- List of differentially expressed genes (to be included).  
