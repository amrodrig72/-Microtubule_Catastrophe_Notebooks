# -Microtubule_Catastrophe_Notebooks

This repository uses the micro-cata package version 0.0.1 developed by Andres Rodriguez (amrodrig@caltech.edu) and Adiel Perez (afperez@caltech.edu) to analyze the microtubule time to catastrophe data acquired from Gardner, Zanic and coworkers (http://dx.doi.org/10.1016/j.cell.2011.10.037). 

# Relevant Data
Data used in this notebook can be found in the data folder but can also be downloaded from:

https://s3.amazonaws.com/bebi103.caltech.edu/data/gardner_mt_catastrophe_only_tubulin.csv

and

https://s3.amazonaws.com/bebi103.caltech.edu/data/gardner_time_to_catastrophe_dic_tidy.csv

Usage of this notebook and the micro-cata package requires both of these datasets.

# Using the notebook
This notebook contains four folders. 

Data: Where the relevant data is stored. This folder should be on the same level as Labeled-Unlabeled, Model-Comparison, and Gamma-ParaEsti folders.  

Labeled-Unlabeled: Contains the notebook where we compare time to catastrophe for labeled and unlabeled tubulin using a ECDF plot.

Model-Comparison: Contains the notebook where use a predictive ECDF and difference predictive ECDF plot to assess the gamma distribution and two-step model.

Gamma-ParaEsti: Contains the notebook where we calculate parameter estimates for the gamma distribution model of various concentrations of labeled tubulin. 

# micro-cata
micro_cata can be found on https://pypi.org/project/micro-cata/0.0.1/ and on https://github.com/amrodrig72/micro_cata

To install, in your terminal write **pip install micro-cata==0.0.1**

If you need access to the github repository of micro-cata, send an email requesting access to amrodrig@caltech.edu 
