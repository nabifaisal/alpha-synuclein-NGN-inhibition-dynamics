# alpha-synuclein-NGN-inhibition-dynamics
Scripts and Jupyter notebooks for CVAE and MSM analysis of alpha-synuclein

This repository contains the core computational scripts, machine learning architectures, and simulation parameters used in our study on α-synuclein aggregation inhibition.

## Files Included:

* **`CVAE_CODE.ipynb`**: Implementation of the Convolutional Variational Autoencoder (CVAE) architecture and training loop.
* **`Clustering_&_tSNE.ipynb`**: Scripts for t-SNE dimensionality reduction and structural clustering of the CVAE latent space.
* **`MSM.ipynb`**: PyEMMA pipeline for Markov State Modeling, including tICA, PCCA+ coarse-graining, and Transition Path Theory (TPT) calculations.
* **`MD_Parameters/`**: GROMACS parameters (`.mdp` files) and topology files used to set up and run the adaptive simulations.

*(Note: Raw MD trajectory files are excluded due to GitHub file size limitations, but the simulations can be fully reproduced using the provided parameter files and notebooks.)*
