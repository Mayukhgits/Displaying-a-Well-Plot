# Displaying-Lithology-Data

## Project Overview
This project focuses on visualizing well log data using Python to interpret subsurface geological formations. The automated plots enhance reservoir characterization by providing clear, customizable visualizations of key petrophysical measurements.

Key Features:
- **Multi-track visualization** of gamma ray, sonic, density, and neutron porosity logs
- **Depth-synchronized plots** for accurate formation analysis
- **Customizable scales** for different log measurements
- **Publication-quality** figures with Matplotlib

## Data Sources
The analysis uses `WellData.csv` containing:
- `DEPTH` (m/ft): Measured depth
- `GR` (API): Gamma ray log
- `RHOB` (g/cm³): Bulk density
- `DT` (μs/ft): Sonic travel time
- `NPHI` (v/v): Neutron porosity
- `RT` (Ωm): Resistivity (optional)

## Tools & Technologies
- **Python 3.8+**
- Core Libraries:
  - `Matplotlib` (Plotting)
  - `Pandas` (Data processing)
  - `NumPy` (Numerical operations)
- File Format: CSV
