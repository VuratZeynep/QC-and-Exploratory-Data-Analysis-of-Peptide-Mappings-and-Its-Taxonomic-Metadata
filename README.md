# QC-and-Exploratory-Data-Analysis-of-Peptide-Mappings-and-Its-Taxonomic-Metadata

  This repository includes two notebooks covering quality control steps and exploratory analysis of mapped peptide dataset and its metadata. For both notebooks, the analyses were supported by markdown notes and comments within the code. The final section includes the key findings of the analysis, potential patterns, and data issues.

### Parquet files:

1. Mapped peptide file – contains the peptide mapping results. (97.744.896 rows, 4 columns)
2. Metadata file – serves as a lookup table for annotations. (4.353.709 rows, 9 columns)

### Notebooks: 

1. QC_and_overview.ipynb
2. Core_analysis.ipynb

### QC and Overview Notebook covers:

1. Loading both Parquet files

2. Quick QC: number of rows/columns, missing values, duplicates

3. Column overview: listing the main columns and what they represent

### Core Analysis Notebook covers:

1. Top counts tables (top 10–20) for:

        i. Most frequent peptides (top 20)

            a. The prevalence of the top 20 peptides in viruses and humans

            b. Peptides with viral + human overlaps

   
        ii. Most frequent accessions/proteins

        iii. Most frequent taxids and/or families (via lookup)


    3. Distributions/plots:

        i. Peptide frequency distribution (how often peptides repeat)

        ii. Counts per taxid/family (bar plot for top groups)

    4. Findings
