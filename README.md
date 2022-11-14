# data_processing
Taking a look at some datasets for use in our methods


# In this repo, we will try to analyze some of the datasets that could be used our methods later on.
## Ideally, we would like to gain better understanding of 

1. Spatial Transcriptomics Data
2. scRNA-seq data
3. Discover datasets that contain both spatial and scRNA-seq data


# Explorations:

### Dataset 4 from Benchmarking paper

First we will attemp to take a look at the 4th dataset as outlined in Li, B., Zhang, W., Guo, C. et al. Benchmarking spatial and single-cell transcriptomics integration methods for transcript distribution prediction and cell type deconvolution. Nat Methods 19, 662–670 (2022). https://doi.org/10.1038/s41592-022-01480-9

The dataset is here:

Dataset 4 (mouse cortex): seqFISH+, https://github.com/CaiGroup/seqFISH-PLUS, and the spatial coordinate of each spot was generated using ‘stitchFieldCoordinates’ function in Giotto; Smart-seq, mouse primary visual cortex (VISp) in the dataset in https://portal.brain-map.org/atlases-and-data/rnaseq/mouse-v1-and-alm-smart-seq.


### Logs

downloaded https://portal.brain-map.org/atlases-and-data/rnaseq/mouse-v1-and-alm-smart-seq into /datasets.

I am using a conda environment 

installed anngtf from https://pypi.org/project/anngtf/

Tried to parse the gtf data from the dataset using anngtf but the code threw an error and was not sure how to resolve, see [mouseVISP.ipynb](mouseVISP.ipynb)