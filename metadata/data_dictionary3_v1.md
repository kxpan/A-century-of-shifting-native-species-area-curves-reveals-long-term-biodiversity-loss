# Data Dictionary

## Metadata for: A century of shifting native species-area curves reveals long-term biodiversity loss

**Manuscript ID:** ELE-01557-2025  
**Date Created:** 2025-12-10  
**Last Updated:** 2025-12-13  
**Document Version:** 1.0

---

## Overview of Data Files

This repository contains **24 data files** organized by:
- **Habitat type:** Grassland vs. Forest
- **Geographic scope:** Nationwide, Natura2000 protected areas, Non-Natura2000 areas
- **Data level:** Plot-level data vs. Species-level data

### File Naming Convention
Files are numbered as: `[ID].[type]_data_[habitat]_[region]_std.csv`

**Categories:**
- **01-04:** Nationwide data (Grassland: 01-02, Forest: 03-04)
- **11-14:** Natura2000 protected areas (Grassland: 11-12, Forest: 13-14)
- **21-24:** Non-Natura2000 areas (Grassland: 21-22, Forest: 23-24)

---

## NATIONWIDE DATA

### File 01: plot_data_grassland_nationalwide_std.csv

**General Information:**
- **Description:** Plot data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 02: species_data_grassland_nationalwide_std.csv

**General Information:**
- **Description:** Species data for measuring grassland species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

### File 03: plot_data_forest_nationalwide_std.csv

**General Information:**
- **Description:** Plot data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 04: species_data_forest_nationalwide_std.csv

**General Information:**
- **Description:** Species data for measuring forest species-area curves across different time periods over the whole Netherlands
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## NATURA2000 PROTECTED AREAS

### File 11: plot_data_grassland_Natura2000_std.csv

**General Information:**
- **Description:** Plot data for measuring grassland species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** Natura2000 areas, The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 12: species_data_grassland_Natura2000_std.csv

**General Information:**
- **Description:** Species data for measuring grassland species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

### File 13: plot_data_forest_Natura2000_std.csv

**General Information:**
- **Description:** Plot data for measuring forest species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** Natura2000 areas, The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 14: species_data_forest_Natura2000_std.csv

**General Information:**
- **Description:** Species data for measuring forest species-area curves across different time periods in Natura2000 protected areas
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## NON-NATURA2000 AREAS

### File 21: plot_data_grassland_Non_Natura2000_std.csv

**General Information:**
- **Description:** Plot data for measuring grassland species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Grassland (plot size 1-100 m²)
- **Geographic coverage:** Non-Natura2000 areas, The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 22: species_data_grassland_Non_Natura2000_std.csv

**General Information:**
- **Description:** Species data for measuring grassland species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

### File 23: plot_data_forest_Non_Natura2000_std.csv

**General Information:**
- **Description:** Plot data for measuring forest species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 5
- **Date range:** 1930-2017
- **Habitat type:** Forest (plot size 100-1000 m²)
- **Geographic coverage:** Non-Natura2000 areas, The Netherlands

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |
| sampleSizeValue | numeric | m² | Size of sampled area |
| geometry | numeric | meters | X and Y coordinates (longitude and latitude of site centroid) |
| region_id | integer | - | K-means spatial region assignment for each plot |

---

### File 24: species_data_forest_Non_Natura2000_std.csv

**General Information:**
- **Description:** Species data for measuring forest species-area curves across different time periods in non-Natura2000 areas
- **Number of columns:** 3
- **Date range:** 1930-2017

**Column Descriptions:**

| Column Name | Data Type | Units | Description |
|-------------|-----------|-------|-------------|
| eventID | character | - | Unique identifier for each sampling plot (matches plot data) |
| scientificName | character | - | Scientific name of recorded species in each sampling plot |
| time_period | character | - | Time period of observation (1930-1959, 1960-1989, 1990-2017) |

---

## Summary Table of All Data Files

