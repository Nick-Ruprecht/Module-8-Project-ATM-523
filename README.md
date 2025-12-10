# Module-8-Project-ATM-523

### ARK-LA-TEX Precipitation Variability and EOF Analysis  
Author: Nicholas Ruprecht

## Overview
This repository contains a reproducible workflow for analyzing precipitation variability in the ARK-LA-TEX region using the **NOAA Global Historical Climatology Network Daily (GHCN-D)** dataset [https://doi.org/10.7289/V5D21VHZ].  
The project integrates anomaly mapping, rolling statistics, and EOF analysis to diagnose long-term climate variability.

## Contents
- **Code:** Modular Python scripts for data loading, anomaly calculation, visualization, and EOF analysis.  
- **Figures:** Maps and time series showing precipitation trends, anomalies, and EOF modes.  
- **Documentation:** Intro, summary, and interpretation notes.

## Methods
1. **Data Source:** NOAA Global Historical Climatology Network Daily (GHCN-D).  
2. **Annual & Seasonal Anomalies:** Rolling means, rolling variability, and decadal composites.  
3. **Spatial Mapping:** Cartopy-based maps of anomalies and EOF spatial patterns.  
4. **EOF Analysis:** SVD decomposition of anomalies into dominant spatial modes (EOFs) and their time series (PCs).  
5. **Interpretation:** EOFs show spatial structures of variability; PCs show temporal evolution of those structures.

## Results
- Annual precipitation shows a gradual increase.  
- Spring (MAM) is the most variable season.  
- EOF analysis confirms dominant basin-wide wet/dry modes and localized variability.  
- PCs highlight intensification of dominant modes and nonlinear multi-decadal variability.

## Reproducibility
- All code is modular and reproducible.  
- Figures saved with explicit labels and units.  
- Environment: Python 3.10, xarray, cartopy, matplotlib, scikit-learn.

## License
Open-source, for academic and research use.
