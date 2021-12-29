## A) Variant Calling [(Secondary Analysis With GATK Best Practices).](https://gatk.broadinstitute.org/hc/en-us)

<p align="center">
  <img width="865" height="570" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/17933481f55b0544350693bbf6cfc0cc2453214a/docs/images/variantcall.png">
</p>

## B) Seconday Analysis with GATK Best Practices.

<p align="center">
  <img width="872" height="501" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/d0440c17f19f726acd780e77c6825f7ba04981ec/docs/images/Best_Practice.png">
</p>

## C) Variant Calling with Parameters Set.
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
