# Overview
+ Panel data was taken from the World Bank API
+ Data was pre-processed and cleaned
+ Exploratory analysis was conducted
+ Findings centred around economic theory (e.g. Kuznets curve)
+ Models used inclue: PanelOLS, PanelOLS with Fixed Effects, 2SLS with Instrumental Variables, LASSO Penalization

# Contents
'data_exploration.ipynb' - Pre-processing and EDA
'models.ipynb' - Regression analysis and conclusion
'data/' - Processed datasets

# Python Version Requirement
** Python Version 3.11.x is required for compatibility with the pandas_datareader library. Alternatively the API
section can be skipped entirely by commenting out Step 1**

# How to reproduce results
# 1. Clone the repo
```bash
git clone https://github.com/adrymmm/WorldBankPanel.git
cd WorldBankPanel
```
# 2. Create and activate a Python 3.11 environment
## Using venv
```bash
python3.11 -m venv .venv
```
## On Windows
```bash
.venv\Scripts\activate
```

## On macOS/Linux
```bash
source .venv/bin/activate
```

# 3. Install dependencies
```bash
pip install -U pip
pip install -r requirements.txt
```

# 4. Launch the Notebooks
```bash
jupyter notebook data_exploration.ipynb
jupyter notebook models.ipynb
```