# Bulk-RNAseq
This is a Bulk RNA-seq analysis that was carried in collaboration with @ErikBot9.  
The DE analysis was performed through the edgeR package, while the expression data belonging to each replicate was taken from the recount3 package. 

## SHORT DESCRIPTION

The purpose of the task was detecting differential gene expression across three different human tissues: brain, liver and lung. Three replicates were selected for each tissue, according to specific quality parameters that are explained in the commented R markdown. 

We repeated the analysis both considering (Full data) and removing non canonical chromosomes, mtRNA, rRNA and pseudogenes (Canonical chromosomes).

In particular, results were obtained by employing a generalized linear model and by designing a contrast matrix to detect the genes overexpressed in each tissue versus the other two. 

After obtaining differential expression results both from full and filtered data, a functional enrichment analysis was performed to identify the most relevant functional annotations (Gene Ontology terms - https://maayanlab.cloud/Enrichr/) related to the overexpressed genes. 

## RESULTS 

We conclude that we were able to find differentially expressed genes between the three different tissues, and that the filtering of the dataset did not affect too much the results.
The biological annotations showed that the differentially expressed genes that we found have functions that are specific for the tissue of belonging.



