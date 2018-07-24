# _ProteinParameters_
An R package to calculate commonly used protein parameters such as molecular weight, theoretical pI, extinction coefficient, and E1%. Can be used to calculate values for a large number of sequences simultaneously.

# _Installation_
Install and load the following packages
```R
install.packages("devtools")
library(devtools)
install_github("Bioconductor/Biostrings")
library(Biostrings)
install_github("Bioconductor/ShortRead")
library(ShortRead)
install_github("tidyverse/stringr")
library(stringr)
install_github("tidyverse/dplyr")
library(dplyr)
install_github("tidyverse/plyr")
library(plyr)
install_github("ypriverol/pIR")
library(pIR)
// code for coloring
```
# _Vignette_
```
in.file <- read.csv("~/Proteins/Sequences.csv")
prot.parameters <- ProteinParam(in.file, out.file)
```




