# Altered-oligodendroglia-and-astroglia-in-chronic-traumatic-encephalopathy
All code used for the manuscript: Chancellor, et al., 2020, Altered oligodendroglia and astroglia in chronic traumatic encephalopathy, bioRxiv. 

Load_Data includes the steps to load counts produced by the inDrops pipeline ("Pipeline for processing inDrops sequencing data" 
(https://github.com/indrops/indrops)) into R. 

Create_Objects converts counts into a single, integrated Seurat object.

Process_Objects performs dimensionality reduction for the primary tSNE with all nuclei and each subset tSNE for each cell type. 

Produce_Figures provides all the code used to produce each figure panel that includes single-nucleus RNA sequencing analysis. 
