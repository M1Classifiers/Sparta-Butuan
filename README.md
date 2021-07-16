Our entry to DOST Sparta Hackathon Challenge 2021

# Datasets 
The datasets are overlayed using the [Butuan city administrative boundary](http://philgis.org/city-and-capital-page/butuan-city) shapefile as basis (Barangay-level clustering).

### [Google Earth Engine](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD13Q1?hl=en#dois)
- NDVI (Normalized difference vegetation index) 
### [Hazardhunter](https://hazardhunter.georisk.gov.ph/map)
- Nabunturan fault earthquake intensity map 
- Surigao fault earthquake intensity map 
- Earthquake-induced landslide susceptibility map
### Housing and settlement data
- [FB Settlement data](https://www.ciesin.columbia.edu/data/hrsl/)
- [OpenStreetMap(OSM)](https://extract.bbbike.org/)
- [Demographic Health Survey (DHS)](https://dhsprogram.com/methodology/survey/survey-display-510.cfm)

# Pre-processing
- **Google Earth Engine**: Javascript used to export GeoTIFF raster data that spans 5 recent months (Jan 10 2021 - June 10 2021). 
- **Hazardhunter**: Features extracted and approximated using QGIS3
- **FB Settlement and OSM**: Settlement, # of buildings, # of points of interest(POIs), # of streets, aggregated using QGIS3
- **DHS**: 
 
# Dependencies
- QGIS v3.16.7
