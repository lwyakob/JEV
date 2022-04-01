# JEV

Project description: code to map JEV cases in Australia and to estimate population at risk, by Laith Yakob

Table of contents:
General info
Technologies
Setup
Features
Status
Contact
General info
JEV case data (infected humans and infected piggeries) for the 2022 Australian JEV outbreak are mapped along with all known locations of piggeries. Boundaries of varying sizes are plotted around the piggery locations and masked to WorldPop raster data to estimate those at risk of infection.

Technologies:
Python - version 3.9

Setup:
Following modules must be installed: matplotlib.pyplot ; numpy ; rasterio ; geopandas; shapely, pyproj; json; plotly
Users will need to download unadjusted 2020 Australia population data from WolrdPop

Features:
Mapping JEV cases: 'JEVmapsUPLOAD.ipynb'
Estimating population at risk of JEV: 'JEVfinalUPLOAD.ipynb'

Status:
Project is: finished

Contact:
Laith Yakob (https://www.lshtm.ac.uk/aboutus/people/yakob.laith) - feel free to contact me!
