# warming_AK
pipeline for RNA-seq of soil 
README 

Adriana L. Romero-Olivares' protocol for processing RNAseq data of soil 


This pipeline is divided in 8 sections. Each section has a filename and a step 



Section 1

File name: 1_clean_trim_QC 

Step: Cleaning-trimming-fastQC of raw reads



Section 2

File name: 2_sortmeRNA

Step: Preparing files for assembly with Trinity 



Section 3

File name: 3_assembly_de_novo

Step: Assembly with Trinity 



Section 4

File name: 4_align_bowtie2 

Step: Alignment of reads with bowtie2 

Section 5 
File name: 5_quant_express
Step: Quantification of reads 

Section 6
File name: 6_diff_expresion 
Step: Differential expression analysis 

Section 7 
File name: 7_annotate_metatranscriptome 
Step: Annotate meta-transcriptome 

Section 8 
File name: 8_create_annotated_metatranscriptome 
Step: Create annotated meta-transcriptome 

