# Identification of biomarkers predictive of metastasis development in early-stage colorectal cancer using network-based regularization

<i> Carolina Peixoto, Marta B. Lopes, Marta Martins, Sandra Casimiro, Daniel Sobral, Ana Rita Grosso, Catarina Abreu, DanielaMacedo, Ana Lúcia Costa, Helena Pais, Cecília Alvim, André Mansinho, Pedro Filipe, Pedro Marques da Costa, Afonso Fernandes, Paula Borralho, Cristina Ferreira, João Malaquias, António Quintela, Shannon Kaplan, Mahdi Golkaram, Michael Salmans, Nafeesa Khan, Raakhee Vijayaraghavan, Shile Zhang, Traci Pawlowski, Jim Godsey, Alex So, Li Liu, Luís Costa, Susana Vinga </i>

Submitted to BMC Bioinformatics (15 March 2022). Under Review.

## Highlights 

-Identification of early-stage CRC patients (stages II-III) likely to develop metastasis

-Identification of genes correlated with metastasis development using supervised learning with network informa-tion

-iTwiner, based on correlation matrices, lead to the best model performance selecting the most stable and robustgene sets

-Classifiers based on the genes pre-selected by regularized logistic regression shown better performance thanthose that use DEGs

## Data
Two cohorts of CRC patients from Hospital Santa Maria (Lisbon, Portugal): 
1) 102 CRC primary and metastatic patients, described in paper Sobral et al., will be available after publishing (accession number EGAD00001007686 - EGA) - https://ega-archive.org/search-results.php?query=EGAD00001007686; 
2) 114 CRC primary patients described in Golkaram, Mahdi, et al.[1], available in NCBI Database (accession number PRJNA689313) - https://www.ncbi.nlm.nih.gov/bioproject/PRJNA689313.


[1] Golkaram, Mahdi, et al. "HERVs establish a distinct molecular subtype in stage II/III colorectal cancer with poor outcome." NPJ genomic medicine 6.1 (2021): 1-11.


## Abstract

Colorectal cancer (CRC) is the third most common cancer and the second most deathly worldwide. It is a very heterogeneous disease that can develop via distinct pathways where metastasis is the primary cause of death. Therefore, it is crucial to understand the molecular mechanisms underlying metastasis. RNA-sequencing is an essential tool used for studying the transcriptional landscape. However, the high-dimensionality of gene expression data makes selecting novel metastatic biomarkers problematic. 

To distinguish early-stage CRC patients at risk of developing metastasis from those that are not, three types of binary classification approaches were used: 1) classification methods (decision trees, linear and radial kernel support vector machines, logistic regression, and random forest) using differentially expressed genes (DEGs) as input features; 2) regularized logistic regression based on the Elastic Net penalty and the proposed iTwiner - a network-based regularizer accounting for gene correlation information; and 3) classification methods based on the genes pre-selected using regularized logistic regression.

Classifiers using the DEGs as features showed similar results, with random forest showing the highest accuracy. Using regularized logistic regression on the full dataset yielded no improvement in the methods' accuracy. 
Further classification using the pre-selected genes found by different penalty factors, instead of the DEGs, significantly improved the accuracy of the binary classifiers. Moreover, the use of network-based correlation information (iTwiner) for gene selection produced the best classification results and the identification of more stable and robust gene sets. 
Some are known to be tumor suppressor genes (OPCML-IT2), to be related to resistance to cancer therapies (RAC1P3) or to be involved in several cancer processes such as genome stability (XRCC6P2), tumor growth and metastasis (MIR602) and regulation of gene transcription (NME2P2).

We show that the classification of CRC patients based on pre-selected features by regularized logistic regression is a valuable alternative to using DEGs, significantly increasing the models’ predictive performance. Moreover, the use of correlation-based penalization for biomarker selection stands as a promising strategy in predicting patients group based on RNA-seq data.
