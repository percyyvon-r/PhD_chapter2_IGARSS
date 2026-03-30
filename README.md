# PhD Chapter 2: IGARSS - Land Surface Temperature Analysis

This repository contains the analysis code and data for Chapter 2 of my PhD thesis, focusing on Land Surface Temperature (LST) variations between summer and winter seasons across different land cover types. The work is prepared for presentation at the IEEE International Geoscience and Remote Sensing Symposium (IGARSS).

## Project Overview

The analysis investigates spatial and temporal patterns in land surface temperature, particularly:
- Seasonal differences (Summer vs Winter LST)
- Land cover type influences on temperature gradients
- Zonal statistics and buffer analysis
- Radial temperature patterns

## Repository Structure

```
├── data/
│   ├── csv/           # Processed CSV data files
│   ├── dbf/           # Database files from ArcGIS
│   ├── igarss/        # ArcGIS project files
│   ├── raster/        # LST raster data (GeoTIFF)
│   └── shapefile/     # Vector data files
├── notebook/
│   └── analysis.ipynb # Main Python analysis notebook
├── output/
│   ├── figures/       # Generated plots and visualizations
│   └── table/         # Statistical tables and results
├── scripts/
│   └── R/             # R scripts for additional analysis
├── requirements.txt   # Python dependencies
└── README.md          # This file
```

## Data Description

- **LST Data**: Land Surface Temperature rasters for summer 2023 and winter 2022
- **Land Cover**: Classified land cover data with grid codes
- **Buffers**: Ring buffers and constructed buffers for zonal analysis
- **Zonal Statistics**: Mean, min, max, std, median LST values by land cover and season

## Dependencies

### Python
- pandas
- numpy
- matplotlib
- jupyter

### R
- R statistical software (version requirements in scripts)

### Software
- ArcGIS Pro (for geospatial processing)
- Python 3.8+

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/percyyvon-r/PhD_chapter2_IGARSS.git
   cd PhD_chapter2_IGARSS
   ```

2. **Create virtual environment**
   ```bash
   python -m venv .venv
   ```

3. **Activate environment**
   - Windows: `.\.venv\Scripts\Activate.ps1`
   - Linux/Mac: `source .venv/bin/activate`

4. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

5. **Install R packages** (as needed in R scripts)

## Usage

1. **Jupyter Notebook**: Open `notebook/analysis.ipynb` to run the main analysis
2. **R Scripts**: Execute R files in `scripts/R/` for additional statistical analysis
3. **ArcGIS Project**: Open `data/igarss/igarss.aprx` for geospatial data visualization

## Key Analysis Components

- Seasonal LST comparison (Summer - Winter differences)
- Land cover type analysis
- Buffer zone temperature gradients
- Statistical summaries and visualizations

## Output

Results are saved in the `output/` directory:
- Figures: Plots and charts
- Tables: Statistical summaries

## Contributing

This is a PhD research repository. For questions or collaboration, please contact the repository owner.

## License

This work is part of ongoing PhD research. Please cite appropriately if used.

## Author

Percy Yvon-R