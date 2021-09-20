<<<<<<< HEAD
## Summary  
The Housing Inventory dataset is an attempt to adapt the county assessor tax parcel data for Utah’s most urban counties, to present additional, standardized information about the type of housing units, land that is associated with them, and related short-term and long-term trends.  

## Description  
This dataset was created from the [Land Information Record (LIR) parcel shapefiles](https://gis.utah.gov/data/cadastre/parcels/) by the Utah Geospatial Resource Center (UGRC), the state’s GIS coordination office. The LIR shapefiles were made possible by the sharing of the annual  tax assessment parcel GIS layer by each County Assessor. The currency of the data is as of midnight Jan 1st for the specified year. The tax parcel information is then finalized in late May and is typically made available for distribution in LIR format later in the summer of the same year.  

WFRC, as the metropolitan planning organization (MPO) covering the urban portions of Salt Lake County, Davis County, and Weber county, prepared the 2020 Housing Inventory dataset for these counties by performing the manual and semi-automated GIS-based operations, listed below, to the original LIR data  

Applying apartment unit counts to multi-family rental properties that do not have individually-owned and platted units (traditional apartment buildings, quadplexes, triplexes, mixed use buildings etc). These counts were informed in part by the [Address Point data layer](https://gis.utah.gov/data/location/address-data/) also published by UGRC.  

For cases where individual condos units, townhome units, and single family homes have associated common areas, these properties were rolled into a single composite parcel record and shape that combines the individual units and common areas into a single record and shape. For the composite record, the appropriate type of units was preserved and aggregated characteristics, values, and unit counts were established. The main purpose of this operation is to better characterize the density of residential land use (dwelling units per acre or DUA). 


Residential parcel types are often differentiated in detail within the Assessor records. For the Housing Inventory these were summarized into the following categories:  
- townhouses
- condos
- apartment
- single family
- duplex
- mixed use (commercial and residential)
- mobile home
- pud (mixed)
- group quarters  

The housing does <ins>not<ins> include the following parcel types in its summary:  
- Nursing or retirement homes
- Extended stay hotels
- Student housing or dormitories  


For more information contact analytics@wfrc.org  
 
Tags: Utah, Housing, Land Use, Parcels, Cadastre, Economy, Planning  
=======
# Housing-Unit-Inventory
Create housing unit inventory for Utah counties using LIR Parcels and other miscellaneous boundary layers
- organizes parcel attributes like total market value, building square footage, number of floors, etc.
- groups propertys contained by common space, summarizing relevant attributes  

Types:
- single_family
- multi_family

Subtypes:
- single_family (no hoa)
- pud (single family w/ hoa)
- duplex
- apartment
- condo
- mixed
- mobile_home_park
>>>>>>> 78fc913812218febd189b05fa0dc11fd4db3ba72