| File ID | Filename | Habitat | Region | Data Level | Rows | Columns |
|---------|----------|---------|--------|------------|------|---------|
| 01 | plot_data_grassland_nationalwide_std.csv | Grassland | Nationwide | Plot | - | 5 |
| 02 | species_data_grassland_nationalwide_std.csv | Grassland | Nationwide | Species | - | 3 |
| 03 | plot_data_forest_nationalwide_std.csv | Forest | Nationwide | Plot | - | 5 |
| 04 | species_data_forest_nationalwide_std.csv | Forest | Nationwide | Species | - | 3 |
| 11 | plot_data_grassland_Natura2000_std.csv | Grassland | Natura2000 | Plot | - | 5 |
| 12 | species_data_grassland_Natura2000_std.csv | Grassland | Natura2000 | Species | - | 3 |
| 13 | plot_data_forest_Natura2000_std.csv | Forest | Natura2000 | Plot | - | 5 |
| 14 | species_data_forest_Natura2000_std.csv | Forest | Natura2000 | Species | - | 3 |
| 21 | plot_data_grassland_Non_Natura2000_std.csv | Grassland | Non-Natura2000 | Plot | - | 5 |
| 22 | species_data_grassland_Non_Natura2000_std.csv | Grassland | Non-Natura2000 | Species | - | 3 |
| 23 | plot_data_forest_Non_Natura2000_std.csv | Forest | Non-Natura2000 | Plot | - | 5 |
| 24 | species_data_forest_Non_Natura2000_std.csv | Forest | Non-Natura2000 | Species | - | 3 |

---

## Additional Information

### Coordinate Reference System
- **Projection:** [Specify - likely RD New (EPSG:28992) for Netherlands or WGS84 (EPSG:4326)]
- **Units:** Meters (X, Y coordinates)

### Time Periods
Data are grouped into three temporal periods:
- **Early period:** 1930-1959 (30 years)
- **Middle period:** 1960-1989 (30 years)
- **Recent period:** 1990-2017 (28 years)

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
- Files can be joined using the `eventID` field

### Taxonomic Information
- Species names follow standard botanical nomenclature
- **Taxonomic authority:** [Specify source, e.g., "The Plant List", "World Flora Online", or "Dutch Flora"]
- **Taxonomy date:** [Specify version or date]

### Missing Data
- Missing values are coded as: `NA`
- Some historical records may lack complete spatial information

### Data Quality
- All data have been standardized and quality-checked
- Spatial coordinates verified for accuracy
- Species names validated against current taxonomy

---

## Data Processing Notes

### Standardization Steps
1. Species names standardized to current accepted taxonomy
2. Coordinates transformed to common reference system
3. Plot sizes verified and outliers checked
4. Temporal assignment validated
5. Regional classifications applied (k-means clustering for region_id)

### Known Limitations
1. Sampling effort may vary across time periods
2. Historical records (1930-1959) may have less complete metadata
3. Detection probability may differ between observers and time periods
4. Plot size ranges differ between grassland and forest habitats

---

## Usage Notes

### Linking Plot and Species Data
To combine plot-level and species-level data:

```r
# Example in R
plot_data <- read.csv("01.plot_data_grassland_nationalwide_std.csv")
species_data <- read.csv("02.species_data_grassland_nationalwide_std.csv")

# Join by eventID
combined_data <- left_join(species_data, plot_data, by = "eventID")
```

### Calculating Species Richness
Species richness per plot can be calculated by counting unique species per eventID:

```r
richness <- species_data %>%
  group_by(eventID) %>%
  summarise(species_richness = n_distinct(scientificName))
```

---

## Contact Information

For questions about this metadata or data files:
- **Name:** [Your name]
- **Email:** [Your email]
- **Institution:** [Your institution]
- **ORCID:** [Your ORCID if available]

---

## References

[Add relevant citations for data sources, taxonomic authorities, or related publications]

---

## Acknowledgments

[Add acknowledgments for data contributors, funding sources, or institutions]

---

**End of Data Dictionary**
