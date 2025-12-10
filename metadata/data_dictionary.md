# Data Dictionary

## Metadata for: A century of shifting native species-area curves reveals long-term biodiversity loss

**Date Created**: 2025-12-10  
**Last Updated**: 2025-12-10

---

## File: species_area_data.csv

### General Information
- **Description**: Species richness measurements across different spatial scales and time periods
- **Number of rows**: [N] (excluding header)
- **Number of columns**: [N]
- **Missing data code**: NA
- **Date range**: 1920-2020
- **Geographic coverage**: [Specify region, coordinates if applicable]
- **Taxonomic coverage**: [Specify taxa included]

### Column Descriptions

| Column Name | Data Type | Units | Description | Valid Range/Values | Notes |
|-------------|-----------|-------|-------------|-------------------|-------|
| site_id | character | - | Unique identifier for each sampling site | Alphanumeric | Format: SITE_XXX |
| year | integer | years | Year of observation | 1920-2020 | - |
| sampling_date | date | YYYY-MM-DD | Exact date of sampling | - | May be NA for historical records |
| area | numeric | hectares | Size of sampled area | > 0 | - |
| species_richness | integer | count | Total number of native species observed | ≥ 0 | - |
| latitude | numeric | decimal degrees | Latitude of site centroid | -90 to 90 | WGS84 datum |
| longitude | numeric | decimal degrees | Longitude of site centroid | -180 to 180 | WGS84 datum |
| habitat_type | character | - | Primary habitat classification | [List valid categories] | Categories: forest, grassland, wetland, etc. |
| native_only | logical | - | TRUE if only native species counted | TRUE/FALSE | - |
| sampling_effort | numeric | person-hours | Total sampling effort | > 0 | May be NA for historical data |
| observer | character | - | Name or ID of primary observer | - | Anonymized for historical records |
| data_source | character | - | Source of data record | [List sources] | See references below |
| quality_flag | character | - | Data quality indicator | high/medium/low | See quality criteria below |

### Quality Flags
- **high**: Modern standardized survey with complete metadata
- **medium**: Partial metadata or non-standardized protocol
- **low**: Historical record with limited documentation

### Data Sources
1. **modern_surveys**: Contemporary field surveys conducted 2000-2020
2. **historical_literature**: Published records from 1920-1999
3. **museum_records**: Natural history museum specimen records
4. **[Add other sources]**: [Description]

---

## File: historical_records.csv

### General Information
- **Description**: Historical biodiversity records used for temporal comparisons
- **Number of rows**: [N]
- **Number of columns**: [N]
- **Missing data code**: NA

### Column Descriptions

| Column Name | Data Type | Units | Description | Valid Range/Values | Notes |
|-------------|-----------|-------|-------------|-------------------|-------|
| record_id | character | - | Unique record identifier | Alphanumeric | Format: HIST_XXXX |
| year | integer | years | Year of record | 1920-2020 | - |
| location | character | - | Site or region name | - | Text description |
| species_list | character | - | Pipe-separated list of species | - | Format: Species1\|Species2\|... |
| species_count | integer | count | Number of species in record | ≥ 0 | - |
| source_type | character | - | Type of historical source | [List types] | publication/specimen/field_note |
| reliability | character | - | Estimated reliability of record | high/medium/low | Based on source quality |
| notes | character | - | Additional contextual information | - | Free text |

---

## File: processed/cleaned_data.csv

### General Information
- **Description**: Data after quality control and standardization (optional intermediate file)
- **Processing steps**: 
  1. Removed records with quality_flag = "low"
  2. Standardized species names to current taxonomy
  3. Calculated area-standardized richness
  4. [Add other processing steps]

### Additional Columns (beyond those in raw data)

| Column Name | Data Type | Units | Description | Calculation |
|-------------|-----------|-------|-------------|-------------|
| std_richness | numeric | species per 100 ha | Area-standardized species richness | species_richness / (area / 100) |
| decade | integer | - | Decade of observation | floor(year / 10) * 10 |
| time_period | character | - | Categorical time period | early (1920-1959), mid (1960-1989), recent (1990-2020) |

---

## Additional Information

### Taxonomic Authority
- Species names follow [Specify taxonomic authority, e.g., "Plants of the World Online" or specific taxonomic database]
- Taxonomy as of [date]

### Coordinate Reference System
- WGS84 (EPSG:4326)

### Data Collection Methods
[Describe standardized protocols, if any]

### Known Limitations
1. [List any known data limitations]
2. Temporal variation in sampling effort
3. Potential observer bias in historical records
4. [Add other limitations]

### Changes from Original Data Sources
[If data were modified from cited sources, describe transformations]

---

## References

[List any publications or databases that should be cited when using this data]

---

## Contact Information

For questions about this metadata:
- **Name**: [Your name]
- **Email**: [Your email]
- **Institution**: [Your institution]

**Document Version**: 1.0  
**Last Updated**: 2025-12-10
