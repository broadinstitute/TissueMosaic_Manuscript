# TissueMosaic Manuscript

The TissueMosaic package can be installed from here: https://github.com/broadinstitute/TissueMosaic. 

After cloning the repo, please create the expected subdirectories to hold intermediate output to run the notebooks to generate the Figures. The expected directory structure to run all the notebooks is as follows:

## Directory structure

```
TissueMosaic_Manuscript/
├── pkls/ # Directory for intermediate files from long-running notebook steps 
├── benchmarking/ # Directory for benchmarking output
│   ├── spagcn/
│   └── stagate/
├── model_checkpoints/ # Directory for pre-trained model checkpoints
│   ├── testis/
│   └── thymus/
├── TissueMosaic_output/ # Directory for TissueMosaic output
│   ├── testis/
│   └── thymus/
├── TissueMosaic_data/  # Directory for TissueMosaic data
│   ├── testis_anndata/
│   └── thymus_anndata/
```
