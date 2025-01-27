# rnaSL: in-house RNA-Seq Analysis Snakemake Workflow 
rnaSL is a modular in-house RNA-Seq analysis workflow. 

rnaSL supports mapping RNA-Seq raw reads to both genome and transcriptome and do both transcript- and gene-level Differential Expression Analysis (DEA) when transcriptome is used as mapping reference for batch processing in my work.


## Quick start
### Set up configuration
Modify the metafile describing your data `configs/metadata.tsv`.
Customize the workflow based on your need in `configs/config_main.yaml`.

### Run rnaSL
`python main.py`
