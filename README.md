# Polio Pathan

Polio-Pathan is a Nextflow pipeline for polio virus NGS analysis and phylogenetics. It takes input FASTQ files and a reference genome, and produces output BAM, VCF, and phylogenetic tree files.

## Installation

To install Polio-Pathan, you will need to have Nextflow installed. You can install Nextflow using the following command:

```
conda install -c bioconda nextflow
```

Once Nextflow is installed, you can clone the Polio-Pathan repository and run the pipeline using the following commands:

```
git clone https://github.com/aysanraza/polio-pathan.git
cd polio-pathan
nextflow run pipeline.nf
```

## Usage

To run the Polio-Pathan pipeline, you will need to specify the input and output files on the command line. You can do this using the following arguments:

* `--input1`: The path to the input FASTQ file.
* `--ref`: The path to the reference genome.
* `--output_bam`: The path to the output BAM file.
* `--output_vcf`: The path to the output VCF file.
* `--output_tree`: The path to the output phylogenetic tree file.

For example, to run the pipeline with the following input and output files:

* `input1.fastq.gz`
* `ref.fa`
* `output.bam`
* `output.vcf`
* `output.tree`

You would use the following command:


`nextflow run pipeline.nf --input1 input1.fastq.gz --ref ref.fa --output_bam output.bam --output_vcf output.vcf --output_tree output.tree`


Once the pipeline has finished running, you will find the output BAM, VCF, and phylogenetic tree files in the directory where you executed the command.

## About Me:

I am a Bioinformatics and Machine learning expert, practecing insilico development and analytics in the domain of biology and medicine. I am open for research collaborations, you can email me to discuss.

Thank you,
```
Ahsan Raza

Masters in Bioinformatics

aysanraza@gmail.com

Islamabad, Pakistan.
```

## 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) 	![Neo4J](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![GIT](https://img.shields.io/badge/Git-fc6d26?style=for-the-badge&logo=git&logoColor=white) ![LINUX](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

 ## 💰 You can help me by Donating
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/https://www.buymeacoffee.com/aysanraza)
