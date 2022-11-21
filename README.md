# PhD-Thesis - Bioengineering program (IST)

## Computational Biology for Modeling Oncological Omics Data: the way towards personalized medicine

<b> Supervisor: </b> Prof. Susana de Almeida Mendes Vinga Martins (INESC-ID)

<b> Co-supervisor: </b> Prof. Luís António Marques da Costa (iMM / Hospital de Santa Maria)

## Abstract

Cancer is consider a very heterogeneous disease. Different subtypes may show distinct clinical and genomic characteristics, posing great challenges for both diagnosis and cancer therapy. To understand the molecular mechanisms that underlie cancer formation, studying patient omics (such as gene expression profiles) and clinical data using high-throughput techniques together with computational biology tools are needed to reach a more personalized medicine. 
During the past years, there was a rising of genome sequencing techniques, allowing us to have more molecular information on patients, improving the accuracy with which they may be categorized and treated. One of the challenges of analyzing transcriptomic data is the high-dimensionality, i.e., the number of genes (p), is typically larger than the number of patients (N). This usually poses many challenges on parameter estimation and causes instability on selected features. Nowadays, techniques such as the inclusion of additional constraints to the parameter optimization problem, are used to handle this dimensionality problem. Some examples are algorithms based on the Lasso, Ridge or Elastic Net penalization and network-based regularization. The estimation of accurate models using high-throughput data is expected to support the identification of biomarkers associated with given disease outcome, which will have a strong impact in personalizing healthcare. 

The goal of this project was to develop clinical decision support systems for personalized medicine. Studying cancer transcriptomic and clinical data will allow a more in-depth knowledge on the cancer biology, and the identification of diagnostic and therapeutic markers that will, ultimately, improve patient outcomes.

Colorectal (CRC) and kidney cancer (RCC) data obtained from TCGA (The Cancer Genome Atlas) database and from Hospital de Santa Maria were analyzed. Different computational tools for survival analysis and classification problems were used. We propose TCox, a novel penalization function for Cox models, which promotes the selection of genes that have distinct correlation patterns in normal vs. tumor tissues; and also iTwiner, to select biomarker signatures that show different correlation patterns between the metastatic vs. non-metastatic early-stage CRC patients. Several putative biomarkers were found using these methods and further investigated using gene set enrichment analysis. 

This work demonstrates the ability of weighted regularization to disclose novel molecular drivers in both CRC and RCC survival, supporting the relevance of network information for biomarker identification in high-dimensional gene expression data and foster new directions for the development of network-based feature selection methods in precision oncology. Also, we demonstrate that classification of CRC patients based on pre-selected features by regularized logistic regression is a valuable alternative to using DEGs, significantly increasing the models’ predictive performance. Moreover, the use of correlation-based penalization for biomarker selection stands as a promising strategy in predicting patients group based on RNA-Seq data.

Overall, this work allowed to better understand cancer genomics and find key biomarkers involved in cancer formation and progression, playing an important role towards a more precise cancer management.

## Outline

![outilelast](https://user-images.githubusercontent.com/45852638/203018243-97875e75-b770-4f58-a87d-122101b60bd4.png)


