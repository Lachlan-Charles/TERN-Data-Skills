## Using Raster Data in R

The accompanying ‘R’, ‘html’, and 'pdf’ files contain the materials for the tutorial *'Using Raster Data in R'*.  A file containing the jupyter notebook version of the tutorial (i.e. '.ipynb' file) is also included. 

In this tutorial synthetic data is used to explain and demonstrate in detail how to work with raster data in R. The tutorial covers the following raster operations: 

1. Introduction
2. Raster Classes
3. Preparation
4. Creating Rasters: Adding, Dropping, and Subsetting Layers
5. Loading and Saving Rasters
6. Navigating Rasters
	1. Dimensions of a raster
	2. Names of raster
	3. Number of rows, columns, and cells
	4. Mapping Cells
	5. Coordinates for the center of raster cells
	6. Columns, Rows, and Cells from Coordinates (at the centre of cells)
7. Examining Raster Contents
	1. Examining raster contents numerically
	2. Visualising raster contents
8. Summarising raster contents
	1. Numerical Summaries
	2. Visual Summaries
9. Working with rasters values
	1. Modifying individual cell values
	2. Raster Calculations: ‘Raster Algebra’ & Raster Calculations using Higher Level Functions
	3. Raster Classification
10. Other ways to Combine multiple Raster objects: ‘mask()’ and ‘cover()’
11. Changing the essential Spatial Attributes of a Raster
	1. Changing Spatial Extent: ‘crop()’, ‘merge()’, ‘trim()’, and ‘extend()’
	2. Changing Resolution
	3. Defining & Changing Spatial Projections
	4. Setting the Spatial Attributes of All Rasters to the same values at once
12. Raster Prediction
	1. Interpolation
	2. Prediction
13 Other GIS operations with rasters in R
	1. Distance & Direction
	2. Spatial autocorrelation Raster
	3. Elevation, slope, aspect


&nbsp;
### Tutorial Materials and How to Obtain them

All the required materials for the workshop can be downloaded from this section of TERN's Data Skills Development Program GitHub pages; see the links above this README.md file. GitHub is a little bit fiddly and the procedures to download different file types differ slightly. These procedures, along with a brief description of the file contents, are described below.

#### '.html'

This file contains: (1) explanations for the workshop tutorial aims and methods, code, and outputs (i.e. results); (2) R code; and (3) code outputs. This will be the main file that we will use in the workshop. To download it: (1) click on the link for the '.html' file, (2) click on the 'View raw' link at the top of Viewer, (3) right click anywhere in the Viewer, then chose 'Save as...', and (4) choose the location and a name for the file, then click on the 'Save' button.

#### '.pdf' 

This file contains the pdf version of the '.html' file. To download it: (1) click on the link for the '.pdf' file, (2) click on the 'Download' button above the Viewer, (3) choose the location and a name for the file, then click on the 'Save' button.  

#### '.r'

This file contains the R code for the workshop tutorial. It is heavily commented, including the comments in the '.html' file. To download it: (1) click on the link for the '.r' file, (2) click on the 'Raw' button above the Viewer, (3) right click anywhere in the Viewer, then chose 'Save as...', and (4) choose the location and a name for the file, delete the extension '.txt' automatically added to the name by GitHub (the file already includes the correct extension '.r'), then click on the 'Save' button.

#### '.Rmd'

This file contains the R and Rmarkdown code used to generate the '.html' file (see above) in R-Studio.  The downloading procedure is as for '.r' files. That is, to download it: (1) click on the link for the '.Rmd' file, (2) click on the 'Raw' button above the Viewer, (3) right click anywhere in the Viewer, then chose 'Save as...', and (4) choose the location and a name for the file, delete the extension '.txt' automatically added to the name by GitHub (the file already includes the correct extension '.Rmd'), then click on the 'Save' button.

#### '.ipynb' 

This file contains the jupyter notebook version of the tutorial. To download it: (1) click on the link for the '.ipynb' file, (2) click on the 'Download' button above the Viewer, (3) right click anywhere in the Viewer then chose 'Save as...', and (4) choose the location and a name for the file, then click on the 'Save' button. 

#### Download or clone all the materials in TERN's Data SKills Development Program GitHub pages

Navigate to [TERN's Data SKills Development Program GitHub](https://github.com/ternaustralia/TERN-Data-Skills) main page. Click on the "Clone or download" green button. From here you can download a zip file with the materials for all TERN's DSDP Tutorials and Workshops. Alternatively, you can also clone these materials using Git.
	

&nbsp;
### Getting Started with the Tutorial

This tutorial uses R and a number of R packages. The packages required and how to install them are described below.

#### Prerequisites

To run the R scripts in this tutorial the following R packages (and their dependencies) must be installed: ggplot2, mapdata, maps, maptools, ncdf4, raster, rasterVis, RColorBrewer, rgdal, RColorBrewer, RKEA, and sp. 

#### Installing

The R packages required for this tutorial are installed in the usual way in R (after selecting a repository).

```
install.packages(c("ggplot2", "mapdata", "maps", "maptools", "ncdf4", "raster", "rasterVis", "RColorBrewer", "rgdal", "RColorBrewer", "RKEA", "sp"))
```


&nbsp;
### Data

This tutorial utilizes synthetic data specifically designed to explain and demonstrate particular operations using with raster data in R.


&nbsp;
### Citation

Please cite this tutorial as: 

Blanco-Martin, Bernardo (2019). 
Tutorial: "Using Raster Data in R".
Terrestrial Ecology Research Network.
Version 2019.04.0, April 2019.
https://github.com/ternaustralia/TERN-Data-Skills/tree/master/Landscapes_AusCover-RemoteSensing/UsingRasterDatainR


&nbsp;
### License

This tutorial is licensed under Creative Commons 'Attribution' (CC BY 4.0) license.

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by.png" alt="drawing" width="200"/>


&nbsp;
### Acknowledgments

To the authors of many fantastic tutorials on *spatial data* or *raster data in R* that inspired and educated the authors (and this tutorial). 

TERN is funded through the National Collaborative Research Infrastructure Strategy (NCRIS), an Australian Government Initiative.










