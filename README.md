# Lung Organoid Data Analysis

The processed gene expression data can be downloaded from: 

    https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE106850

where sample data files included are:
    
    lung1.tar.gz
    lung2.tar.gz
    lung3.tar.gz
    pure_at2.tar.gz

Analyzing these data sets are more convenient because multiple libraries for 
each samples are merged. In addition, both the umi count data and the cell-size 
normalized log-transformed gene expression data are available. 
To access this data, one can directly utilize load expression data from the 
respective folders (`merged_umi/` or `merged_umi_log`). The data is consistent 
with the 10x standard output for gene expression data 
(`barcodes.tsv` , `features.tsv`, `  matrix.mtx`). 

Finally, each data folder also includes a meta information file for the 
cells within `analysis_res.tsv`. Each row corresponds to a cell with its 
10x barcode, and the columns include t-SNE projection and cluster labels that 
we obtained from the standard Seurat pipeline. One can use them directly for 
data visualization.

With all of these data resources, one can directly re-analyze and visualize 
the data, or perform differential gene expression analysis without having to 
install Seurat or other 10x specific data analysis tools. 
For example, the html files for each sample include our customized analyses 
for our manuscript: 

    Lung1_Analysis.html  
    Lung2_Analysis.html  
    Lung3_Analysis.html  
    PurifiedAT2_Analysis.html

with helper code provided in src.tar.gz.  
One can freely re-use our code or build more customized code around it. 
