# scDetect
scDetect is a new cell type ensemble learning classification method for single-cell RNA sequencing across different data platforms, using a combination of gene expression rank-based method and majority vote ensemble machine-learning probability-based prediction method.

To further accurate predict the tumor cells in the single cell RNA-seq data, we developed scDetect-Cancer, a classification framework which incorporated the cell copy number information and epithelial origin information in the classification. 

This [scDetect introduction](https://ivdgenomicslab.github.io/scDetect-Introduction/) shows a basic workflow for cell type prediction.

scDetect required the package "rJava". You can install and load the package as follows:

```markdown
install.packages("rJava") 
library(rJava)
```

You can install scDetect via devtools as follows:

```markdown
devtools::install_github("IVDgenomicslab/scDetect")
```
