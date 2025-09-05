# Reproducing Figures from Raw Data

This repository contains the code and notebooks used to generate the figures from the raw datasets in the `data/` folder.

## Quick Start

```bash
# 1) (Recommended) create a fresh environment
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 2) Install dependencies
pip install numpy==2.2.5 scipy==1.15.2 matplotlib==3.9.2 pandas==2.2.3

# 3) Launch Jupyter
python -m pip install notebook
jupyter notebook  # or: jupyter lab
```

Open the notebooks in `notebooks/` and run all cells. Each notebook reproduces the corresponding figure(s).

## Data

* All raw data live in the `data/` directory.
* CSV examples used by the notebooks include:

  * `stellar-211modes-15000.csv`
  * `stellar-22modes-15000.csv`
  * `stellar-31modes-15000.csv`
  * `stellar-4modes-15000.csv`
  * `stellar-3modes-12000.csv`
  * `stellar-4modes-12000.csv`
  * `stellar-5modes-12000.csv`
  * `spdc-3modes-11000.csv`
* MATLAB `.mat` example:

  * `noise-stellar-3modes-12000-list.mat`

> If you add or rename files, keep the same structure or update the notebook paths accordingly.


## Software Versions

* Python: **3.12.2**
* NumPy: **2.2.5**
* SciPy: **1.15.2**
* Matplotlib: **3.9.2**
* Pandas: **2.2.3**

