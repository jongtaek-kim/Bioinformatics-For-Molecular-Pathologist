## A) Variant Calling [(Secondary Analysis With GATK Best Practices).](https://gatk.broadinstitute.org/hc/en-us)

<p align="center">
  <img width="865" height="570" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/17933481f55b0544350693bbf6cfc0cc2453214a/docs/images/variantcall.png">
</p>

<p align="center">
  <img width="872" height="501" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/2cadd7d5587027e943e3730669fc38d57385cc43/docs/images/Variant_Call_Best_Practices.png">
</p>

## Quality Control with FastQC Program.
```bash
$  java -jar $GATK \
        -T MuTect2 \
        -I:tumor hcc1143_N_subset50k.bam \
        --dbsnp dbSNP142_GRCh38_subset50k.vcf.gz \
        --artifact_detection_mode \
        -o 1_normalforpon.vcf.gz \
        -L chr6:33,413,000-118,315,000 \
        -R ~/Documents/ref/hg38/Homo_sapiens_assembly38.fasta
```
&nbsp; 
