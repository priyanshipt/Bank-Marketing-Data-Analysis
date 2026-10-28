# Bank Marketing Data Analysis

A Jupyter Notebook project that inspects the Bank Marketing dataset and explores customer subscription outcomes for term deposits.

## Project contents

- `Bank_Marketing_Inspection_test.ipynb` — data inspection, missing-value checks, summary statistics, target distribution, and numerical-feature correlation heatmap.
- `bankmarketing.csv` — dataset used by the notebook.
- `.gitignore` — excludes local environments, notebook checkpoints, secrets, and temporary files.
- `requirements.txt` — Python dependencies.

## Requirements

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run the notebook

Keep `bankmarketing.csv` in the same directory as the notebook, then start Jupyter:

```bash
jupyter notebook
```

Open `Bank_Marketing_Inspection_test.ipynb` and run the cells in order.

## Analysis covered

1. Load and preview the dataset.
2. Inspect missing values and column data types.
3. Review descriptive statistics.
4. Visualize the target variable (`y`).
5. Plot a correlation heatmap for numeric features.

## Notes

This is an initial exploratory data analysis project. It does not yet train or evaluate a predictive machine-learning model. Confirm the dataset's source and license before redistributing it publicly.
