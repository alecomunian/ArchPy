# ArchPy
[![Documentation Status](https://readthedocs.org/projects/archpy/badge/?version=latest)](https://archpy.readthedocs.io/en/latest/?badge=latest)
![logo](./sphinx_build/source/figures/logo_web.png)

A hierarchical stochastic geological modeling tool in Python


## Installation

ArchPy can be installed with pip :

```
pip install geoarchpy
```

OR 

ArchPy can be installed with 
```
pip install .
```
when in the main directory.

Alternatively, it is possible to add ArchPy path directly in the python script with sys :
```
sys.path.append("path where ArchPy is") 
```
and then import ArchPy.

:warning: **Issues with widgets**: For some reasons, widgets does not work properly with recent version of jupyter-server due to recent versions of tornardo. Ensure to have tornado==6.1 if you plan to use widgets and interactive functions with the matplotlib notebook backend. 

## Requirements

Works with python>=3.8

The following python packages are absolutely necessary:
   - [Geone](https://github.com/randlab/geone)
   - matplotlib
   - numpy
   - SciPy
   - sklearn
   - pandas
   - shapely < 2.0
   - scikit-learn

These are not required but highly recommanded.
   - PyVista
   - pyyaml (for export uses)
   - Rasterio (to use rasters)
   - Geopandas (to use shapefile)
   - ipywidgets
   
 ## Examples
 There is some example notebooks :
 - 01_basic : a folder where simple and basics ArchPy functionnalities are described 
 - 02_3D_ArchPy : a complete 3D ArchPy model example
 - 03_Article_example : a synthetical example shown in ArchPy article
 - 04_hierarchies : an exemple with many hierarchical units to test ArchPy capabilities
 - 05_mps_surfaces : an example how to use MPS to simulate the units surfaces
 - 06_cross_validation : a notebook that present how to perform a cross-validation directly with ArchPy
 - 07_geological_map : this notebook presents how to integrate and use a geological in an ArchPy model
 - 08_inference : little guide how to use archpy inference tools to estimate surface parameters (no facies parameters for now)
 - 09_interface : little exemple of an interface to call an preexisting archpy model.
 
 ## Paper
 A paper was published on the ArchPy concept and its different capabilities.
 The paper was written with the version 0.1 of ArchPy.
 It is available with the following [link](https://www.frontiersin.org/articles/10.3389/feart.2022.884075/).

 ## Contact
 For any questions regarding ArchPy, please contact me at <ludovic.schorpp@unine.ch>
