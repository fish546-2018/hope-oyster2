
Research Question: Where are SNPs located in samples 1 & 2? Are these located in genes?

Steps: Download data, fastQC, bowtie alignment, SNP calling with mpileup, bedtools intersect, visualization

Repository Structure:

Data: .fq data files for two paired-end samples: sample1A, sample1B, sample2A, sample2B, reference genome, annotated genome

Analyses: fastqc results in html format for each sample (4), oyster reference genome in ebwt format as index for bowtie, reference genome, sorted samples 1 & 2 for SNP calling, samples 1 & 2 SNPs as both bcf and vcf files, text files with the location of SNPs from each sample in relation to the annotated genome, a visualization of the location of each SNP in relation to the annotated genome using IGV

Scripts: scripts for downloading data, running fastQC, aligning using bowtie, calling SNPs with mpileup, downloading the annotated genome, running bedtools intersect




