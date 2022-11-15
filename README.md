# Tutorials

Collection of tutorials I have undertaken and example notebooks I have found useful for producing climate change figures using Python.

## In-depth Tutorials:
- [Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro.html) Tutorial series covering Python environments and key packages for analysis and visualisation, including valuable assignments (shown below) to problem-solve independently. 
  - (*Numpy, Pandas, Matplotlib, Xarray, Cartopy*)
- [Pythia Foundations](https://foundations.projectpythia.org/landing-page.html) Tutorial on introductory and intermediate workflows for analysing climate change data using Python. Covers key libaries, and particularly good for GitHub.
  - (*NumPy, Matplotlib, Cartopy, Datetime, Pandas, Xarray*)
- [Earth Data Science](https://www.earthdatascience.org/) Thorough Intro and Intermediate courses, covering the complete data access, analysis and visualisation workflow.
  - (*Xarray, Matplotlib, Pandas*)

## Full Geospatial Workflow Tutorials:
- [Spatial Thoughts: Python Foundation for Spatial Analyse](https://courses.spatialthoughts.com/python-foundation.html) Python fundamentals, including APIs. 
  - (*Pandas, Geopandas, NumPy, RasterIO*)
- [Spatial Thoughts: Mapping and Data Vizualization with Python](https://courses.spatialthoughts.com/python-dataviz.html) 
  - (*Matplotlib, GeoPandas, Xarray, rioxarray, Cartopy, Folium, Streamlit, Leafmap*)
- [Python Geospatial Tutorial](https://colab.research.google.com/drive/1B7gFBSr0eoZ5IbsA0lY8q3XL8n-3BOn4#scrollTo=sOFhBVx_fQcY) Basic, Intermediate and Advanced scripts covering automated downloading, in-depth manipulation and plotting of gridded data, culminating in producing a video. 
  - (*Xarray, Matplotlib, cv2*)

## Specialist Notebooks on Accessing Data:

- [Copernicus Training](https://github.com/ecmwf-projects/copernicus-training) Series of notebooks training on accessing and visualising Copernicus CDS and CAMS data, including APIs and GIFs. 
  - (*cdsapi, Xarray, Matplotlib, Cartopy, imageio*)
- [NASA Coding Club](https://github.com/podaac/the-coding-club/blob/main/notebooks/Earthdata_webinar_20220727.ipynb) Notebook tutorial for accessing NASA sea level data from Amazon cloud.
  - (*AWS*)
- [ESA CCI SST](https://surftemp.github.io/sst-data-tutorials/) Individual notebook tutorial for accessing ESA satellite SST data from Amazon cloud.
  - (*AWS*)
- [Pharos API](https://colab.research.google.com/drive/1WkIm8thDSWI8ENDlPdAGMnlhaZWG0Ch0?usp=sharing) Individual notebook tutorial for accessing Pharos Data Catalogue.
  - (*Pharos API*)
- [CarbonPlan CMIP-6](https://github.com/carbonplan/cmip6-downscaling/blob/main/notebooks/accessing_data_example.ipynb) Individual notebook accessing downscaled CMIP-6 data.
- [CryoTEMPO-EOLIS](https://cryotempo-eolis.org/tutorials/) Two notebooks accessing CryoSat elevation data.
- [Pangeo Notebooks](http://gallery.pangeo.io/index.html) Large, wide-ranging collection containing advanced notebooks on topics including CMIP6, LandSat and Cryosphere data.

## Specialist Python Visualisation Resources:

- [PyViz](https://pyviz.org/tools.html) Comprehensive list documenting all the visualisation packages in Python.
-  [Coding for Economists](https://aeturrell.github.io/coding-for-economists/vis-intro.html) Large, advanced-level explainer across multiple visualisation libraries.
- [Awesome Matplotlib](https://github.com/paniterka/awesome-matplotlib) List of resources and tutorials.
- [The Python Coding Book](https://thepythoncodingbook.com/basics-of-data-visualisation-in-python-using-matplotlib/) Step by step tutorial on the basics of using Matplotlib, including animations.
  - (*Matplotlib*)
- [Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book) Large, in-depth book covering every aspect of visualisation using Matplotlib.
  - (*Matplotlib*)
- [Matplotlib for Storytellers](https://github.com/alexanderthclark/Matplotlib-for-Storytellers/tree/main/Demos) Book and notebooks, focussed on figure customisation.
  - (*Matplotlib*)
- [Dunder Data on Matplotlib DPI](https://medium.com/dunder-data/why-matplotlib-figure-inches-dont-match-your-screen-inches-and-how-to-fix-it-993fa0417dba) Detailed tutorial on sizing Matplotlib figures in Jupyter notebooks. 
  - (*Matplotlib*)
- [Figuring Figures Out: A Matplotlib Tutorial, Part 2](https://www.sonofacorner.com/figuring-figures-out/) In-depth tutorial on sizing figure elements using Matplotlib coordinate systems. 
  - (*Matplotlib*)
- [Python Maps](https://github.com/symmy596/towards-data-science-articles) Articles and notebooks on producing customised maps.
  - (*Matplotlib, GeoPandas*)

## Video Tutorial Series:
- [MetPy Mondays](https://www.youtube.com/playlist?list=PLQut5OXpV-0ir4IdllSt1iEZKTwFBa7kO) Large (200+) collection of videos on individual topics throughout processing and plotting geospatial data in python. Useful if you are stuck on something meteorological. 
  - (*Xarray, Cartopy, MetPy*)
- [Climate Unboxed](https://www.youtube.com/channel/UC94xkaJn1NkxR4trAfVArbg) Series on acessing CDS API and analysing NetCDF files in Python.
  - (*cdsapi*)

# Tutorial Assignments

Assignment from the [Earth and Environmental Data Science Tutorial](https://earth-env-data-science.github.io/assignments/more_matplotlib.html) recreating target plots in Matplotlib, using prescribed data (often different from the original data). All credit to the authors (Ryan Abernathey, Kerry Key and Tim Crone).

## Line plots

**Target Figure:**           

<img src="https://user-images.githubusercontent.com/44374383/200693145-c485c11e-0ee2-499b-9e7d-8de19692e592.png" width="800" />   

**My Attempt:**       [Code for Figure](https://github.com/danhooke/Python-Tutorials/blob/main/Line%20Assignment.ipynb)

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/Line%20Assignment.png?raw=true" width="800" />

## Contour plots

**Target Figure:**

<img src="https://earth-env-data-science.github.io/_images/fig2.png" width="800" /> 

**My Attempt:** [Code for Figure](https://github.com/danhooke/Python-Tutorials/blob/main/Contour%20Assignment.ipynb)

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/Contour%20Assignment.png?raw=true" width="800" /> 

## Scatter plots

**Target Figure:**

<img src="https://earth-env-data-science.github.io/_images/fig3.png" width="800" /> 

**My Attempt:** [Code for Figure](https://github.com/danhooke/Python-Tutorials/blob/main/Scatter%20Assignment.ipynb)

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/Scatter%20Assignment.png?raw=true" width="800" /> 
