# TissueMosaic Manuscript

The TissueMosaic package can be installed from here: https://github.com/broadinstitute/TissueMosaic. 

After cloning the repo, please create the expected subdirectories to hold intermediate output required to run the notebooks to generate the Figures. These intermediate files can be downloaded from a publicly available google bucket (see corresponding urls below). 

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
