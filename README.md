# Bioinformatics-For-Molecular-Pathologist 
Lecture and Tutorial Created For Molecular Oncology Rotation at the University of Utah/ARUP Laboratories



## 1. What Is Bioinformatics?
### Bioinformatics is an intersection between biological data (like DNA sequence) and computer programming (software).

<p align="center">
  <img width="1100" height="425" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/d9dfdcf549ae117579a61f6c96ddfbe811c83b4c/docs/images/Bioinformatics%20diagram.png">
</p>

## Bioinformatics and Next Generation Sequencing Overview

<p align="center">
  <img width="1240" height="470" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/d9dfdcf549ae117579a61f6c96ddfbe811c83b4c/docs/images/workflow.png">
</p>


### *Click [here](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/Understanding-Bioinformatics-NGS) for a bioinformatics lecture.
### *Rest of this web page below is for NGS and Bioinformatics Tutorial.

## 2 Setting Up Your Computer For NGS Tutorial
### Install Miniconda which contains the conda package manager.
### Once Miniconda is installed, you can use the conda command to install any other packages such as FastQC, Trimmomatic, BWA, SAMtools, GATK, etc.

### *Click here for complete instructions [(Setting Up)](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/Setting-Up-Your-Computer)

## 3. Introduction To The Command Line.
### Learn basic UNIX command-line coding (Needed later to perform quality control, align reads to a reference genome, and annotate variants).
### *Click here for complete instructions [(Command Line Tutorials)](Command-Line-Coding/README.md)

## 4. FastQC: Qualirty Control Of Sequence Reads
### [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) is a quality control tool for high throughput sequence data such as next generation sequencing.
<p align="center">
  <img width="700" height="500" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/4a407669119ac2622aad424d5113e981d6e7ced7/docs/images/fastqc.png">
</p>

### [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic) is flexible read trimming tool you can use to remove bad quality reads and perform adaptor clipping.


### *Click here to learn more about primary analysis with [FastQC](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/FastQC) and [Trimmomatics.](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/FastQC)



## 5. Alignment To The Reference Genome (SAM/BAM)

### [BWA](http://bio-bwa.sourceforge.net/) is a software package for mapping low-divergent sequences against a large reference genome, such as the human genome. 

<p align="center">
  <img width="1022" height="586" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/3c3ed130236a806ef2510ff6fe2a3f3e72c6eb1f/docs/images/BWA1.png">
</p>

### *Click here to learn more about secondary analysis with [BWA.](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/BWA-Alignment)

## 6. Variant Calling [(Secondary Analysis With GATK Best Practices).](https://gatk.broadinstitute.org/hc/en-us)

<p align="center">
  <img width="865" height="570" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/17933481f55b0544350693bbf6cfc0cc2453214a/docs/images/variantcall.png">
</p>

### *Click here to learn more about variant calling and secondary analysis with [GATK Best Practices.](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/Variant-Calling-GATK)



## 7. Tertiary Analysis: Interpretation of Somatic Variants in VCF File.

<p align="center">
  <img width="1024" height="428" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/c4a43ebdc86d52fe523fdb2f596858a2b8539409/docs/images/vcf.png">
</p>

### Somatic Variant Classification Using 4 TIER System [(Speical Article Standards and Guidelines for the Interpretation and Reproting of Sequence Variants in Cancer By AMP, ASCO, CAP)](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/f990c21e9c0f9f7cc1fc3103f8a566e7e23954b5/docs/files/2017%20Marilyn%20Li%20Standards%20and%20guidelines%20for%20the%20interpretation%20and%20reporting%20of%20sequence%20variants%20in%20cancer%20JMD.pdf)

<p align="center">
  <img width="1069" height="586" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/2098079a3c7deb9fba59ebe651533b22ac03109f/docs/images/Tier4.jpg">
</p>


## 8. Review of Variant Classification Databases and Variant Annotation Resources
### Variant interpretation is a challenge for many molecular pathology laboratories. 
<p align="center">
  <img width="586" height="366" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/bd97198a61fb49f50ed13a410022da445e100296/docs/images/ngsinterpretation2.png">
</p>

### We will go over databases and annotation resources geared towards molecular pathology laboratories [here.](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/Variant-Classification)





