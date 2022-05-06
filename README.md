# bioe235_final_project

This repo contains the Jupyter notebook `tissue_sample_clustering.ipynb` that performs PCA and t-SNE clustering on an example nanopore dataset comprising four human tissue samples (aorta, adrenal gland, bladder, lymph node). 

Required packages (for Python 3):
* numpy
* matplotlib
* seaborn
* sklearn

The example nanopore data have been preprocessed (i.e. capture extraction from bulk raw current + normalization) following the pipeline used in https://www.nature.com/articles/s41587-021-01002-6, code for which can be found at https://github.com/uwmisl/NanoporeTERs. 
