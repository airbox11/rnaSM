    **************************************
    *                      #####  #     #*
    *#####  #    #   ##   #     # ##   ##*
    *#    # ##   #  #  #  #       # # # #*
    *#    # # #  # #    #  #####  #  #  #*
    *#####  #  # # ######       # #     #*
    *#   #  #   ## #    # #     # #     #*
    *#    # #    # #    #  #####  #     #*
    **************************************


# rnaSL: in-house RNA-Seq Analysis Snakemake Workflow 

rnaSL is a flexible, in-house RNA-Seq analysis workflow. It supports mapping RNA-Seq raw reads to both the genome and transcriptome. When using the transcriptome as the mapping reference, rnaSL performs both transcript- and gene-level Differential Expression Analysis (DEA), facilitating batch processing for my work.

## Quick start
### Set up configuration
Modify the metafile describing your data `configs/metadata.tsv`.
Customize the workflow based on your need in `configs/config_main.yaml`.

### Run rnaSL
`python main.py`
