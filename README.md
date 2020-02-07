# Pancreatic Adenocarcinoma (PAAD)
## RNASeq Analysis of Pancreatic Adenocarcinoma Samples using GCT files
### AUTHOR: PAWAN VERMA
### LOCATION: Centre of Computation Natural Sciences and Biology (CCNSB), International Institute Of Information Technology, Hyderabad
### PLATFORM: R-3.6.1, RStudio
#### Link: https://mountainman12.github.io/PAAD/index.html

## OVERVIEW:
- The gene expression data was parsed using cmapR library
- Principal Compnent Analysis using stats library
- GSVA using GSVA library

## CONSTRAINTS:
- S4 object was not subsettable, when trying to remove samples
- The expression set contained NaNs and negative values
- The histological subtype (Other) data was avaliable for very few samples

## SESSION INFO
R version 3.6.1 (2019-07-05)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 18363)

Matrix products: default

locale:
[1] LC_COLLATE=English_India.1252  LC_CTYPE=English_India.1252    LC_MONETARY=English_India.1252
[4] LC_NUMERIC=C                   LC_TIME=English_India.1252    

attached base packages:
parallel stats graphics grDevices utils datasets methods base     

other attached packages:
GSVA_1.32.0 vsn_3.52.0 Biobase_2.44.0 BiocGenerics_0.30.0 cmapR_0.99.15

## ACKNOWLEDGEMNETS
- https://bioconductor.org/

## ISSUES
In case of any queries, contact: pawan12394@gmail.com
