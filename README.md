
# How to Run (Windows)

This repository includes:
- `amazon_analysis_clean.ipynb` — the main notebook.
- `RESULTS_business_impact.md` — summarized results & recommendations.
- `price_bucket_repeat_stats.csv` — repeat-rate by price bucket.
- `potential_churn_users.csv` — list of flagged churn-risk users.

## Requirements
- Python 3.8+
- Packages: pandas, numpy, matplotlib, seaborn

Install packages:
```bash
pip install pandas numpy matplotlib seaborn
```

## Dataset Path
The notebook reads the dataset from this exact path (as requested):
```
C:\Users\DELL\Desktop\DA PROJECT\amazon.csv
```
Make sure the file exists there. If you need to change it, edit `DATA_PATH` in the first code cell.

## Running
1. Open Jupyter Notebook:
```bash
jupyter notebook
```
2. Open `amazon_analysis_clean.ipynb` and run all cells.

### Outputs
- `price_bucket_repeat_stats.csv`
- `potential_churn_users.csv`
- See `RESULTS_business_impact.md` for business insights and action items.
