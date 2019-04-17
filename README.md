# Single-cell RNA-seq of human embryonic stem cell derived macrophage reveals distinct macrophage population

We used single-cell RNA-sequencing technology to characterize the human embryonic stem cells-derived macrophages (iMACs). 3,323 cultured iMACs were sequenced and 1,608 cells were further analysed after filtering. Our data showed that iMACs were grouped into 6 clusters with various different characteristics, such as glycolytic metabolism, mitochondrial respiration, proliferation and antigen presenting. These data will facilitate better understanding of heterogeneity in embryonic stem cell derived-macrophages at single cell resolution.

# INSTALL & RUN
1. Install R (www.r-project.org) & Rstudio (https://www.rstudio.com/)
2. Install Shiny package (https://cran.r-project.org/web/packages/shiny/index.html)

# command line
3. install.packages("Shiny")
4. install.packages("Seurat")
5. install.packages("dplyr")
6. if (!requireNamespace("BiocManager", quietly = TRUE))
   install.packages("BiocManager")
   BiocManager::install("monocle", version = "3.8")

7. Download R codes (https://github.com/kimsc77/iMACs/issues/1)

1) Unzip iMACs.zip
2) load iMACs.r

8. Download Dataset (https://github.com/kimsc77/iMACs/issues/2)

9. Run iMACs.r using Rstudio
