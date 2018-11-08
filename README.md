# ClassifyR

Data and slides for ClassifyR workshop at Bioconductor Symposium, presented by Dr Dario Strbenac and Dr Shila Ghazanfar.  

This repository contains presenter slides and data files used for the ClassifyR workshop at [Bioconductor Hands-on Training Day](https://www.abacbs.org/bioc2018-handson-training-day/) on Thursday 29th November 2018.

--------

To install Bioconductor software, BiocManager must firstly be obtained from CRAN.

```
install.packages("BiocManager")
library(BiocManager)
```

Before attending the workshop, ensure R is at least version 3.5.0 and install ClassifyR using

```
install("ClassifyR", dependencies = TRUE)
```

Additionally, DESeq2, EDASeq and genefilter are used for some exploratory visualisations and analysis. They can be installed by running the command

```
install(c("DESeq2", "EDASeq", "genefilter"))
```
