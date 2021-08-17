# GTEx-Networks-For-Senescence

This directory contains the MEGENA co-networks for 32 cancer types from TCGA database.

Author: Peng Xu

Email: peng.xu@mssm.edu

Draft date: Aug 17, 2021

## Description

The co-expression networks for different cancer types were uniformly processed by the MEGENA pipeline. The gene expressions were generated from the normalized RNA-seq data from the TCGA database. 

Four files were shared for the co-expression network results.

Pancancer_meta.tsv: The meta file including sample and patient information for all the samples analyzed

Pancancer_network.tsv: The co-expression networks for all cancers.

Pancancer_bigtable.tsv: The module summary information for all co-expression networks.

Pancancer_module.tsv: The module genes for each co-expression network.

Pancancer_DEG_FDR_0.05_logFC_1.tsv: The differentially expressed genes (DEGs) between tumor and normal samples.

Pancancer_DMC_FDR_0.05_beta_0.2.tsv: The differentially methylated CpGs (DMCs) between tumor and normal samples.

Pancancer_module_cytoband_enrichment.tsv: The network modules enriched with chromosomal cytobands.

Pancancer_module_DEG_enrichment.tsv: The network modules enriched with DEGs.

Pancancer_module_DMC_enrichment.tsv: The network modules enriched with DMCs.


For detailed method information, please refer to the Senescence manuscript and the MEGENA publication (Song W.-M., Zhang B. (2015) Multiscale Embedded Gene Co-expression Network Analysis. PLoS Comput Biol 11(11): e1004574.)

## News

8/17/2021: First version released.

