# Maturity Index Olive Bari

Analysis workspace for olive ripening and production data, with manuscript-ready figures and summary tables.

## Project Structure

- `olive_atlas_analysis.ipynb`: main analysis notebook currently present in this repository.
- `Atlas_data.csv`: input dataset available in this workspace.
- `figures/`: exported plots for manuscript/report use.
- `tables/`: exported CSV summary tables.

## Requirements

Recommended Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `scikit-learn`
- `jupyter`

## Quick Start

1. Create/activate a Python environment.
2. Install dependencies.
3. Open and run the notebook.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter
jupyter notebook
```

Then open:

- `olive_atlas_analysis.ipynb`

## Data Notes

- Ensure your CSV input file is in the project root.
- The current workspace includes `Atlas_data.csv`.
- If your notebook expects a different filename, either:
  - rename the CSV to the expected name, or
  - update the `DATA_FILE` path inside the notebook.

## Outputs

When executed, the notebook exports:

- Figures to `figures/`
- Tables to `tables/`

## Reproducibility Tips

- Run notebook cells from top to bottom after kernel restart.
- Keep the same Python version/environment for manuscript regeneration.
- Commit both notebook and exported assets (`figures/`, `tables/`) when finalizing results.
