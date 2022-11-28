# Tutorials

Collection of tutorials I have undertaken, focussed on accessing, processing and visualising climate change data using Python.

## In-depth Tutorials:

- [Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro.html) Tutorial series covering Python environments and key packages for analysis and visualisation. Includes valuable assignments (shown at the bottom of this page) to problem-solve independently. 
  - (*Numpy, Pandas, Matplotlib, Xarray, Cartopy*)
- [Pythia Foundations](https://foundations.projectpythia.org/landing-page.html) Tutorial series progressing from introductory to intermediate level, covering analysis of climate change data using Python. Particularly good introduction to Jupyter and GitHub.
  - (*NumPy, Matplotlib, Cartopy, Datetime, Pandas, Xarray*)
- [Earth Data Science](https://www.earthdatascience.org/) Thorough 'Intro' and 'Intermediate' textbooks, covering the complete data access, analysis and visualisation process. Valuable section handling remote sensing data.
  - (*Xarray, Matplotlib, Pandas*)
- [Spatial Thoughts: Python Foundation for Spatial Analyse](https://courses.spatialthoughts.com/python-foundation.html) Python fundamentals focussed on accessing and manipulating geospatial data, including Anaconda, APIs and data structures.
  - (*Pandas, Geopandas, NumPy, RasterIO*)

## Full Geospatial Workflow Tutorials:

- [Spatial Thoughts: Mapping and Data Vizualization with Python](https://courses.spatialthoughts.com/python-dataviz.html) In-depth guide on how to access and visualise geospatial data, progressing from Matplotlib basics to interactive maps and apps.
  - (*Matplotlib, GeoPandas, Xarray, rioxarray, Cartopy, Folium, Streamlit, Leafmap*)
- [Python Geospatial Tutorial](https://colab.research.google.com/drive/1B7gFBSr0eoZ5IbsA0lY8q3XL8n-3BOn4#scrollTo=sOFhBVx_fQcY) 'Basic', 'Intermediate' and 'Advanced' scripts covering automated downloading, in-depth manipulation and plotting of gridded data, culminating in producing a video. 
  - (*Xarray, Matplotlib, cv2*)
- [Copernicus Training](https://github.com/ecmwf-projects/copernicus-training) Series of notebooks covering how to  access and visualise data from Copernicus CDS and CAMS. Excellent CSD API introduction and GIF tutorial.
  - (*cdsapi, Xarray, Matplotlib, Cartopy, imageio*)
  
## Notebooks on Accessing Data:

Specialist notebooks tutorials on accessing climate change data.

- [NASA Coding Club](https://github.com/podaac/the-coding-club/blob/main/notebooks/Earthdata_webinar_20220727.ipynb) Individual notebook tutorial for accessing and basic plotting of NASA sea level data from Amazon cloud.
  - (*AWS*)
- [ESA CCI SST](https://surftemp.github.io/sst-data-tutorials/) Individual notebook tutorial for accessing ESA satellite SST data from Amazon cloud.
  - (*AWS*)
- [Pharos API](https://colab.research.google.com/drive/1WkIm8thDSWI8ENDlPdAGMnlhaZWG0Ch0?usp=sharing) Individual notebook tutorial for accessing Pharos Data Catalogue.
  - (*Pharos API*)
- [CarbonPlan CMIP-6](https://github.com/carbonplan/cmip6-downscaling/blob/main/notebooks/accessing_data_example.ipynb) Individual notebook accessing downscaled CMIP-6 data.
- [CryoTEMPO-EOLIS](https://cryotempo-eolis.org/tutorials/) Two notebooks accessing CryoSat elevation data.
- [Pangeo Notebooks](http://gallery.pangeo.io/index.html) Large, wide-ranging collection containing advanced notebooks on topics including CMIP6 (Google Cloud) and LandSat8 (AWS). Focus on accessing large datasets.
  - (*Zarr*)

## Jupyter Books:

Collection of longer, in-depth training resources on climate data.

- [ICESat-2](https://www.icesat-2-sea-ice-state.info/content/0_home.html) Accessing, wrangling and visualising Arctic sea ice data from NASA's ICESat-2.
- [Dust Aerosol Detection, Monitoring and Forecasting](https://dust.trainhub.eumetsat.int/docs/index.html) EUMETSAT training on dust monioring and forecasting data from ground, satellite and model sources.
- [FANGS - Fire Applications with Next Generation Satellites](https://fire.trainhub.eumetsat.int/docs/index.html) EUMETSAT training on satellite fire datasets. Requires registration.
- [Physical Oceanography](http://rabernat.github.io/intro_to_physical_oceanography/intro.html) Educational resource, teaching principles of physical oceanography using Python. Includes Xarray/Holoviews implementation.
- [LTPy](https://gitlab.eumetsat.int/eumetlab/atmosphere/atmosphere) Thorough tutorial series covering the full workflow for satellite and modelled atmospheric composition data on topics such as pollution, fires and ozone.

## Python Visualisation Resources:

- [PyViz](https://pyviz.org/tools.html) Comprehensive list of visualisation packages in Python.
- [Coding for Economists](https://aeturrell.github.io/coding-for-economists/vis-intro.html) Large, advanced-level Jupyter book covering multiple visualisation libraries.
  - (*Matplotlib, Seaborn, Plotly*)
- [Awesome Matplotlib](https://github.com/paniterka/awesome-matplotlib) List of resources and tutorials across a range of proficiencies.
  - (*Matplotlib*)
- [The Python Coding Book](https://thepythoncodingbook.com/basics-of-data-visualisation-in-python-using-matplotlib/) Step by step tutorial on the basics of using Matplotlib, including animations.
  - (*Matplotlib*)
- [Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book) Large, advanced-level book covering every aspect of visualisation using Matplotlib.
  - (*Matplotlib*)
- [Matplotlib for Storytellers](https://github.com/alexanderthclark/Matplotlib-for-Storytellers/tree/main/Demos) Book and notebooks, focussed on figure customisation.
  - (*Matplotlib*)
- [Dunder Data on Matplotlib DPI](https://medium.com/dunder-data/why-matplotlib-figure-inches-dont-match-your-screen-inches-and-how-to-fix-it-993fa0417dba) Detailed tutorial on sizing Matplotlib figures in Jupyter notebooks. 
  - (*Matplotlib*)
- [Figuring Figures Out: A Matplotlib Tutorial, Part 2](https://www.sonofacorner.com/figuring-figures-out/) Detailed tutorial on sizing figure elements using Matplotlib coordinate systems. 
  - (*Matplotlib*)
- [Python Maps](https://github.com/symmy596/towards-data-science-articles) Articles and notebooks on producing customised maps.
  - (*Matplotlib, GeoPandas*)
  
## Tutorials on writing Jupyter Notebooks:
- [Ploomber](https://ploomber.io/blog/clean-nbs/) Advanced-level guide on best practice for using Jupyter notebooks. 
- [Earth Observation Training](https://www.mdpi.com/2072-4292/14/14/3359) Thorough paper specifically for producing Jupyter notebooks for training purposes.

## Video Tutorial Series:

- [MetPy Mondays](https://www.youtube.com/playlist?list=PLQut5OXpV-0ir4IdllSt1iEZKTwFBa7kO) Large (200+) collection of videos on individual topics throughout processing and plotting geospatial data in Python. Useful if you are stuck on something meteorological. 
  - (*Xarray, Cartopy, MetPy*)
- [Climate Unboxed](https://www.youtube.com/channel/UC94xkaJn1NkxR4trAfVArbg) Series on acessing CDS API and analysing NetCDF files in Python.
  - (*cdsapi*)

# Tutorial Assignments

Assignment from the [Earth and Environmental Data Science Tutorial](https://earth-env-data-science.github.io/assignments/more_matplotlib.html). The objective was to produce **My Attempts** at recreating **Target Figures** using Matplotlib, Xarray and Cartopy. Data access was not part of this assignment (often different from data in the target figure). All credit to the authors (Ryan Abernathey, Kerry Key and Tim Crone).

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

## NARR data Assignment

**Target Figure:**

<img src="https://earth-env-data-science.github.io/_images/narr_map.png" width="600" />

**My Attempt:**

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/NARR%20Assignment.png?raw=true" width="600" />

## Antarctic Sea Ice Assignment

**Target Figure:**

<img src="https://earth-env-data-science.github.io/_images/sea_ice_map.png" width="600" />


**My Attempt:**

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/Antarctic%20Assignment.png?raw=true" width="600" />

## Global USGS Earthquakes Assignment

**Target Figure:**

<img src="https://earth-env-data-science.github.io/_images/earthquake_map.png" width="600" />

**My Attempt:**

<img src="https://github.com/danhooke/Python-Tutorials/blob/main/Earthquakes%20Assignment.png?raw=true" width="600" />
