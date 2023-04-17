Metadata for ALoCE:
- Title
```
Downscaled and bias corrected dataset for multiple GCMs and variables
```
- Abstract
```
Understanding the impact of climate variability and change is of great importance for developing adaptation 
and mitigation strategies. Coarse resolution data sets such as simulations of general circulation models (GCMs) 
are important for reconstructing historical climate and predicting the future. However, scale discrepancy and 
biases limit the coarse resolution data sets from being directly used for impact assessments and decision making. 
One solution for bridging this gap is to downscale and bias correct coarse resolution data to the local scale.
```
- Summary
```
We bias corrected and downscaled 9 climate variables for 5 popular GCMs from the latest CMIP6 
with a widly used method, namely quantile delta mapping (QDM). 
The dataset has spatial resolution of 0.25 degree and daily temporal scale. For each GCM, 
two emission levels are included(ssp126 as low emission level and ssp585 as high emission level). 
The names of the 5 GCMs are EC-Earth3, MPI-ESM1-2-HR, MRI-ESM2-0, IPSL-CM6A-LR,and GFDL-ESM4. 
The 9 variables include daily total precipitation (pr), daily maximum near-surface air temperature(tasmax), 
daily minimum near-surface air temperature (tasmin),eastward near-surface wind (uas),northward 
near-surface wind (vas),near-surface relative humidity (hurs), surface downwelling shortwave radiation (rsds), 
surface downwelling longwave radiation (rlds) and sea level pressure (psl). The dataset will be used as forcings 
for the watershed modeling and physical/biogeochemical modeling around the bay area to explore adaptation and 
mitigation strategies.
```
- Author (Full name, ORCID, email, institution)
```
Fang Wang, fzw0024@auburn.edu, Department of Crop, Soil and Environmental Sciences, Auburn University
Di Tian, tiandi@auburn.edu, Department of Crop, Soil and Environmental Sciences, Auburn University
```
- Co-authors (Full names - ORCIDs if you have them is even better, emails and institutions)
- Geographical region of interest (bounding geospatial box is fine - lat/long of furthest extents or specific sites is fine also)
```
longitude range -94.5, -84.25
Latitude range: 26.00, 35.25
```

From Pat:
- Note that the abstract and summary is usually referencing the dataset itself and not necessarily the project abstract/summary.
- I can also mint DOIs for any datasets as well - just let me know if you need/want one to reference further in papers or publications.
- I will coordinate with the submitter to make sure we have the proper information to supoprt the DOI minting and uploading the data.


