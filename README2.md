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

### Data Files (`data/`)
- `processed/` - Processed data ready for analysis

### Metadata Files (`metadata/`)

**Grassland Data:**
- `01.plot_data_grassland_nationalwide_std.csv` - Plot-level grassland data (nationwide)
- `02.species_data_grassland_nationalwide_std.csv` - Species-level grassland data (nationwide)

**Forest Data (Nationwide):**
- `03.plot_data_forest_nationalwide_std.csv` - Plot-level forest data (nationwide)
- `04.species_data_forest_nationalwide_std.csv` - Species-level forest data (nationwide)

**Forest Data (Natura2000 Protected Areas):**
- `11.plot_data_forest_Natura2000_std.csv` - Plot-level forest data (Natura2000)
- `12.species_data_forest_Natura2000_std.csv` - Species-level forest data (Natura2000)
- `13.plot_data_forest_Natura2000_std.csv` - Additional plot data (Natura2000)
- `14.species_data_forest_Natura2000_std.csv` - Additional species data (Natura2000)

**Forest Data (Non-Natura2000 Areas):**
- `21.plot_data_forest_Non_Natura2000_std.csv` - Plot-level forest data (non-protected)
- `22.species_data_forest_Non_Natura2000_std.csv` - Species-level forest data (non-protected)
- `23.plot_data_forest_Non_Natura2000_std.csv` - Additional plot data (non-protected)
- `24.species_data_forest_Non_Natura2000_std.csv` - Additional species data (non-protected)

### Code Files (`code/`)
- `01_data_preparation.R` - Data cleaning and preparation
- `02_statistical_analysis.R` - Statistical analyses
- `03_figure_generation.R` - Code to generate all figures
- `functions/` - Custom helper functions

---

## Data Description

### Data Files Overview

The dataset includes both plot-level and species-level data for:
- **Grassland ecosystems** (nationwide coverage)
- **Forest ecosystems** in three categories:
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

### Required R Packages

```r
# Install required packages
install.packages(c("tidyverse", "lme4", "nlme", "ggplot2", "cowplot"))

# Load packages
library(tidyverse)  # Data manipulation
library(lme4)       # Mixed-effects models
library(nlme)       # Linear and nonlinear mixed effects models
library(ggplot2)    # Visualization
library(cowplot)    # Figure arrangement
```

---

## Reproducibility

To reproduce all analyses and figures:

1. Download or clone this repository
2. Install required R packages (see above)
3. Set working directory to repository root
4. Run scripts in order:

```r
source("code/01_data_preparation.R")
source("code/02_statistical_analysis.R")
source("code/03_figure_generation.R")
```

All outputs (figures and results) will be saved to their respective directories.

---

## Data Availability

- **Processed data:** Available in `data/processed/` directory
- **Metadata files:** Available in `metadata/` directory with detailed descriptions
- **Complete documentation:** See `metadata/data_dictionary.md` for full variable descriptions
- **License:** CC-BY-4.0 (see LICENSE file)

---

## Citation

If you use this data or code, please cite:

**Manuscript:**
> Pan, [First Name] et al. (2025). A century of shifting native species-area curves reveals long-term biodiversity loss. *Ecology Letters*.

**Data and Code Repository:**
> Pan, [First Name] et al. (2025). Data and code for: A century of shifting native species-area curves reveals long-term biodiversity loss [Data set]. Open Science Framework. https://doi.org/10.17605/OSF.IO/XXXXXXX

---

## License

This work is licensed under **Creative Commons Attribution 4.0 International (CC-BY-4.0)**.

You are free to:
- **Share** - copy and redistribute the material in any medium or format
- **Adapt** - remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** - You must give appropriate credit, provide a link to the license, and indicate if changes were made

Full license details: http://creativecommons.org/licenses/by/4.0/

---

## Contact

For questions about the data or code, please contact:

- **Name:** [Your Name]
- **Email:** [Your Email]
- **Institution:** [Your Institution]
- **ORCID:** [Your ORCID if available]

---

## Funding

[Add funding acknowledgments if applicable]

---

## Additional Information

- **Geographic Coverage:** Netherlands (based on Natura2000 references)
- **Temporal Coverage:** [Add time period covered by data]
- **Taxonomic Coverage:** [Specify plant groups or taxa included]
- **Data Collection Methods:** [Brief description or reference to methods section]

---

**Last Updated:** December 2024  
**Version:** 1.0
