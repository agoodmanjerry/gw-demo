# Tutorials on the Glitch Classification of Gravitational Wave Data
This is a series of tutorials on the data analysis of Gravitational Wave (GW) data released by [https://gwosc.org/](https://gwosc.org/). We will use the packages like [GWpy](https://gwpy.github.io/docs/stable/), [PyCBC](), [Bilby](), [Omicron](https://virgo.docs.ligo.org/virgoapp/Omicron/), etc., to process data, detect GW signals and do the Parameter Estimation (PE) on the detected signals.

## Installing Environments
It is recommended to use [Mamba](https://mamba.readthedocs.io/en/latest/) or [Conda](https://www.anaconda.com/docs/getting-started/miniconda/main) to manage the python packages used in the tutorials.
To install the environment, please follow the instructions:
1. ```git clone https://github.com/agoodmanjerry/glitch-classification.git```
2. ```cd glitch-classification```
3. ```mamba env create -y -f environment.yaml```

Then load the environment and run the codes in the jupyter notebook.