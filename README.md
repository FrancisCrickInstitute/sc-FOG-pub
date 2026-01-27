# Festival of Genomics - Crick single-cell workshop

28th January 2026

## Welcome

This repository will help you follow along with the single-cell workshop. You will need to clone the repository to your local disk. 

## Cloning the repository

If you have git set up already, you can probably clone the repo by running: 

- `git clone https://github.com/FrancisCrickInstitute/sc-FOG-pub.git` or
- `git clone git@github.com:FrancisCrickInstitute/sc-FOG-pub.git` if you have ssh set up 

If all else fails, look for the green button marked 'Code' near the top of the GitHub repo page. Click it and choose 'download ZIP' at the bottom of the pane that appears.


## Set-up your Python environment

We are assuming that you are not a complete Python noob and these instructions will make some sense. Remeber that Google is your friend.

You will need to have a Python environment and we recommend sticking to versions between 3.9 and 3.11. You will need a few Python packages as well. Specifically:

- scanpy
- celltypist
- pandas
- numpy
- matplotlib
- seaborn
- jupyter
- ipykernel

If you are using conda, we have included a sc-fog-conda.yml file that might help you to create an envirnment for the session by running: `conda env create --file sc-fog-conda.yml`.

If you prefer to use uv, we have also included `pyproject.toml` and `uv.lock` files.


## Following along

We have included an iPython notebook with some code snippets to help you along the way. The notebook is called 'student_notebook.ipynb' and should be in the top folder of the repo.

There is also a 'data/' folder containing two files:

- adata_raw.h5ad - You can load the anndata object we will work with using this file
- Adult_Mouse_Gut.pkl - This pickle file will help you to annotate cell types later in the session

## Credits

This workshop was a collaborative effort between Georgia Whitton, James Campbell and Lina Gerontogianni. We would like to thank the Francis Crick Institute in London for being an awesome place to work. We would also like to give a special thanks to the Bioinformatics and Biostatistics STP (BABS) at the Crick for their contributions to the collective knowledge we all benefit from. Kanad Mandke gave us valuable input to help polish what we are presenting.

The data were provided by the Anne O'Garra lab at the Crick and are part of a data set published by Alvarez-Martinez _et al._ 2024. You can read more at [the Nature Immunology site](https://pubmed.ncbi.nlm.nih.gov/38609547/). 


## Do you want to learn more?

The Crick provide technical training on a wide range of scientific topics. You can find out more by visiting [www.crick.ac.uk/careers-and-study/technical-training](https://www.crick.ac.uk/careers-and-study/technical-training)











