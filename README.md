# virus-genome-assembly-using-NGS-data
Notes on NGS data analysis: lumpy skin disease virus (lsdv) genome assembly and mutation analysis.

## tools used: 
- [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/). ([on github](https://github.com/s-andrews/FastQC))
- [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic)
- [bowtie2 on github](https://github.com/BenLangmead/bowtie2)
- [samtools](http://www.htslib.org). ([samtools on github](https://github.com/samtools/samtools) and [bcftools on github](https://github.com/samtools/bcftools))
- python and [pyvcf](https://github.com/jamescasbon/PyVCF)
- [Ugene](http://ugene.net)


### analysis data were used in the articles:
1. Complete Genome Sequence of the Lumpy Skin Disease Virus Recovered from the First Outbreak in the Northern Caucasus Region of Russia in 2015
Authors: Alexander Sprygin, Yuriy Babin, Yana Pestova, Svetlana Kononova, Olga Byadovskaya, Aleksandr Kononov. DOI: https://doi.org/10.1128/MRA.01733-18
2. Sprygin A, Babin Y, Pestova Y, Kononova S, Wallace DB, Van Schalkwyk A, et al. (2018) Analysis and insights into recombination signals in lumpy skin disease virus recovered in the field. PLoS ONE 13(12): e0207480. https://doi.org/10.1371/journal.pone.0207480

