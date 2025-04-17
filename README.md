<h1 align=`center`>AnaVox</h1>

This repository contains a simple linear pipeline for the analysis of volume series output by heterogeneity software designed for the anlayis of single-particle Cryo-EM samples. It is based on Singular Value Decomposition (SVD) of a series volumes, as well as an inspection of power power spectrum across the series. 

Details about AnaVox construction can be found in the associated [publication](https://www.biorxiv.org/content/10.1101/2024.10.07.617120v1)

The data necessary to run the `compare_volume_series.ipynb` notebook can be found on [zenodo](https://zenodo.org/records/13900836).

# Installation 
  1. `git clone git@github.com/flatironinstitute/AnaVox`
  2. `conda create -n AnaVox python=3.10`
  3. `conda activate AnaVox`
  4. `cd AnaVox`
  5. `pip install .`
  6. Run the `compare_volume_series.ipynb` jupyter notebook.