Metadata for researchers, what are in these directories?
```
./NOAA_data                                           # The main directory including BC/downscaled and original data
./NOAA_data/ERA5-single-hourly                        # Hourly ERA5 data directly downloaded from ECMWF website
./NOAA_data/ERA5-single-hourly/hurs                   # Hourly ERA5 data for near-surface relative humidity (hurs)
./NOAA_data/ERA5-single-hourly/psl                    # Hourly ERA5 data for sea level pressure (psl)
./NOAA_data/ERA5-single-hourly/rlds                   # Hourly ERA5 data for surface downwelling longwave radiation (rlds)
./NOAA_data/ERA5-single-hourly/rsds                   # Hourly ERA5 data for surface downwelling shortwave radiation (rsds)
./NOAA_data/ERA5-single-hourly/uas                    # Hourly ERA5 data for eastward near-surface wind (uas)
./NOAA_data/ERA5-single-hourly/vas                    # Hourly ERA5 data for northward near-surface wind (vas)
./NOAA_data/ERA5-single-hourly/d2m                    # Hourly ERA5 data for 2m dew temperature
./NOAA_data/ERA5-single-hourly/pr                     # Hourly ERA5 data for total precipitation
./NOAA_data/ERA5-single-hourly/t2m                    # Hourly ERA5 data for 2m temperature
./NOAA_data/ERA5-single-daily                         # Daily ERA5 data for the 9 variables
./NOAA_data/CMIP6_GCMs                                # All the original GCM data without BC and downscaling
./NOAA_data/CMIP6_GCMs/MPI-ESM1-2-HR                  # GCM MPI-ESM1-2-HR  
./NOAA_data/CMIP6_GCMs/MPI-ESM1-2-HR/ssp126           # GCM MPI-ESM1-2-HR for the low emssion level ssp126(2015 to 2100)
./NOAA_data/CMIP6_GCMs/MPI-ESM1-2-HR/ssp585           # GCM MPI-ESM1-2-HR for the high emssion level ssp585(2015 to 2100)
./NOAA_data/CMIP6_GCMs/MPI-ESM1-2-HR/historical       # GCM MPI-ESM1-2-HR in the historical period (1979 to 2014)
./NOAA_data/CMIP6_GCMs/EC-Earth3                      # GCM EC-Earth3 
./NOAA_data/CMIP6_GCMs/EC-Earth3/ssp126               # GCM EC-Earth3 for the low emssion level ssp126(2015 to 2100)
./NOAA_data/CMIP6_GCMs/EC-Earth3/ssp585               # GCM EC-Earth3 for the high emssion level ssp585(2015 to 2100)
./NOAA_data/CMIP6_GCMs/EC-Earth3/historical           # GCM EC-Earth3 in the historical period (1979 to 2014)
./NOAA_data/CMIP6_GCMs/MRI-ESM2-0                     # GCM MRI-ESM2-0
./NOAA_data/CMIP6_GCMs/MRI-ESM2-0/ssp126              # GCM MRI-ESM2-0 for the low emssion level ssp126(2015 to 2100)
./NOAA_data/CMIP6_GCMs/MRI-ESM2-0/ssp585              # GCM MRI-ESM2-0 for the high emssion level ssp585(2015 to 2100)
./NOAA_data/CMIP6_GCMs/MRI-ESM2-0/historical          # GCM MRI-ESM2-0 in the historical period (1979 to 2014)
./NOAA_data/CMIP6_GCMs/IPSL-CM6A-LR                   # GCM IPSL-CM6A-LR                 
./NOAA_data/CMIP6_GCMs/IPSL-CM6A-LR/ssp126            # GCM IPSL-CM6A-LR for the low emssion level ssp126(2015 to 2100)
./NOAA_data/CMIP6_GCMs/IPSL-CM6A-LR/ssp585            # GCM IPSL-CM6A-LR for the high emssion level ssp585(2015 to 2100)
./NOAA_data/CMIP6_GCMs/IPSL-CM6A-LR/historical        # GCM IPSL-CM6A-LR in the historical period (1979 to 2014)
./NOAA_data/CMIP6_GCMs/GFDL-ESM4                      # GCM GFDL-ESM4                     
./NOAA_data/CMIP6_GCMs/GFDL-ESM4/ssp126               # GCM GFDL-ESM4 for the low emssion level ssp126(2015 to 2100)             
./NOAA_data/CMIP6_GCMs/GFDL-ESM4/ssp585               # GCM GFDL-ESM4 for the high emssion level ssp126(2015 to 2100)
./NOAA_data/CMIP6_GCMs/GFDL-ESM4/historical           # GCM GFDL-ESM4 in the historical period (1979 to 2014)
./NOAA_data/QDM                                       # All the BC/downscaled results through QDM
./NOAA_data/QDM/IPSL-CM6A-LR                          # BC/downscaled results for GCM IPSL-CM6A-LR                          
./NOAA_data/QDM/IPSL-CM6A-LR/ssp126                   # BC/downscaled results for GCM IPSL-CM6A-LR of ssp126(2015 to 2100) 
./NOAA_data/QDM/IPSL-CM6A-LR/ssp585                   # BC/downscaled results for GCM IPSL-CM6A-LR of ssp585(2015 to 2100)
./NOAA_data/QDM/EC-Earth3                             # BC/downscaled results for GCM EC-Earth3  
./NOAA_data/QDM/EC-Earth3/ssp126                      # BC/downscaled results for GCM EC-Earth3 of ssp126(2015 to 2100)                      
./NOAA_data/QDM/EC-Earth3/ssp585                      # BC/downscaled results for GCM EC-Earth3 of ssp585(2015 to 2100) 
./NOAA_data/QDM/MPI-ESM1-2-HR                         # BC/downscaled results for GCM MPI-ESM1-2-HR 
./NOAA_data/QDM/MPI-ESM1-2-HR/ssp126                  # BC/downscaled results for GCM MPI-ESM1-2-HR of ssp126(2015 to 2100)
./NOAA_data/QDM/MPI-ESM1-2-HR/ssp585                  # BC/downscaled results for GCM MPI-ESM1-2-HR of ssp585(2015 to 2100)
./NOAA_data/QDM/MRI-ESM2-0                            # BC/downscaled results for GCM MRI-ESM2-0 
./NOAA_data/QDM/MRI-ESM2-0/ssp126                     # BC/downscaled results for GCM MRI-ESM2-0 of ssp126(2015 to 2100)
./NOAA_data/QDM/MRI-ESM2-0/ssp585                     # BC/downscaled results for GCM MRI-ESM2-0 of ssp585(2015 to 2100)
./NOAA_data/QDM/GFDL-ESM4                             # BC/downscaled results for GCM GFDL-ESM4 
./NOAA_data/QDM/GFDL-ESM4/ssp126                      # BC/downscaled results for GCM GFDL-ESM4 of ssp126(2015 to 2100)
./NOAA_data/QDM/GFDL-ESM4/ssp585.                     # BC/downscaled results for GCM GFDL-ESM4 of ssp585(2015 to 2100)
```
