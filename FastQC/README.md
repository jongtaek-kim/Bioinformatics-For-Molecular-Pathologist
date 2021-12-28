
## Quality Control with FastQC Program.
```bash
$ fastqc fastqfile
```
&nbsp; 

## Run with real data
```bash
$ fastqc Small_R1.fastq Small_R2.fastq
```
&nbsp; 

## Open html files to view the results
### Quality Phred Scores Across All Bases
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/per_base_quality.png">
</p>

### Per Sequence Quality Score Distribution
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/per_sequence_quality.png">
</p>

### Per Sequence GC Content
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/per_sequence_gc_content.png">
</p>

### Distribution of Sequence Lengths Over All Sequences
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/sequence_length_distribution.png">
</p>

### Per Base Sequence Content Across All Bases
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/per_base_sequence_content.png">
</p>

### Duplication Levels
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/duplication_levels.png">
</p>

### Adapter Content
<p align="center">
  <img width="800" height="600" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/e46565d32538089d1539e939478fd43beec87bca/docs/images/adapter_content.png">
</p>

## You may also remove lower quality reads and shorter fragments with trimmomatic.
```bash
$ trimmomatic SE fastqfile trimmed_fastqfile SLIDINGWINDOW:4:22 MINLEN:100
```
&nbsp; 

## Run with real data.
```bash
$ trimmomatic SE Small_R1.fastq trimmed_Small_R1.fastq SLIDINGWINDOW:4:22 MINLEN:100
TrimmomaticSE: Started with arguments:
 Small_R1.fastq trimmed_Small_R1.fastq SLIDINGWINDOW:4:22 MINLEN:100
Automatically using 4 threads
Quality encoding detected as phred33
Input Reads: 364744 Surviving: 296810 (81.37%) Dropped: 67934 (18.63%)
TrimmomaticSE: Completed successfully
```
&nbsp; 



