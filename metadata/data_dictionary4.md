# Data Dictionary

## Metadata for: A century of shifting native species-area curves reveals long-term biodiversity loss

**Manuscript ID:** ELE-01557-2025  
**Date Created:** 2025-12-10  
**Last Updated:** 2025-12-13  
**Document Version:** 1.0

---

## DATA

---

## File : plot_data.shp

### General Information

- **Description:** Plot data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 6
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²), Forest (plot size 100-1000 m²)
- **Geographic coverage:** The Netherlands

### Column Descriptions

| Column Name | Data Type | Units | Description |
| --- | --- | --- | --- |
|  |  |  |  |
| eventID | character | - | Unique identifier for each sampling plot |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| Year30 | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| Region | integer | - | Whether it is Nationwide, within Natura2000 protected areas (Natura2000) or outside Natura2000 protected areas (Non_Natura2000) |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |

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

---

**End of Data Dictionary**
