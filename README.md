# A-century-of-shifting-native-species-area-curves-reveals-long-term-biodiversity-loss

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

## Repository Structure
```
├── README.md                                                     # This file
├── LICENSE                                                       # License information
├── data/                                                         # Data used to produce the statistics and figures reported in the paper
│   └── processed/                                                # Processed data
├── metadata/
│   ├── 01.plot_data_grassland_nationalwide_std.csv               # Data cleaning and preparation
│   ├── 02.species_data_grassland_nationalwide_std.csv            # Statistical analyses
│   ├── 03.plot_data_forest_nationalwide_std.csv                  # Code for all figures
│   ├── 04.species_data_forest_nationalwide_std.csv               # Code for all figures
│   ├── 11.plot_data_forest_Natura2000_std.csv                    # Code for all figures
│   ├── 12.species_data_forest_Natura2000_std.csv                 # Code for all figures
│   ├── 13.plot_data_forest_Natura2000_std.csv                    # Code for all figures
│   ├── 14.species_data_forest_Natura2000_std.csv                 # Code for all figures
│   ├── 21.plot_data_forest_Non_Natura2000_std.csv                # Code for all figures
│   ├── 22.species_data_forest_Non_Natura2000_std.csv             # Code for all figures
│   ├── 23.plot_data_forest_Non_Natura2000_std.csv                # Code for all figures
│   ├── 24.species_data_forest_Non_Natura2000_std.csv             # Code for all figures
│   └── functions/                                                # Custom functions
├── code/
│   ├── 01_data_preparation.R                                     # Data cleaning and preparation
│   ├── 02_statistical_analysis.R                                 # Statistical analyses
│   ├── 03_figure_generation.R                                    # Code for all figures
│   └── functions/                                                # Custom functions
```

## Description

This repository contains all data, code, and metadata necessary to reproduce the analyses and figures presented in the manuscript "A century of shifting native species-area curves reveals long-term biodiversity loss" submitted to Ecology Letters (manuscript ID: ELE-01557-2025).

### Raw Data Files
See `metadata/data_dictionary.md` for complete variable descriptions, units, and definitions.

## Reproducibility

To reproduce all analyses and figures:

1. Clone this repository
2. Install required R packages (see below)
3. Set working directory to repository root
4. Run scripts in order:
```r
   source("code/01_data_preparation.R")
   source("code/02_statistical_analysis.R")
   source("code/03_figure_generation.R")
```

## Citation

If you use this data or code, please cite:

> Pan, [First Name] et al. (2025). A century of shifting native species-area curves reveals long-term biodiversity loss. *Ecology Letters*.

## License

This work is licensed under CC-BY-4.0
