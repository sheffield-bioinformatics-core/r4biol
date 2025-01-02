
![](logo-sm.png)

# R for Biological Data Analysis

## Part 1 (R with a biological twist)

### Overview

+ Importing example "medical data" from a spreadsheet
+ selecting columns
+ restricting rows with filter
+ summarising data, and grouping
+ boxplots and bar plots
+ "piping" to create short workflows

### Package install



```
install.packages(c("readr",
                  "dplyr",
                  "ggplot2",
                  "stringr",
                  "forcats"))
```

### Materials

+ [HTML](Part1.nb.html)
+ [Markdown](Part1.Rmd)
+ [Example Data (tcga_clinical_CLEANED.tsv)](tcga_clinical_CLEANED.tsv)

## Part 2 (Tidy RNA-seq)

### Overview

+ Import some RNA-sequencing counts
+ long vs wide data
+ Using PCA as QC diagnostic
+ Differential expression to find statistically-significant genes
+ Associating statistical findings with biological and clinical significance

### Materials

- [HTML](Part2.nb.html)
- [Markdown](Part2.Rmd)
 
  