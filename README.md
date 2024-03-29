# scRNA-seq of IL10-expressing CAR-T cells

This repo contains scripts to analyse single-cell sequencing data of HER2 CAR-T cells engineered to express interleukin IL10 - from the work by Yang Zhao et al. *Nature Biotechnology* 2023 (in press)

Main scripts:
* [Unsupervised analysis](https://github.com/carmonalab/LiTang_IL10_CART/blob/master/unsupervised_analysis_CART.Rmd): compare transcriptome of HER2-specific IL10-expressing CAR-T cells to HER2 CAR-T cells without the IL10-expressing construct.
* [Reference-based analysis](https://github.com/carmonalab/LiTang_IL10_CART/blob/master/projection_analysis_CART.Rmd): use a reference TIL map and the ProjecTILs method to characterize IL10-HER2-CAR-T cells vs. HER2-CAR-T cells
* [Analysis of splenic CAR-T cells](https://github.com/carmonalab/LiTang_IL10_CART/blob/master/splenic_CART.Rmd): characterize the transcriptomics state of HER2 CAR-T cells isolated from murine spleen 
* [Human CAR-T](https://github.com/carmonalab/LiTang_IL10_CART/blob/master/human_NSG_CART.Rmd) and [Human CD8 CAR-T](https://github.com/carmonalab/LiTang_IL10_CART/blob/master/human_NSG_CART_CD8.Rmd): analysis of human CAR-T cells sorted from cured NSG mice. 