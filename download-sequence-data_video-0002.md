# How to download sequence data from online repositories

Example Project ID: **PRJNA857539**

Example SRA ID: **SRR31096354**

## Option-1: Download data from NCBI SRA

Install BBMap
```bash
micromamba install bioconda::bbmap
```
Split an interleaved fastq file
```bash
reformat.sh in=interleaved.fastq.gz out1=Forward.fastq.gz out2=Reverse.fastq.gz
```

