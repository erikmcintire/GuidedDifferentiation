# GuidedDifferentiation

Code used in the analysis of data generated from scRNA-seq of guided differentiation cell cultures.  
  
The analysis folder contains 3 separate R Markdown files:  
  
1. Manual_cell_annotation.Rmd: Manual annotation of guided differentiation cell cultures using Seurat. This code produces Fig. 1B and 1C, as well as Extended Figures 2 through 5.  
2. Timecourse_integration.Rmd: Seurat integration of a 16-day iPSC-CM differentiation time-course dataset published by Elorbany et al. (2022), and the guided differentiation dataset. This code produces Fig. 2.  
3. In_vivo_reference.Rmd: Automated annotation of cells from guided differentiation cell cultures, mature multilineage organoids published by Silva, et al. (2021), and a PBMC dataset from 10x Genomics. Automated annotation was performed using the scPred prediction model trained on annotated fetal heart cells published by Miao et al. (2020). This code produces Fig. 3A, 3C, and 3D.
