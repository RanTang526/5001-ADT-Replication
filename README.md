# ADT Replication Artifact: Statistical Analysis

This repository contains the replication code and dataset for the statistical analysis of the paper:
> **"A limited technical background is sufficient for attack-defense tree acceptability"** (Schiele & Gadyatskaya, 2025).

This reproduction was conducted as part of an academic research project to independently verify the Brunner-Munzel (BM) tests and Two One-Sided Tests (TOST) presented in the original study.

## 📂 Repository Contents

* `Survey Data.csv`: The original anonymized dataset provided by the authors.
* `Replication_Code.ipynb` *(Note: rename this to match your actual notebook filename)*: The Jupyter Notebook containing the full statistical evaluation workflow.

## ⚙️ Environment & Dependencies

The code was successfully executed and verified in **Python 3.13**. 

**Important Dependency Note:** The original documentation does not explicitly specify all required third-party packages. Before running the notebook, you must manually install the following dependencies. You can do this by running the following commands in the first cell of your Jupyter Notebook or in your terminal:

```bash
pip install pandas
pip install pingouin
