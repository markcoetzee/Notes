
# R
*** With the advent of ‘modern’ GIS software, most people want to point and click their way through life. 

*copied from web

- raster: Reading, writing, manipulating, analyzing and modeling of gridded spatial data
- rgdal: Provides the most important and basic spatial functionalities. Provides bindings to Frank Warmerdam’s Geospatial Data Abstraction Library (GDAL) (>= 1.6.3, < 2) and access to projection/transformation operations from the PROJ.4 library
- sf and sp are the most important R packages to handle vector data; sf is a successor of sp, but it’s still evolvin
- rgeos: Provides spatial vector operations like buffer and intersect. Interface to Geometry Engine – Open Source (GEOS) using the C API for topology operations on geometries.
- maps: This package has pre-loaded maps stored which can be added to your map plots.
- maptools: tools for reading and writing spatial data (visualisation)
- ncdf4: Use with NetCDF files. Note that the raster package is also able to read NetCDF files and I prefer to use raster whenever possible.

### Spatial data visualization packages

- ggplot2: With the recent incorporation of sf into ggplot2, you can now use geom_sf() to plot vector data.
- leaflet: Use leaflet in R to create interactive maps and visualize spatial data
- tmap: ggplot 2 for maps! A new package that gives Arc-like functionality to creating publication ready maps.
- rasterVis: a package that can be used to visualize raster data. Provides more functionality and customization than base plot for rasters.
- mapview: provides functions to create interactive visualisations of spatial data.

### Links
https://www.r-spatial.org/
https://cengel.github.io/rspatial/
CRAN Task View: Analysis of Spatial Data: https://cran.r-project.org/web/views/Spatial.html
http://cyberhelp.sesync.org/geospatial-packages-in-R-lesson/

### Books
https://geocompr.robinlovelace.net/

# Python
