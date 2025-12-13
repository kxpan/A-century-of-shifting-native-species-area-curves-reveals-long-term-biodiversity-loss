# Data Dictionary

## Metadata for: A century of shifting native species-area curves reveals long-term biodiversity loss

**Date Created**: 2025-12-10  
**Last Updated**: 2025-12-13

## Data: 01.plot_data_grassland_nationalwide_std.csv
## Data: 02.species_data_grassland_nationalwide_std.csv

## Data: 03.plot_data_forest_nationalwide_std.csv
## Data: 04.species_data_forest_nationalwide_std.csv


## Data: 11.plot_data_forest_Natura2000_std.csv
## Data: 12.species_data_forest_Natura2000_std.csv


## Data: 13.plot_data_forest_Natura2000_std.csv
## Data: 14.species_data_forest_Natura2000_std.csv


## Data: 21.plot_data_forest_Non_Natura2000_std.csv
## Data: 22.species_data_forest_Non_Natura2000_std.csv


## Data: 23.plot_data_forest_Non_Natura2000_std.csv
## Data: 24.species_data_forest_Non_Natura2000_std.csv


---

## Data: 01.plot_data_grassland_nationalwide_std.csv  

### General Information
- **Description**: Plot data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Grassland (plot size 1-100 m2)
- **Geographic coverage**: The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 02.species_data_grassland_nationalwide_std.csv

### General Information
- **Description**: Species data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Data: 03.plot_data_forest_nationalwide_std.csv  

### General Information
- **Description**: Plot data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Forest (plot size 100-1000 m2)
- **Geographic coverage**: The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 04.species_data_forest_nationalwide_std.csv

### General Information
- **Description**: Species data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Data: 11.plot_data_grassland_Natura2000_std.csv  

### General Information
- **Description**: Plot data for measuring grassland species-area curves across different time periods over Natura2000 areas in the Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Grassland (plot size 1-100 m2)
- **Geographic coverage**: Natura 2000, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 12.species_data_grassland_Natura2000_std.csv

### General Information
- **Description**: Species data for measuring grassland species-area curves across different time periods over Natura2000 areas in the Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Data: 13.plot_data_forest_Natura2000_std.csv  

### General Information
- **Description**: Plot data for measuring forest species-area curves across different time periods over Natura2000 areas in the Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Forest (plot size 100-1000 m2)
- **Geographic coverage**: Natura 2000, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 14.species_data_forest_Natura2000_std.csv

### General Information
- **Description**: Species data for measuring forest species-area curves across different time periods over Natura2000 areas in the Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Data: 21.plot_data_grassland_Non_Natura2000_std.csv  

### General Information
- **Description**: Plot data for measuring grassland species-area curves across different time periods over Non-Natura2000 areas in the Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Grassland (plot size 1-100 m2)
- **Geographic coverage**: Non-Natura 2000, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 22.species_data_grassland_Non_Natura2000_std.csv

### General Information
- **Description**: Species data for measuring grassland species-area curves across different time periods over Non-Natura2000 areas in the Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Data: 23.plot_data_forest_Non_Natura2000_std.csv  

### General Information
- **Description**: Plot data for measuring forest species-area curves across different time periods over Non-Natura2000 areas in the Netherlands
- **Number of columns**: 5
- **Date range**: 1930-2017
- **Habitat type**: Forest (plot size 100-1000 m2)
- **Geographic coverage**: Natura 2000, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |
| sampleSizeValue | numeric | m2 | Size of sampled area |
| geometry | numeric | x and y in meter | Longitude and Latitude of site centroid |
| region_id | integer | count | k-mean spatial region where each plot is assigned to |

---

## Data: 24.species_data_forest_Non_Natura2000_std.csv

### General Information
- **Description**: Species data for measuring forest species-area curves across different time periods over Non-Natura2000 areas in the whole Netherlands
- **Number of columns**: 3
- **Date range**: 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | scientificName of recorded species in each sampling plot | 
| time_period | character | Time period: 1930-1959, 1960-1989, 1990-2017 | Time period of observation |

---

## Additional Information

### Raw data
- Species names follow [Specify taxonomic authority, e.g., "Plants of the World Online" or specific taxonomic database]
- Taxonomy as of [date]

---

## References

[List any publications or databases that should be cited when using this data]

---

**Document Version**: 1.0  
**Last Updated**: 2025-12-10

