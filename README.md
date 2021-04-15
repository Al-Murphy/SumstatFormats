# SumstatFormats
Meta-analysis of the most common GWAS Summary Statistic file formats

## Background
SumstatsFormats builds upon the work of the [gwas-download repository](https://github.com/mikegloudemans/gwas-download) which created a script to download publicly available GWAS summary statistics from over 200 different publications.

## Results
Click [here](https://al-murphy.github.io/SumstatFormats/analysis.html) to view the meta-analysis of GWAS Summary Statistic file formats.

## Running SumstatFormats
SumstatFormats goal is to give insight into the most frequent format of summary statistic files from GWAS. If you want to run the code yourself please first run the download script from gwas-download and set your working directory to this repository's folder.

## Future work
SumstatFormats highlights the disparity across summary statistic files, creating a barrier major to automated meta-analysis studies. To address this issue, the bioconductor R package MungeSumstats was created to standardise the file format of summary statistic files, including VCF files. See the [MungeSumstats github page](https://github.com/neurogenomics/MungeSumstats) for more details.
