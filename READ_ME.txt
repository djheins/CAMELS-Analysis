These scripts are the core of what I used in my MSc dissertation to analyze data from the CAMELS dataset, and almost all of the figures included can be reproduced exactly or approximately from the scripts here. Skimming through said dissertation would likely help understand what the code is for.

To use, you will need to download the CAMELS data downloaded and expand the CAMELS datasets with the folders `/basin_timeseries_v1p2_metForcing_obsFlow/`
and `/camels_attributes_v2.0/` into some home folder, and copy that path into the start of `A_FunctionDefinitions.ipynb`, as well as stating the path for the data folder included here. 

The data folder here has some pre-processed data, created with modified forms of the scripts here. Explanation of columns is in DATA_EXPANATION.txt

All other scripts rely on A_FunctionDefinitions.ipynb, which defines a variety of functions for processing/visualizing data. ClusteringAndPlotting3D.ipynb requires a PlotLy account to create 3D scatterplots. 

Apologies for not cleaning/commenting the code further, and in particular for making anyone using the code have to set up the file structures. I'm happy to provide any help/answer any questions about using any of my code. 

-Dan (daniel.heins@gmail.com)

