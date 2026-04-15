# ESR Project

This repository contains datasets and Jupyter notebooks used for ESR model experimentation and analysis.

## Repository Structure

- `main.ipynb` - Main notebook workflow
- `main_15k.ipynb` - 15k-sample workflow
- `main_15k copy.ipynb` - Alternate/copy of the 15k workflow
- `final_dataset.csv` - Processed dataset
- `esr_dataset_15k_final.csv` - 15k subset dataset
- `esr/` - Local Python virtual environment

## Prerequisites

- Windows PowerShell
- Python 3.11+
- Jupyter Notebook (installed in the virtual environment)

## Setup

1. Open PowerShell in the project root.
2. Activate the virtual environment:

```powershell
& .\esr\Scripts\Activate.ps1
```

3. (Optional) Verify Jupyter is available:

```powershell
jupyter --version
```

## Running the Notebooks

1. With the environment activated, open VS Code in this folder.
2. Open any notebook (`main.ipynb`, `main_15k.ipynb`, etc.).
3. Select the Python kernel from the `esr` environment.
4. Run cells from top to bottom.

## Notes

- Keep large datasets out of source control if they are generated artifacts.
- If package issues occur, reinstall dependencies in the active virtual environment.
