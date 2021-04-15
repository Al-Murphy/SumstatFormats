# SumstatFormats
Meta-analysis of the most common GWAS Summary Statistic file formats

## Background
SumstatsFormats builds upon the work of the [gwas-download](https://github.com/mikegloudemans/gwas-download) repository which created a script to download publicly available GWAS summary statistics from over 200 different publications.

## Results
The results of the meta-analysis of GWAS Summary Statistic file formats are described in Index.Rmd/HTML.

## Running SumstatFormats
SumstatFormats goal is to give insight into the most frequent format of summary statistic files from GWAS. If you want to run the code yourself please first run the download script from [gwas-download](https://github.com/mikegloudemans/gwas-download) and set your working directory to this repository's folder.

## Future work
SumstatFormats highlights the disparity across summary statistic files, creating a barrier major to automated meta-analysis studies. To address this issue, the bioconductor R package *MungeSumstats* was created to standardise the file format of summary statistic files, including VCF files. See the [MungeSumstats](https://github.com/neurogenomics/MungeSumstats) github page for more details.
