# TissueMosaic Manuscript

The TissueMosaic package can be installed from here: https://github.com/broadinstitute/TissueMosaic. 

We analyze the following publicly available spatial transcriptomics datasets:

* **Testis**: Chen, H. et al. Dissecting mammalian spermatogenesis using spatial transcriptomics. *Cell Reports* (2021) https://pubmed.ncbi.nlm.nih.gov/34731600/

* **Thymus**: Liu, S. et al. Tissue architecture dynamics underlying immune development and decline in the thymus *bioRxiv* (2025) https://www.biorxiv.org/content/10.1101/2025.06.28.662120v1 

## Download

After cloning this repo, please download and unzip the expected subdirectories which hold intermediate output required to run the notebooks to generate the figures as well as the preprocessed datasets (see citations above). These subdirectories can be downloaded from a publicly available google bucket (see corresponding urls below). 

* https://storage.googleapis.com/tissuemosaic_manuscript/pkls.tar.gz # pkls/
* https://storage.googleapis.com/tissuemosaic_manuscript/benchmarking.tar.gz # benchmarking/
* https://storage.googleapis.com/tissuemosaic_manuscript/model_checkpoints.tar.gz # model_checkpoints/
* https://storage.googleapis.com/tissuemosaic_manuscript/TissueMosaic_output.tar.gz # TissueMosaic_output/
* https://storage.googleapis.com/tissuemosaic_manuscript/TissueMosaic_data.tar.gz # TissueMosaic_data/

The expected directory structure to run all the notebooks is as follows:

## Directory structure

```
TissueMosaic_Manuscript/
├── pkls/ # Directory for intermediate files from long-running notebook steps 
├── benchmarking/ # Directory for benchmarking output 
│   ├── spagcn/
│   └── stagate/
├── model_checkpoints/ # Directory for pre-trained model checkpoints:
│   ├── testis/
│   └── thymus/
├── TissueMosaic_output/ # Directory for TissueMosaic output
│   ├── testis/
│   └── thymus/
├── TissueMosaic_data/  # Directory for TissueMosaic data
│   ├── testis_anndata/
│   └── thymus_anndata/
```
