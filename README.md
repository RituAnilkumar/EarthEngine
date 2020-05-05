# Tutorials on Google Earth Engine
This is a set of tutorials using the Earth Engine Python and JavaScript API. It is presently still being updated and modified. 
For anyone interested in using these tutorials, feel free to do so. Many of these have been prepared using several references available at the Earth Engine forum, the example codes on the Earth Engine page as well as examples by N Clinton, N Gorelick, Qiusheng Wu and G Dochyts. 
Additional referencing and improvements will be undertaken shortly. Presently, there are three files:
* A [presentation](https://github.com/RituAnilkumar/EarthEngine/blob/master/IntroductionToEE.ppsx) on Earth Engine using Materials heavily derived from N Clinton, N Gorelick and G Dochyts with links to many of their works. I've also linked scripts to working with the Code Editor for beginners. But fair warning: this is also largely derived and compiled rather than created.
* [Exercise 1](https://github.com/RituAnilkumar/EarthEngine/blob/master/Exercise1_single_band_visualization.ipynb) is aimed at simply accessing imagery and displaying them on a map. We use the [MODIS Vegetation Indices product](https://lpdaac.usgs.gov/documents/103/MOD13_User_Guide_V6.pdf). We explore a variety of the map tools such as the [IPython Display](https://ipython.readthedocs.io/en/stable/api/generated/IPython.display.html), [Folium](https://python-visualization.github.io/folium/quickstart.html), [geemap](https://github.com/giswqs/geemap) and the [Earth Engine Plugin for QGIS](https://github.com/gee-community/qgis-earthengine-plugin)
* [Exercise 2](https://github.com/RituAnilkumar/EarthEngine/blob/master/Exercise2_multispectral_analysis.ipynb) is far more detailed and will begin a proper Earth Engine Experience. We will access imagery([Sentinel 2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2)), filter it based on our Area of Interest (AOI) and date range of our interest and learn to visualize the multispectral data. Next, we will learn how to perform arithmetic operations and create a spectral indices ([modified normalized difference water index](https://www.tandfonline.com/doi/abs/10.1080/01431160600589179?journalCode=tres20)) and perform some basic logical operations and threshold it to generate a map of water bodies. 

Tentative exercises I'm planning to upload are:
* Exercise 3: Integrating EE with numpy
* Exercise 4: Timeseries analysis, charting and animations
* Exercise 5: Image Classification using existing EE libraries
* Exercise 6 Image classification using scikitlearn and Earth Engine imagery
* Exercise 7:Integrating with Keras/TensorFlow

Stay tuned. And hope I beat the procrastination monster.
