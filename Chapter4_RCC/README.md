# Kidney cancer biomarker selection using regularized survival models

<i> Carolina Peixoto, Marta Martins, Luís Costa and Susana Vinga (2022). </i>

Submitted to Cells special issue - Translational Oncobiology: From Molecular Mechanisms to Targeted Therapies.

## Abstract

Clear cell renal cell carcinoma (ccRCC) is the most common subtype of RCC showing significant percentage of mortality. One of the priorities of kidney cancer research is to identify RCC-specific biomarkers for early detection and screening of the disease. 

With the development of high-throughput technology it is now possible to measure the expression levels of thousands of genes in parallel and assess the molecular profile of individual tumors. Studying the relationship between gene expression and survival outcome has been widely used to find genes associated to cancer survival, providing new information for clinical decision-making. One of the challenges of using transcriptomics data is their high-dimensionality that can lead to instability on the selection of genes signatures. 

Here we identify potential prognostic biomarkers correlated to survival outcome of ccRCC patients using two network-based regularizers (EN and TCox) applied to Cox models. Some genes always selected by each method were found (<i>COPS7B, DONSON, GTF2E2, HAUS8, PRH2, ZNF18</i>) with known roles in cancer formation and progression. Afterwards, different lists of genes ranked based on distinct metrics (logFC of DEGs or beta coefficients of regression) were analyzed using GSEA to try to find over- or under-represented mechanisms and pathways. Some ontologies were found in common between the gene sets tested, such as nuclear division, microtubule and tubulin binding and plasm membrane and chromosome regions.

Additionally, genes that were more involved in these ontologies and genes selected by the regularizers were used to create a new gene set where we applied Cox regression model. With this smaller gene set we were able to split significantly patients in high/low risk groups showing the importance of studying these genes as potential prognostic factors to help clinicians better identifying and monitoring patients with ccRCC.
