# single-cell-sequencing-Technology
- What is single cell technology and how to separate the individual cell from a group of cells
- Applications of SCT in cancer, immunology, neurology, reproduction, basic and clinical research
- Why is the need for studying single cell RNA seq( to look at gene expressions of PBMCs)
- What is the difference between bulk RNA seq and single cell RNA seq?
- How do you isolate individual cells?
- Steps in SCT- sample preparation and sequencing; sequence alignment and sequence count; data normalization and gene expression(quality control and filtering, normalization, expression by cells, dimensionality reduction amd call clustering); downstream analysis(differential expression etc)
- Unbiased profiling
- Single cell resolution which reveals cellular diversity, identifies rare cell types and uncovers dynamic gene expression patterns
- Distinguishing the isolated individual cells by tagging a unique molecular identifier to the cell?
- How does SC RNA-Seq work?
- Challenges associated with SC RNA -Seq include cell capture effiency, amplification bias, sequencing depth, requires high dimensional data analysis. batch effects and high computational requirements, poor library quality
- Quality control, clustering and annotation, differential gene expression,
- How to calculate sample size?
- To download fastq files using SRA toolkit(fastq-dump)
``` bash 
 fastq-dump -X 3 SRR11537950 --stdout
```
- cell thawing
- pipette tip recommendation for single cell assays
- quality control and exploratory analysis
- Filtering cells based on technical and biological parameters(nCount_RNA, nFeature_RNA, percent_mitochondria)
- Normalization of gene expression within a cell
- Clustering and why do we cluster cells
- Dimensionality reduction
- Graph based clustering
- How to visualize cells in lower dimension
- 
