## _ProteinParameters_
An R package to calculate commonly used protein parameters such as molecular weight, theoretical pI, extinction coefficient, and E1%. Can be used to calculate values for a large number of sequences simultaneously.

## _Installation_
Install and load the following packages
```
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
```
## _Usage_
```
input.file <- readcsv("/filepath/filename.csv")
output.file <- file.path("/filepath/filename.csv")
ProteinParam <- Parameters(input.file)
```
#### Input file format: csv file with sequence name in first column and sequence in second column



