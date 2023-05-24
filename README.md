# New-Gridded-Population-Mapping
This is the official repository for the article "Improving gridded population map for mainland China using 3D building, nighttime light, points-of-interest, and land use/cover data in a multiscale geographically weighted regression model"

Data description

Auxiliary Data.gdb:
Land_use: original land use data
POI_name: interests-point-data from the Amap platform (name indicates category)
Nighttime light: nighttime light data
Res_building_volume_m3: residential building volume data

New_gridded_population_dataset(.gdb): 
Experimental result data, i.e., a gridded population map of mainland China with a resolution of 100 meters

PopulationData_AdministrativeUnitLevel(.gdb):
Population_data_mainlandChina_level3: population data at the district and county level in mainland China
Population_data_Name_level4: township and street-level population data for provinces and municipalities

POI_Correlation_Coefficient:
Python script: programming implementation for selecting the optimal bandwidth for POI
Zonal statistical output of POI kernel density values: summary of various POI kernel densities in residential areas of administrative units
Summary of POI Pearson correlation coefficients: sum of Pearson's correlation coefficients for 13 types of POIs at a certain bandwidth
