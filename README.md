# AsiaFLUX 2025 – R and Jupyter Binder Environment

🚀 This repository contains teaching materials for data processing, gap-filling, and carbon budget analysis using R (RStudio) and Jupyter notebooks on Binder. It’s a hands-on, end-to-end tutorial built around EddyPro outputs and REddyProc workflows to clean, process, and gap-fill Eddy Covariance (EC) data for the AsiaFlux 2025 community.


# 🧭 Overview

This repository helps you go from raw EddyPro data ➜ gap-filled fluxes ➜ carbon budget analysis, using both Python and R (REddyProc) in one flexible setup.
✨ The workflow is designed to be easy to follow — ideal for students, researchers, and data managers working on ecosystem flux studies.

# ⚙️ Workflow Steps

# 🪶 1. Data Cleaning & Preparation (Python)

Clean, filter, and prepare EddyPro outputs for REddyProc:

Removes bad or incomplete records

Selects key columns

Applies initial QC filtering

Outputs a ready-to-use dataset

📁 Script: 1_EddyPro_processed_data_cleaning_and_processing.py


# 🧩 2. Gap-Filling & Flux Partitioning (R / REddyProc)

Process the cleaned data using REddyProc:

Gap-filling of fluxes and meteorological data

Partitioning of net ecosystem exchange (NEE)

Compatible with RStudio or Jupyter Notebook (via R kernel)

📄 Scripts:

2_REddyProc_R_Studio_version.R

2_REddyProc_Jupyter_version.ipynb


# 🌱 3. Data Exploration & Carbon Budget (Python)

After gap-filling, visualize and explore the results:

Carbon flux analysis

Visualization of time-series trends

Summary statistics and plots

📊 Notebook: 3_Gap_filled_Data_Exploration_and_Carbon_Budget.ipynb


# 🧰 Included Files
| File                             | Description                        |
| -------------------------------- | ---------------------------------- |
| `eddypro_2021_biomet_*.csv`      | Example biomet data from EddyPro   |
| `eddypro_2021_full_output_*.csv` | Full EddyPro output for processing |
| `fetches.xlsx`                   | Site fetch and metadata info       |
| `README.md`                      | Documentation (this file!)         |


# 💻 How to Use

🐍 Run Python scripts first to clean and prepare the EddyPro output.

📊 Load the processed file in R or Jupyter (R runtime) and run REddyProc scripts.

🌍 Use the final Python notebook for visualization and carbon budget estimation.




## Launch the Environment

You can launch Binder in either RStudio or JupyterLab:

| Environment | Launch Link |
|--------------|--------------|
| **JupyterLab** | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ShamsuzzamanMd/Binder/main?urlpath=lab) |
| **RStudio** | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ShamsuzzamanMd/Binder/main?urlpath=rstudio) |


---

### Contents
- `2 EC Data Gap-filling using REddyProc R Studio version.Rmd` – R Markdown tutorial  
- `2 REddyProc Jupyter version.ipynb` – Jupyter-based version of the same analysis  
- `install.R`, `requirements.txt`, and `runtime.txt` – environment configuration files  
- `index.ipynb` – optional launch notebook  

---

### Notes
- Binder may take a few minutes to build the environment the first time.  
- You can switch between R and Python kernels inside JupyterLab.  
- For reproducibility, the R and Python dependencies are pinned in the setup files.


