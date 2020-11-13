# Lung Organoid Data Analysis

The purpose of this repository is to provide customized code written by Junjie Zhu used in the single cell RNA-seq analysis for the manuscript:

<a href="https://www.biorxiv.org/content/10.1101/2020.07.27.212076v1"> Progenitor identification and SARS-CoV-2 infection in long-term human distal lung organoid cultures</a> 

The processed gene expression data can be downloaded from: 

    https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE106850

where sample data files included are:
    
    GSM2855474	Lung_1_1
    GSM2855475	Lung_1_2
    GSM2855476	Lung_1_3
    GSM2855477	Lung_1_4
    GSM2855478	Lung_2_1
    GSM2855479	Lung_2_2
    GSM2855480	Lung_2_3
    GSM2855481	Lung_2_4
    GSM2855482	Lung_3_1
    GSM2855483	Lung_3_2
    GSM2855484	Lung_3_3
    GSM2855485	Purified_AT2

In addition, both the umi count data and the cell-size 
normalized log-transformed gene expression data are available. 
The data are consistent with the 10x standard output for gene expression data 
(`barcodes.tsv` , `features.tsv`, `matrix.mtx`). 


The html files for each sample include customized analyses written by Junjie Zhu 
for our manuscript: 

    Lung1_Analysis.html  
    Lung2_Analysis.html  
    Lung3_Analysis.html  
    PurifiedAT2_Analysis.html

with helper code provided in src.tar.gz.  
