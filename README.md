# Mind-Scan

## Goal
To create a script to automate the creation of Mobium Mind Scans.

## To run the notebook
Jupyter Notebook and Python 3.x must be installed on your machine. The easiest way to do this is to install Anaconda (https://www.anaconda.com/download) which will install all dependencies along with JN. Once this is installed, open Jupyter Notebooks by going to your command prompt terminal and typing:

`$ jupyter notebook`

This will open Jupyter Notebook in your browser. You can then navigate to this repo, select the notebook, and run cells.


## Alternative way to run the notebook
Notebook can be run from a docker file with the following link. However, there is no way to upload data to it currently

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/raferguson/Mind-Scan.git/master)


## Alternative way 3 to run the notebook
Python 3.x, pip, and virtualenv must be installed. Then, from the main directory folder of the repo, call

`virtualenv mindscan-automation`  
`source activate mindscan-automation`  
`pip install -r requirements.txt`  
`jupyter notebook`
