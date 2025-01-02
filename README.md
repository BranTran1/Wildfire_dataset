# Wildfire_dataset

This dataset contains environmental and climatic variables for 1000 geographic coordinates within the Boreal Forest region of Alberta, Canada. The data was collected to investigate the factors influencing wildfire occurrences and to train machine learning models for wildfire prediction. The dataset includes 500 coordinates where wildfires occurred and 500 coordinates where no wildfires were reported. Each coordinate is associated with key environmental variables that affect wildfire activity.

The dataset includes the following columns:
Latitude: Latitude of the coordinate (decimal degrees).
Longitude: Longitude of the coordinate (decimal degrees).
Wildfire: Binary indicator (1 = wildfire occurred, 0 = no wildfire).
NDVI: Normalized Difference Vegetation Index
Avg_Temp: Average temperature at the coordinate 
Total_precip: Total precipitation at the coordinate.
Avg_humid: Average relative humidity at the coordinate.
Avg_wind: Average wind speed at the coordinate.

Data was obtained using the Nasa Fire Information for Resource Management System (FIRMS) website along with the Google Earth Engine datasets for ERA5 Climate Reanalysis and MODIS.
