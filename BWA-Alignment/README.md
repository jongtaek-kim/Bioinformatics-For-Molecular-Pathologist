## Aligment with [BWA.](http://bio-bwa.sourceforge.net/)
```bash
$ bwa mem ref.fa read1.fq read2.fq > sample1.sam
```
&nbsp; 

<p align="center">
  <img width="1022" height="586" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/3c3ed130236a806ef2510ff6fe2a3f3e72c6eb1f/docs/images/BWA1.png">
</p>

## Run with real data and human reference genome which creates SAM file.
```bash
$ bwa mem hg19.fa Small_R1.fastq Small_R2.fastq > Aligned-pe.sam
[main] Version: 0.7.17-r1188
[main] CMD: bwa mem hg19.fa Small_R1.fastq Small_R2.fastq
[main] Real time: 188.283 sec; CPU: 186.328 sec
```
&nbsp; 

## Convert SAM file to BAM file for downstream analysis.
```bash
$ samtools view -Sb Aligned-pe.sam > Aligned-pe.bam
```
&nbsp; 

## Get Mapping Statistics On Bam File.
```bash
$ samtools flagstat Aligned-pe.bam
```
&nbsp; 
