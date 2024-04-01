![LOGO](banner.png)

Reproducible material for Elastography project 


## Project structure
This repository is organized as follows:

* :open_file_folder: **Code**: python library containing notebooks for reproducing the results
* :open_file_folder: **Data**: folder containing acoustic pressure estimations obtained from FOCUS

## Notebooks
The following notebooks are provided:

- :orange_book: ``1_ARF_modeling.ipynb``: notebook performing ARF modeling taking FOCUS acoustic pressure simulation as input
- :orange_book: ``2_Finite_Differences.ipynb``: notebook performing finite differences modeling using fdelmodc to obtain medium displacement after injecting the ARF
- :orange_book: ``3_Scatterers.ipynb``: notebook performing dynamic displacement estimation in the medium using cross correlation
- :orange_book: ``4_2D_Inversion.ipynb``: notebook performing LSQR inversion using the gradiometry approach 
- :orange_book: ``4.1_2D-Seismic-modeling.ipynb``: notebook performing FD modeling on a model with a spherical inclusion 
