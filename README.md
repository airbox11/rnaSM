# rnaSL: RNA-Seq Analysis Snakemake Workflow 
rnaSL is a modular, flexible and user-friendly RNA-Seq analysis workflow. 

rnaSL can be applied to both model and non-model organisms. It supports mapping RNA-Seq raw reads to both genome and transcriptome (can be downloaded from public database or can be homemade by users) and it can do both transcript- and gene-level Differential Expression Analysis (DEA) when transcriptome is used as mapping reference. It requires little programming skill for basic use. If you're good at programming, you can do more magic with rnaSL!


## Quick start
### Set up configuration
Modify the metafile describing your data `configs/metadata.tsv`.
Customize the workflow based on your need in `configs/config_main.yaml`.

### Run rnaSL
`python main.py`
