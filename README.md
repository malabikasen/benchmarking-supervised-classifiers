# benchmarking-supervised-classifiers
Performance of Supervised Classifiers on Mouse Cell Atlas single-cell RNA  Sequencing Data for Cell Annotation


Cell type identification is a key component of any downstream analysis of sc-RNA seq data (Luecken and Theis, 2019). Identifying cell types can provide
valuable information on emergence of new cell types and lineage tracing for known cell types (Svensson, Vento-Tormo and Teichmann, 2018). Commonly, cell
type identification is achieved either through manual annotation, automated unsupervised clustering or supervised classification. 

There has been a significant amount of algorithms developed for automatic cell type identification given the cumbersome nature of manual annotation. Based on a survey of 22 such classification algorithms (Abdelaal et al., 2019), and brief research on automated clustering methods we believe there is room for improvement. Despite the vast number of datasets (27) used to measure annotation accuracy, Abdelaal et. al.’s analysis lacks testing on a truly diverse dataset like that of the Mouse Cell Atlas (Han et al., 2018). 


In light of these shortcomings with the individual cell type identification methods and validation datasets, we will study the effects of the top performing supervised cell type annotation methods on the Mouse Cell Atlas (MCA) Dataset by Han et. al.


This project benchmarks 2 supervised classifiers viz. SVM and ACTINN on the MCA dataset.


The link to the whole report can be found (here)[https://github.com/malabikasen/benchmarking-supervised-classifiers/blob/main/CS_5854__Final_Project_Report.pdf].
