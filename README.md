# TissueMosaic Manuscript

The TissueMosaic package can be installed from here: https://github.com/broadinstitute/TissueMosaic. 

After cloning the repo, please create the expected subdirectories to hold intermediate output required to run the notebooks to generate the Figures. These intermediate files can be downloaded from a publicly available google bucket (see corresponding urls below). The expected directory structure to run all the notebooks is as follows:

## Directory structure

```
TissueMosaic_Manuscript/
├── pkls/ # Directory for intermediate files from long-running notebook steps: https://storage.googleapis.com/tissuemosaic_manuscript/pkls.tar.gz
├── benchmarking/ # Directory for benchmarking output: https://storage.googleapis.com/tissuemosaic_manuscript/benchmarking.tar.gz
│   ├── spagcn/
│   └── stagate/
├── model_checkpoints/ # Directory for pre-trained model checkpoints:  https://storage.googleapis.com/tissuemosaic_manuscript/model_checkpoints.tar.gz 
│   ├── testis/
│   └── thymus/
├── TissueMosaic_output/ # Directory for TissueMosaic output:  https://storage.googleapis.com/tissuemosaic_manuscript/TissueMosaic_output.tar.gz
│   ├── testis/
│   └── thymus/
├── TissueMosaic_data/  # Directory for TissueMosaic data: https://storage.googleapis.com/tissuemosaic_manuscript/TissueMosaic_data.tar.gz
│   ├── testis_anndata/
│   └── thymus_anndata/
```
