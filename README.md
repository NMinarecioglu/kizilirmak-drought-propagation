# Kızılırmak Basin Drought Propagation Analysis — Python Codes

## Description
This repository contains the Python codes used in the study:

**"Drought Propagation Dynamics in the Kızılırmak Basin: A Copula and Bayesian Network Framework Across Climatically Heterogeneous Sub-Basins"**

Minarecioğlu, N., Çıtakoğlu, H. (2026). Water Resources Research.

## Contents

| File | Description |
|---|---|
| `Run_Theory_ve_Drought_Characteristics_Box_Plots.ipynb` | Drought event identification using run theory and box plot visualization |
| `CWT.ipynb` | Continuous Wavelet Transform (CWT) analysis |
| `Cross_Wavelet_Transform_(XWT)_and_Wavelet_Coherence_(WTC)_Analysis.ipynb` | Cross Wavelet Transform and Wavelet Coherence analysis |
| `Sequential_MK_Analysis_—_Basin_Average.ipynb` | Mann-Kendall trend analysis and Sen's slope estimation |
| `Drought_Propagation_Heatmap_–_Kızılırmak_Basin.ipynb` | Propagation lag heatmap visualization |
| `Trigger_threshold_and_Response_Probability.ipynb` | Copula-based dependence analysis and trigger threshold estimation |
| `Copula_and_Bayesian_Network_Analysis.ipynb` | Copula fitting and Bayesian network modelling of drought propagation chains |

## Requirements
Python 3.x
pandas
numpy
scipy
matplotlib
seaborn
pgmpy
pycwt
openpyxl

## Data
Input data (SPI, RDI, SDI) were computed using DrinC software (Tsakiris et al., 2013) and SPI_SL_6 (NDMC, University of Nebraska-Lincoln). Meteorological data are available from MGM (https://www.mgm.gov.tr) and streamflow data from DSİ (https://www.dsi.gov.tr).

## License
This code is licensed under the MIT License.

## Contact
Necmiye Minarecioğlu — nminarecioglu@ahievran.edu.tr
