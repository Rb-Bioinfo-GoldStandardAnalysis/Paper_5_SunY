# Paper_5_SunY
Sun, Y,, Wang, X,, Zhang, D,Y, et al, Brain-wide neuronal circuit connectome of human glioblastoma, Nature (2025), https://doi,org/10,1038/s41586-025-08634-7

# Data availability
Raw and processed single-cell and bulk RNA-seq data reported in this study are available at the NCBI Gene Expression Omnibus under accession numbers GSE274460 and GSE274633. Patient sample information is listed in Supplementary Table 1, and primer sequences are listed in Supplementary Table 2. The human reference genome (GRCh38 v.41) is available at https://www.gencodegenes.org/human/release_41.html. The scRNA-seq data in Fig. 1 and Extended Data Fig. 1 are available from https://singlecell.broadinstitute.org/single_cell/study/SCP393/single-cell-rna-seq-of-adult-and-pediatric-glioblastoma#study-download, GSE174554, and GSE84465. Source data are provided with this paper.

# Code availability
Absent

# Versions
Statistical analyses were conducted in R v4.3.1. All image analysis for Carl Zeiss (.CZI) raw confocal images were imported into ImageJ/FIJI v2.1.0 for further analysis and pre-processing, and data were imported into R v4.3.1 for additional analysis and visualization. For bioinformatic analyses, standard pipelines in R v4.3.1 (via RStudio) were employed, using the following packages: Seurat v4.4.0, HoneyBADGER v0.1, DESeq2 v1.40.2, dittoSeq v1.12.2, UCell v2.4.0, GSVA v1.48.3, ggpubr v0.6.0, sctransform v0.4.1, rstatix v0.7.2, harmony v1.1.0, UpSetR v.1.4.0, and survminer (v0.4.9). The 'get.sig.scores' function to obtain GBM cell state annotations were adapted from LeBlanc et al., Cancer Cell 2022 (https://github.com/vleblanc/GBM-PDE-paper/blob/main/scRNA_seq/funcs_analysis.R). GO analyses were performed via overrepresentation test as implemented in pantherdb.org (PANTHER v18.0). No original software or algorithms were developed in the current study.
