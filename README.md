# landsat-sst-san-andres
Surface Temperature Mapping using Landsat Satellite Data (San Andrés Island)

Sea Surface Temperature Mapping — San Andrés Island (Landsat 8)

This project analyzes sea surface temperature (SST) around San Andrés Island, Colombia, using NASA Landsat 8 Level-2 satellite data. The goal is to visualize spatial variability in ocean temperatures and explore future steps for marine ecosystem monitoring in the Seaflower Biosphere Reserve.

*Data Source:*
Landsat 8 OLI/TIRS Level-2, Surface Temperature Product
Downloaded from: USGS EarthExplorer

*Scene ID example:*
LC08_L2SP_014051_20210114_20210308_02_T1_ST_B10.TIF

*Library	- Purpose*
Rasterio - Read geospatial raster data
NumPy	- Pixel data transformations
Matplotlib -	Visualization
Python - Analysis and plotting

*Methodology*
1. Download thermal infrared satellite data from EarthExplorer
2. Convert Kelvin → Celsius
3. Visualize SST around San Andrés Island
4. Interpret spatial differences in temperature
 - Note: Image currently includes land and cloud pixels — cloud and land masking will be a next step in analysis.

*Study Region*
San Andrés is part of Colombia’s Seaflower Marine Protected Area, a UNESCO Biosphere Reserve.

