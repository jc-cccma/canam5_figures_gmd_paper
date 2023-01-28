# Repo for reproduction of figures in the CanAM5 paper submitted to GMD

This repo contains the juytper notebooks used to produce all figures in the paper "The Canadian Atmospheric Model version 5 (CanAM5.0.3)" that is submitted to GMD.

There are two directories:
1. `Main_Text_Figures` - Create the figures in the main text
2. `Supplemental_Figures` - Create the figures in the supplemental

In each of the directory there are Jupyter notebooks that use python to create each figure, including simple manipulation of observations.  There is a cell in each notebook where one can set variables that point to the input files.  Plots are inlined so they will need to be saved if one wants external figures.

Also include is the conda configuration file, `CanAM5_GMD_env.yaml` that can be used to generate the enviroment needed for the notebooks.
