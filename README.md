# NGCHM Demo Data

This package contains demonstration data for the
[NGCHM-R package](https://github.com/MD-Anderson-Bioinformatics/NGCHM-R). Loading the NGCHMDemoData package makes the data available in the R session.

## Installation

This package can be installed from the [MD-Anderson-Bioinformatics R-Universe](https://md-anderson-bioinformatics.r-universe.dev/packages) repository.


```R
install.packages("NGCHMDemoData", repos = c("https://md-anderson-bioinformatics.r-universe.dev", "https://cran.r-project.org"))
```

## Details

This data was obtained from the [MBatch Omic Browser](https://bioinformatics.mdanderson.org/MQA/).
In order to create a data set small enough for demonstration purposes the expression data was filtered
to remove genes with low expression and variance, and only 200 randomly selected samples were used.

- TCGA.BRCA.ExpressionData MBatch Omic Browser information:
  - Source: GDC
  - Category: Gene Expression Quantification
  - Platform: HTSeq - Counts
  - Version: 2020\_12\_22\_1000
- TCGA.BRCA.TP53MutationData MBatch Omic Browser information:
  - Source: GDC
  - Category: Masked Somatic Mutation
  - Platform: SomaticSniper Variant Aggregation and Masking
  - Version: 2020\_12\_22\_1000


