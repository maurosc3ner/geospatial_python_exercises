# Using GDAL in Python

Nowadays, geospatial data is becoming the queen of data scientists. For remote sensing, earth conservation, or Health as in my research (effect of long-term pollutants), geospatial and particularly raster datasets are generated every day, minutes, and seconds by several satellites.

With projects, theses, new packages (rasterio, shapely or geopandas), or companies on its shoulders. GDAL has stood as the main geospatial library out there for years or even decades. Initially implemented in C/C++, GDAL is guilty of numerous successes in the geospatial community. 

![Greater Cincinnati](https://user-images.githubusercontent.com/4038971/109750294-2deb8a80-7baa-11eb-89c2-8bbf7d29869f.png)

As with any other low-level library, it is far from being easy with a stepped learning curve, especially in vector data. However, I will start adding some basic examples in geospatial tasks from the bottom-up perspective. Those examples will be driven by my curiosity and the necessity to create well-documented examples in Python 3. I plan to add examples to my playground repo incrementally. 

## Learning goals:

Learn common geographical tasks (transform, clipping, vector manipulation, zona statistics) in Python and its ecosystem.

Improve my python skills due to the fact that I have been habituated to R for GIS tasks.

## References
1. In the meantime,  this is the first exercise [GDAL intro](https://duckduckgo.com "NDVI, transformation and clipping").
2. For the proper installation of gdal env you can check this [tutorial](https://www.google.com/url?q=https%3A%2F%2Fmedium.com%2F%40nathancook_36247%2Flaunching-jupyter-notebook-from-the-command-line-can-be-more-powerful-than-using-anaconda-navigator-c7425cf1fd8a&sa=D&sntz=1&usg=AFQjCNHkVXiZUkzS6ZT2upfiqwIlVp_TKg)
3. API and documentation is at https://gdal.org/ 
