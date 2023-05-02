# IRIS-HEP-Summer-2022-Bioinfomatics-project
This file was created this summer, when i was a part of the IRIS-HEP Programm internship. This is RMarkdown file. First few steps were made using Bash, after that it was made in R.

In this project, we analyzed the effect of over-expression of myocardin on other genes in smooth muscle cells (SMC) from the human coronary artery using the RNA-Seq method.
SMC were treated with adenoviruses that expressed nothing (control group) or over-expressed myocardin (treatment group). There were 4 virus induced and 4 control samples. 
RNA was extracted from these cells and sequenced with paired-end reads on an illumina machine. 
We compared these two groups to find a list of genes that show differential expression and predicted the functional role of these affected genes.

We will used fastQC and multiQC for sequence quality control. 
For quantification of the transcripts, we used Salmon that performs read mapping to a human genome and counting reads corresponding to specific genes.
This process gave us raw count data that was be analyzed for differential gene expression signals using DESeq2.
At the end, we used WebGestaltR for functional analysis of the differentially expressed genes.

In the file provided you could see the code used in quantification of the thanscripts that were made in Bash command line and the first part of functional analysis, that was made in R language. 
