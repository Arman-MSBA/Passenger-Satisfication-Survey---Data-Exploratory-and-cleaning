# Passenger satisfaction: data profiling and cleaning

A Python/pandas coursework project that audits and cleans airline passenger survey data, with a focus on business-class passengers.

**Authors:** Riachi, Khachatryan, and Ike (Group 13), as recorded in the original notebook's export filename. This is collaborative coursework; it does not imply sole authorship by Arman Khachatryan.

## Contents and workflow

- `Data Cleaning.ipynb`: original analysis, explanations, and saved outputs.
- `Passengers_Satisfaction_Survey.csv`: the supplied input already present in this repository.
- `Report.html`: a historical exported report, not regenerated during maintenance.
- `data scraped.csv`: an additional historical CSV retained from the original submission; the notebook does not read it.

The notebook profiles column types and distributions, selects business-class passengers, normalizes categories, handles invalid values and duplicates, fills missing values, and converts data types. It records 104,910 input rows, a 50,000-row business-class subset, and 46,117 final rows. These are saved notebook results, not newly rerun measurements.

## Run locally

Use Python 3.10 or 3.11 in an isolated environment. To preserve the older APIs used by this historical notebook, install the bounds in `requirements.txt` with `python -m pip install -r requirements.txt`, then launch `python -m jupyterlab`. Open the notebook from the repository root, restart the kernel, and run all cells. The import now uses the checked-in `Passengers_Satisfaction_Survey.csv` filename.

The notebook writes `Project_2_Riachi_Khachatryan_Ike_Group#13.csv` locally.

## Interpretation and limitations

This is a historical cleaning exercise, not a validated predictive model. Mean/mode imputation can change distributions; several invalid-value rules replace an entire record with missing values. Predictive work should split data before learning imputation values. Recheck all row counts by rerunning in a compatible environment.

The data was supplied for coursework; its original redistribution license is not documented here. Existing publication does not establish unrestricted reuse rights.

All 26 Python code cells parsed successfully during maintenance. The full notebook and historical report were not rerun.
