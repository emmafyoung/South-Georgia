- - - -
# South Georgia Oceanographic Model
NEMO regional configuration for South Georgia
- - - -

## Introduction
A regional oceanographic model for the South Georgia region has been developed to undertake analyses on the spatial and temporal variability in the regional oceanography, the key drivers of this variability, and the impact on the distribution of exploited species. The model development was funded by the UK Foreign, Commonwealth and Development Office. The underlying model system is NEMO (Nucleus for European Modelling of the Ocean; <https://www.nemo-ocean.eu/>), which has been widely adopted by the European scientific community for a range of modelling studies from regional to global scales. NEMO is a highly versatile modelling system, and includes a range of options for model parameterisation that enables good representation of regions characterised by complex bathymetry and precipitous shelf-edges.

## Model Overview

The South Georgia regional model extends from 58°S, 49°W to 48°S, 30°W, with bathymetry derived from GEBCO2014 and a high-resolution dataset for the South Georgia shelf compiled by Hogg et al. (Figure 1). The model has a horizontal resolution of 1/20° longitude by 1/40° latitude (~2.5 - 3km, varying with latitude). The vertical dimension is represented by 75 levels arranged as partial-cell z-levels, and with variable cell depth such that vertical resolution is enhanced over the shallow shelf regions. The models are forced at the open boundaries with tides from a global tidal model (TPXO7.2), and with barotropic flows, sea surface height, temperature and salinity from a global application of NEMO at 1/12° horizontal resolution. Atmospheric forcing is derived from reanalysis (DFS5.2). Climatological spatially-varying terrestrial freshwater input is included using a theoretical description of the seasonal melt cycle based on historical temperature and precipitation data. The model has been run for 1992-2012 with simulated sea surface height, mixed layer depth, 3D temperature, salinity and velocities saved as 5-day mean fields.

![](SGmodel_bathy_4git.png)
#### Figure 1: Model bathymetry; black contours are at 500, 1000 and 2500 m.
