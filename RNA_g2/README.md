# RNA2-seq Pipeline

This project analyzes RNA-seq data. It includes:
- Retreval of data with SRA-tools
- Integrity checks with md5sum
- Preprocessing with Trimmomatic
- Alignment with HISAT2
- Quantification with featureCounts (installed as subreads)

It is recomended to install these programs with conda in a single environment prior to beining to procced
```
conda create -N RNA2-seq
conda activate RNA2-seq
conda install -c bioconda sra-tools
conda install -c bioconda trimmomatic
conda install -c bioconda hisat2
conda install -c bioconda subreads
```



