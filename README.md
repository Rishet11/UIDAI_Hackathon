# UIDAI Data Hackathon 2026

Analytical report on Aadhaar enrolment and update trends.

## Setup

```bash
pip install -r requirements.txt
```

## Project Structure

```
├── api_data_aadhar_*/     # Raw data CSVs
├── data/processed/        # Cleaned Parquet files
├── notebooks/             # Jupyter notebooks
├── src/                   # Python modules
├── outputs/figures/       # Generated visualizations
└── outputs/               # Final PDF report
```

## Usage

Run notebooks in order:
1. `01_data_ingestion_cleaning.ipynb`
2. `02_eda_visualizations.ipynb`
3. `03_analysis_modeling.ipynb`
4. `04_report_generation.ipynb`
