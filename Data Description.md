# Data Description
Every line contains the complete dataset for one building.
For the public version the house numbers, shape, and centroid were removed.

# Columns 
|Column name | Description |
|---|--|
|Shape	| geoshape of the building |
|Centroid | GPS-location of the building centroid |
|MinHeight| minimum heigt of the building|
|MaxHeight|  maximumg height of the building|	
|NumOfObj|  number of dwellings in the building |	
|StreetName|  name of the street |
|HouseNr| house number of the building
|BuildingType| type of building (e.g. single building, apartment bloc |
|ResidentialArea| residentail area in the building in m² |
|OtherArea	| non-residential area in the building in m² |
|YearOfConstr|	year of construction |
|NumOfFloors	| number of floors |
|YearCat	| year category according to TABULA Webtool |
|TypeCat	| type category according to TABULA Webtool |
|SpecResHD|	specific residential heating demand in kWh/m²/year |
|ResHD	| total residential heating demand per year in kWh/year |
|ThermalCond	| generalized thermal conductance |
|ThermalStorageCap |	generalized thermal storage capacity |
|MaxHeatPower	| maximum heating power for that building |
|HeatingTimeSeries_i  | hourly heating demand for the hour i = {1,...,8760} |

