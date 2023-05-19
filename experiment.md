## Introduction

Over 1.5 million women (25% of all women with cancer) are diagnosed with breast cancer (BC) every year, making it the most common cancer in women worldwide and the second leading cause of cancer mortality in women [1]. The tumour microenvironment (TME) is an important determinant of the initiation, progression and metastasis of cancer. Despite the existence of different BC subtypes and patient inter-variability, recent studies focused on the TME have been unveiling tumour-infiltrating immune cell patterns that are either correlated with poor patient prognosis or good outcome [2]. Myeloid cells compose a high fraction of breast tumour-infiltrating immune populations, with tumour associated macrophages (TAMs) reaching over 50% of the tumour mass in some BCs [3]. TAMs have already been described as being potent regulators of tumour-associated immune suppression, cell invasion and metastasis [2]. Nonetheless, their remarkable heterogeneity may conceal the real extent of pro- and anti-tumour effectors and the molecular determinants that control their functions. In vitro, macrophages have already been characterized as being able to be polarized with different stimuli and exert dual influences on tumourigenesis by either enhancing anti-tumour responses or by manifesting tumour-promoting activities [3]. However, we are still lacking a comprehensive characterization of the full spectrum of macrophage phenotypes in vivo. 

## Work Plan and Methods

We aim at characterising subtypes and activation states of breast tumour-infiltrating myeloid cells and define their molecular distinctiveness.
Karine Serre’s team has established a C57BL/6 triple-negative BC mouse model of tumour regression strictly dependent on the presence of macrophages, based on the myeloid cell properties to respond to stimulatory agents. 
In order to characterize the full spectrum of macrophage activation in vivo, we generated a scRNA-seq dataset consisting of 3 replicates of each of the following conditions:
* Tumours that were left to grow for a maximum of 15 days (Not-treated/Early-tumours);
* Tumours that were left to grow for up to 30 days (Big/Late-tumours); 
* Tumours with experimentally-induced anti-tumour macrophages (MCT/Treated tumours)

Karine’s team FACS sorted CD45+CD3–CD19–NK1.1– cells coupled with 10X Genomics microdroplet technology to prepare libraries for sequencing with an Illumina machine.
Most data analyses were performed in R (software environment for statistical computing), using packages from Bioconductor (public repository of R tools for the analysis of high-throughput genomic data, https://www.bioconductor.org/). Alignment and mapping of the reads was performed with Cell Ranger (https://github.com/10XGenomics/cellranger), designed to process 10x Genomics Chromium scRNA-seq raw data. Pre-processing, e.g., quality control and normalization,relied on packages developed for scRNA-seq data analysis, e.g., scater, scran and Seurat. We also developed scStudio, a web-based tool for scRNA-seq data analysis by non-computational researchers.


## References
[1] Sun et al. 2017. International Journal of Biological Sciences 
[2] Man et al. 2013. Journal of Cancer 
[3] Weagel et al., 2015. Journal of Clinical & Cellular Immunology 



