# Overview of data downloaded and needed

## From MRI to 3D-1D FEM:

### Installation and preparation

Download the simulation software and data (meshes, simulation results, videos) snapshot from Zenodo: 

* Causemann, M., Masri, R., Kuchta, M., & Rognes, M. E. (2025). Software and data for "In-silico molecular enrichment and clearance of the human intracranial space" [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14749163

Clone the paper and code repository

* Paper and code repository: https://github.com/MariusCausemann/brain-PVS-SAS-transport

    git clone git@github.com:MariusCausemann/brain-PVS-SAS-transport.git

Follow the conda installation instructions in the readme.md given there. In short, first time around, create the conda environment from the .yml file:

    `conda env create -f environment.yml`

Then activate with

    `conda activate pvs_transport_env`
