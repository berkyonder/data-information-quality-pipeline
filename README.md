# data-information-quality-pipeline

A portfolio-ready academic data quality project focused on assessing and improving the quality of an artists/artworks dataset.

## Project Objective
This project demonstrates a complete **Data Information & Quality (DIQ)** workflow: profiling, cleaning, standardization, missing-value handling, outlier analysis, and duplicate detection.

## Dataset Overview
The original dataset contains records related to **artists and artworks** (tabular CSV format). The notebook performs exploratory analysis and applies data quality techniques to improve consistency and usability.

See [`data/README.md`](data/README.md) for expected local data setup.

## Data Quality Problems Addressed
The pipeline addresses common issues such as:

- Missing and incomplete fields
- Inconsistent text formatting and standardization issues
- Invalid or noisy values
- Outliers in numeric attributes
- Duplicate or near-duplicate records

## Pipeline Steps
1. Data loading and initial profiling
2. Missing-value analysis and handling
3. Data cleaning and standardization
4. Outlier detection and review
5. Deduplication (including fuzzy matching/record linkage)
6. Validation and final quality checks

## Tools and Libraries Used
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn, missingno
- scikit-learn
- rapidfuzz
- recordlinkage

## Repository Structure

```text
data-information-quality-pipeline/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── DIQ.ipynb
├── reports/
│   └── report.pdf
├── data/
│   └── README.md
└── docs/
    └── project_summary.md
```

## How to Run (with Local CSV Files)
1. Clone this repository.
2. Create and activate a Python environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Place the required CSV files in the local `data/` directory (see `data/README.md`).
5. Start Jupyter:
   ```bash
   jupyter notebook
   ```
6. Open `notebooks/DIQ.ipynb` and run cells in order.

## Final Result
The project delivers a reproducible, documented DIQ workflow that can be reused on the original dataset once local CSV access is available.

## Academic Context
This repository is an academic portfolio adaptation of coursework completed for a **Data Information and Quality** course, emphasizing applied data quality engineering practices.
