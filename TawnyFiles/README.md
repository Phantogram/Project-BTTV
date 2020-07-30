# Project-BTTV

## Notebooks: 

### Step 1 Geo
#### Geo Locations USA States By County (notebook)
This notebook starts with CDC data of cancer death rates and merges it with lat and lons to store geo locations for mapping. The dataframe is outputed as "Geo out" and is imported in Step 2 Census by county

### Step 2 Census
#### Census by County (notebook)
This notebook starts with "Geo out" and merges it with census data. The dataframe is outputed as "Census out" and is imported in Step 3 HRSA by county

#### Census by State (notebook)
This notebook starts with CDC data of cancer death and merges it with census data.

### Step 3 HRSA
#### Underservice(notebook)
This notebook starts "Census out" and merges it with Health Resources and Services Administration data to determin medical underserviced corrilations.

## Resrouce Library: 

### Resource file name: USCS_OverviewMap

#### Topic: Death Rates by State

Source: United States Cancer Statistics: Data Visualizations
https://gis.cdc.gov/Cancer/USCS/DataViz.html

All Types of Cancer, All Ages, All Races/Ethnicities, Male and Female
Rate per 100,000 people



### Resource file name: BYAREA_COUNTY

##### Topic: Death Rates by County (and State)

Source: United States Cancer Statistics (USCS) 1999–2017 zip icon[ZIP-39.5MB]
https://www.cdc.gov/cancer/uscs/dataviz/download_data.htm




### Resource file name: Resource file name: Data_Explorer_Dataset_MedicalUnderservice_2014_2018

#### Topic: Index of Medical Underservice Score & Providers per 100,000

Source: Health Care Facilities (CMS): Medically Underserved Areas/Populations (MUA/P)

orginal file name: Data_Explorer_Dataset
https://data.hrsa.gov/tools/data-explorer