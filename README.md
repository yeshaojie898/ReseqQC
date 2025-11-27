ReseqQC is a tool that can assess and improve the quality of populational genomic variant datasets, which would facilitate more accurate genotyping and related analyses and applications.
ReseqQC requires five compulsory inputs: the sequence of reference genome (in fasta format), the genome annotation file (in gtf format), the nucleotide diversity calculated from genomic variants (in tsv format) and genomic variants(in vcf format).
There are five options:
--pi   input pi file
--fa   input fasta file
--gtf  input gtf file
--vcf  input vcf file
--w    input 'QC' , 'QCFA' or 'QCFA-e'
'QC' , 'QCFA' or 'QCFA-e'
QC, QCFA, and QCFA-E correspond to three distinct operational modes. Specifically, QC denotes data quality assessment, while QCFA and QCFA-E are designated for VCF files with VQSR features and those without VQSR features, respectively.
