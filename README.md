# Land Stratification
## [![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/kritika-srivastava/Random-Password-Generator/blob/master/LICENSE)![Project Status](https://img.shields.io/badge/ProjectStatus-Completed-orange)[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
![Python Badge](https://img.shields.io/badge/Python-3.5%7C3.6%7C3.7-success)![Dependency](https://img.shields.io/badge/Dependencies-Rasterio%20%7C%20Matplotlib%20%7C%20PIL-critical)

Land cover classification has been one of the most common tasks in remote sensing as it is the foundation for many global and environmental applications.

This project is an extension to the project [The Conurbation Algorithm](https://github.com/kritika-srivastava/The-Conurbation-Algorithm) and the aim of this project is to preprocess the input data for the city Generation.
### Challenges :
- Dataset preprocessing and stitching all tif images cooresponding to a geographical location (Mosaic generation).
- Extraction of contours for vegetation.
- Desaturating the contour plot  to obtain a grayscale image.
### Input-
LISS-III satellite data obtained from Open Data Archive from [ISROBhuvan](https://bhuvan-app3.nrsc.gov.in/data/download/index.php)

The sample dataset consists of 16 tif images(4 cooresponding to each of the 4 geographical location).

Input multispectral Images -

<img src="https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/img/readme.png" width="400" height ="400">

### Dependencies -
- Python
- Rasterio
- PIL
- Matplotlib
### Steps to replicate the output
- Clone this repository.
- Install the required dependencies in the runtime environment (Preferably Anaconda).
- cd to the [jupyter notebook](https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/Main.ipynb) and change the paths of inputs. 
- Run the jupyter notebook.
##### Note- The jupyter notebook won't be visible on the github as github cannot render raster files properly. It is advised to run the file on google colab or jupyter notebook.

If everything worked so far the output should look like the one given below.

### Output Mosaic -

<img src="https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/img/output.PNG" width="400">

### Contour Extraction -
<img src="https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/img/contour.PNG" width="400">

### Grayscale Image-
<img src="https://github.com/kritika-srivastava/Land-Stratification-ISRO/blob/master/Binary_mosaic.png" width="400">

### References -
#### [Rasterio Documentation](https://rasterio.readthedocs.io/en/latest/quickstart.html)
#### [Mosaic Generation](https://automating-gis-processes.github.io/CSC18/lessons/L6/raster-mosaic.html)
