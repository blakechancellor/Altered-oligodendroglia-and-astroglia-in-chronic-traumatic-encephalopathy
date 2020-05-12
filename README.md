# Altered-oligodendroglia-and-astroglia-in-chronic-traumatic-encephalopathy
All code used for this manuscript. 

main_script includes all the code used in R to perform computational analysis for this manuscript. All pre-processing, 
i.e., sequencing reads to count matrices, was performed following the "Pipeline for processing inDrops sequencing data" 
(https://github.com/indrops/indrops). 

Table of Contents for main_script;
Lines 1-275: Reads inDrops matrices into R and prepare them for Seurat. 

Lines 276-315: Builds Seurat objects for Control and CTE, then creates an integrated Seurat object. 

Lines 316-383: Performs scaline and dimensionality reduction on integrated object, as well as initial visualize. 

Lines 384-432: Subsets each celltype to create new tSNE projections. 

Lines 433-465: Code to produce Figure 1 and Supplementary Figure 1. 

Lines 466-485: Code to produce Figure 2 and Supplementary Figure 4a. 

Lines 486-502: Code to produce Figure 3.

Lines 503-524: Code to produce Figure 4 and Supplementary Figure 6a. 

Lines 525-538: Code to produce Supplementary Table 2. 

Lines 539-602: Code to produce Supplementary Table 3. 

Lines 603-720: Code to produce Supplementary Table 4. 

Lines 721-728: Code to produce Supplementary Table 5. 

Lines 729-740: Code to produce Supplementary Table 6.
