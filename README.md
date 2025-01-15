
![](logo-sm.png)

# R for Biological / Medical Data Analysis

## Part 1 (R for Medical Data) - January 22nd 9:00 - 12:00

### Overview

+ Importing example "medical data" from a spreadsheet
+ selecting columns
+ restricting rows with filter
+ summarising data, and grouping
+ boxplots and bar plots
+ "piping" to create short workflows

### Pre-course package install

Please install the following packages **before the course** using the following code:-

```
install.packages(c("readr",
                  "dplyr",
                  "ggplot2",
                  "stringr",
                  "forcats"))
```

### Pre-course downloads

Please download all these files and place in a folder that you wish to work in

+ [Example Data (tcga_clinical_CLEANED.tsv)](tcga_clinical_CLEANED.tsv)
+ [Example Data 2 (tcga_clinical_MESSY.tsv)](tcga_clinical_MESSY.tsv)
+ [R Markdown](Part1.Rmd)

### Materials

+ [HTML](Part1.nb.html)

## Part 2 (R for omics analysis) - January 29th 09:00 -12:00

### Overview

+ Importing some RNA-sequencing counts
+ Using PCA as QC diagnostic
+ Differential expression to find statistically-significant genes
+ Using databases to map between gene naming schemes
+ Associating statistical findings with biological and clinical significance

### Package Install

Please install the following packages **before the course** using the following code:-

```
install.packages("BiocManager")
BiocManager::install(c("SummarizedExperiment",
                      "tidybulk",
                      "org.Hs.eg.db",
                      "EnhancedVolcano",
                      "ggrepel"))

```

### Download before the course

- [Breast Cancer RNA-Seq counts](brca_example.tsv)
- [Breast Cancer RNA-Seq metadata](brca_example_meta.tsv)
- [R Markdown](Part2.Rmd)

### Rendered Materials

- [HTML](Part2.html)

  