# Indian Ocean Acidification Using Bias-Corrected CMIP6 Model Projection Under Future Climate Scenarios: 

This repository contains Jupyter notebooks used for **data preparation, analysis, and visualization**.

### Data Preparation

Notebooks for preprocessing, regridding, masking, merging, and preparing CMIP6 and reference pH datasets for analysis.

### Analysis

Notebooks for calculating the CMIP6 ensemble, seasonal variability, trends, bias correction, future projections, uncertainty, extreme events, and time of emergence of ocean acidification.

### Figures
## Figure Details

The table below lists the notebook(s) used to generate each figure in the study and the data file(s) they use.

| Figure No. | Python Script | Data File Name |
| --- | --- | --- |
| Fig. 1 | `Study_domain.ipynb` | - |
| Fig. 3 | `model_uncertainty.ipynb`<br>`model_uncertainty_avg.ipynb`<br>`UIN_ENS.ipynb`<br>`UIN_ENS_ssp245.ipynb`<br>`UIN_ENS_ssp126.ipynb`<br>`Total_uncertainty_ph.ipynb`<br>`pH_uncertainty_plot.ipynb` | `ph_cmip6_ensemble_ssp585.nc`<br>`ph_cmip6_ensemble_ssp245.nc`<br>`ph_cmip6_ensemble_ssp126.nc` |
| Fig. 4 | `Future_mean_Hplus_projections.ipynb`<br>`Future_mean_ph_projections.ipynb` | `Hplus_cmip6_ensemble_ssp585.nc`<br>`ph_cmip6_ensemble_ssp585.nc` |
| Fig. 5 | `Monthly_pH_cycle_of_CMIP6_ENS.ipynb` | `ph_cmip6_ensemble_ssp585.nc` |
| Fig. 6 | `Taylor_plot_bc.ipynb` | `ph_cmip6_ensemble_ssp585.nc`<br>`Hplus_cmip6_ensemble_ssp585.nc` |
| Fig. 7 | `seasonal_cycle_nc_files_bc.ipynb`<br>`seasonal_anomaly_plots_bc-hplus.ipynb` | `Hplus_ssp585_biascorrected.nc`<br>`Hplus_ssp245_biascorrected.nc`<br>`Hplus_ssp126_biascorrected.nc` |
| Fig. 8 | `Time_of_Emergence_biascorrected_data.ipynb` | |
| Fig. 9 | `test-regional_extremes_recal_bc.ipynb` | |
| Fig. 10 | `intensity_recal_bc.ipynb` | |
| Fig. 11 | `extrems_H+_duration-test-Copy1.ipynb` | |

## Python Environment

The analysis is implemented primarily in Python using scientific and visualization libraries.

### Main dependencies

```text
Python
NumPy
Pandas
xarray
Matplotlib
SciPy
cmocean
Cartopy
Basemap
```

A typical environment can be installed using:

```bash
conda env create -f environment.yml
conda activate
```


