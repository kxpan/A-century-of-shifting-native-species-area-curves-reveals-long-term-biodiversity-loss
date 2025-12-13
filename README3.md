# A century of shifting native species-area curves reveals long-term biodiversity loss

**Manuscript ID:** ELE-01557-2025  
**DOI:** 10.17605/OSF.IO/XXXXXXX (or Zenodo DOI if applicable)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

---

## Description

This repository contains all data, code, and metadata necessary to reproduce the analyses and figures presented in the manuscript "A century of shifting native species-area curves reveals long-term biodiversity loss" submitted to Ecology Letters (manuscript ID: ELE-01557-2025).

---

## Repository Structure

### Main Files
- `README.md` - This file (project overview)
- `LICENSE` - CC-BY-4.0 license information

### Data Files (`data/`) - Data ready for analysis
**Grassland Data (Nationwide):**
- `01.plot_data_grassland_nationalwide_std.csv` - Plot-level grassland data (nationwide)
- `02.species_data_grassland_nationalwide_std.csv` - Species-level grassland data (nationwide)

**Forest Data (Nationwide):**
- `03.plot_data_forest_nationalwide_std.csv` - Plot-level forest data (nationwide)
- `04.species_data_forest_nationalwide_std.csv` - Species-level forest data (nationwide)

**Grassland Data (Natura2000 Protected Areas):**
- `11.plot_data_forest_Natura2000_std.csv` - Plot-level forest data (Natura2000)
- `12.species_data_forest_Natura2000_std.csv` - Species-level forest data (Natura2000)

**Forest Data (Natura2000 Protected Areas):**
- `13.plot_data_forest_Natura2000_std.csv` - Additional plot data (Natura2000)
- `14.species_data_forest_Natura2000_std.csv` - Additional species data (Natura2000)

**Grassland Data (Non-Natura2000 Areas):**
- `21.plot_data_forest_Non_Natura2000_std.csv` - Plot-level forest data (non-protected)
- `22.species_data_forest_Non_Natura2000_std.csv` - Species-level forest data (non-protected)
**Forest Data (Non-Natura2000 Areas):**
- `23.plot_data_forest_Non_Natura2000_std.csv` - Additional plot data (non-protected)
- `24.species_data_forest_Non_Natura2000_std.csv` - Additional species data (non-protected)

### Metadata Files (`metadata/`)

### Code Files (`code/`)
- `01_data_preparation.R` - Data cleaning and preparation
- `02_statistical_analysis.R` - Statistical analyses
- `03_figure_generation.R` - Code to generate all figures

---

## Data Description

### Data Files Overview

The dataset includes both plot-level and species-level data for:
- **Grassland habitat** in three categories:
  - Nationwide (all forests)
  - Natura2000 protected areas
  - Non-Natura2000 areas (unprotected)
- **Forest habitat** in three categories:
  - Nationwide (all forests)
  - Natura2000 protected areas
  - Non-Natura2000 areas (unprotected)

### Metadata

Complete variable descriptions, units, and definitions are available in:
- `metadata/data_dictionary.md`

---

## Code Description

All analyses were performed in R. Scripts should be run in numerical order:

1. **01_data_preparation.R** - Loads raw data, performs quality checks, standardizes data formats
2. **02_statistical_analysis.R** - Implements all statistical models and tests reported in the manuscript
3. **03_figure_generation.R** - Generates all figures included in the manuscript

---

## Reproducibility

To reproduce all analyses and figures:

1. Download or clone this repository
2. Set working directory to repository root
3. Run scripts in order:

```r
source("code/01_data_preparation.R")
source("code/02_statistical_analysis.R")
source("code/03_figure_generation.R")
```

All outputs (figures and results) will be saved to their respective directories.

---

**Last Updated:** December 2025  
**Version:** 1.0

