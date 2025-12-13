# Data Dictionary

## Metadata for: A century of shifting native species-area curves reveals long-term biodiversity loss

**Manuscript ID:** ELE-01557-2025  
**Date Created:** 2025-12-10  
**Last Updated:** 2025-12-13  
**Document Version:** 1.0

---

## NATIONWIDE DATA

---

## File 01: plot_data_grassland_nationalwide_std.csv

### General Information

- **Description:** Plot data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 02: species_data_grassland_nationalwide_std.csv

### General Information

- **Description:** Species data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## File 03: plot_data_forest_nationalwide_std.csv

### General Information

- **Description:** Plot data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 04: species_data_forest_nationalwide_std.csv

### General Information

- **Description:** Species data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## NATURA2000 PROTECTED AREAS

---

## File 11: plot_data_grassland_Natura2000_std.csv

### General Information

- **Description:** Plot data for measuring grassland species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** Natura2000 areas, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 12: species_data_grassland_Natura2000_std.csv

### General Information

- **Description:** Species data for measuring grassland species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## File 13: plot_data_forest_Natura2000_std.csv

### General Information

- **Description:** Plot data for measuring forest species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** Natura2000 areas, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 14: species_data_forest_Natura2000_std.csv

### General Information

- **Description:** Species data for measuring forest species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## NON-NATURA2000 AREAS

---

## File 21: plot_data_grassland_Non_Natura2000_std.csv

### General Information

- **Description:** Plot data for measuring grassland species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** Non-Natura2000 areas, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 22: species_data_grassland_Non_Natura2000_std.csv

### General Information

- **Description:** Species data for measuring grassland species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## File 23: plot_data_forest_Non_Natura2000_std.csv

### General Information

- **Description:** Plot data for measuring forest species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** Non-Natura2000 areas, The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

## File 24: species_data_forest_Non_Natura2000_std.csv

### General Information

- **Description:** Species data for measuring forest species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 3
- **Date range:** 1930-2017

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## Summary Table of All Data Files

| File ID | Filename | Habitat | Region | Data Level | Columns |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |
| 01 | plot_data_grassland_nationalwide_std.csv | Grassland | Nationwide | Plot | 5 |
| 02 | species_data_grassland_nationalwide_std.csv | Grassland | Nationwide | Species | 3 |
| 03 | plot_data_forest_nationalwide_std.csv | Forest | Nationwide | Plot | 5 |
| 04 | species_data_forest_nationalwide_std.csv | Forest | Nationwide | Species | 3 |
| 11 | plot_data_grassland_Natura2000_std.csv | Grassland | Natura2000 | Plot | 5 |
| 12 | species_data_grassland_Natura2000_std.csv | Grassland | Natura2000 | Species | 3 |
| 13 | plot_data_forest_Natura2000_std.csv | Forest | Natura2000 | Plot | 5 |
| 14 | species_data_forest_Natura2000_std.csv | Forest | Natura2000 | Species | 3 |
| 21 | plot_data_grassland_Non_Natura2000_std.csv | Grassland | Non-Natura2000 | Plot | 5 |
| 22 | species_data_grassland_Non_Natura2000_std.csv | Grassland | Non-Natura2000 | Species | 3 |
| 23 | plot_data_forest_Non_Natura2000_std.csv | Forest | Non-Natura2000 | Plot | 5 |
| 24 | species_data_forest_Non_Natura2000_std.csv | Forest | Non-Natura2000 | Species | 3 |

---

## Additional Information

### Coordinate Reference System

- Projection: RD New (EPSG:28992) for Netherlands or WGS84 (EPSG:4326)
- Units: Meters (X, Y coordinates)

### Time Periods

Data are grouped into three temporal periods:
- **Early period:** 1930-1959
- **Middle period:** 1960-1989
- **Recent period:** 1990-2017

### Spatial Coverage

- **Country:** The Netherlands
- **Natura2000 areas:** EU protected nature areas under the Birds and Habitats Directives
- **Non-Natura2000 areas:** Areas outside protected designations

### Plot Size Ranges

- **Grassland plots:** 1-100 m²
- **Forest plots:** 100-1000 m²

### Data Structure

- **Plot data files** contain environmental and spatial information for each sampling location
- **Species data files** contain lists of species observed at each plot (linked via eventID)
- Files can be joined using the eventID field

---

**End of Data Dictionary**
