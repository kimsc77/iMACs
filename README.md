# Single-cell RNA-seq of human embryonic stem cell derived macrophage reveals distinct macrophage population

Macrophages exhibit high plasticity to achieve their roles in maintaining tissue homeostasis,
innate immunity, tissue repair and regeneration. Therefore, macrophages are target
candidates for a wide spectrum of therapeutic applications, including cell-based therapy.
Therapeutic application of blood monocyte- or bone marrow-derived macrophages is
hindered due to inadequate numbers and cellular heterogeneity. In contrast, pluripotent stem
cell (PSC)-derived macrophages serve as an alternative source of macrophages; however,
the inefficiency of available techniques in producing scalable, reproducible, homogenous
macrophages remains a major limitation for therapeutic usage. Thus, we have developed a
technique to produce embryonic stem cell-derived macrophages referred to as iMACs
amenable for scale-up. The current study presents a large-scale transcriptome dataset of
2,931 highly pure iMACs obtained by single-cell RNA sequencing. This dataset provides a
valuable genomic profile for understanding the molecular characteristics of PSC-derived
macrophage cells and uncovers cellular homogeneity

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

7. Download Dataset 
   1) https://github.com/kimsc77/iMACs/issues/1
   2) https://sites.google.com/site/computationalbiostatistics/data-sets

(1) Unzip iMACs.zip & CMC3.zip
- matrix.mtx
- barcodes.tsv
- genes.tsv

8. Download R-code (https://github.com/kimsc77/iMACs/issues/2)

(1) Unzip R_codes.zip 
- macropahge_scRNAseq.r
- ILoReg_iMAC.r

9. Run macropahge_scRNAseq.r & ILoReg_iMAC.r using Rstudio
