# Global Freelancers — Data Cleaning & EDA (Jupyter Notebook)

This project cleans and explores a global freelancers dataset using **Python (Pandas/NumPy)** and creates basic **visualizations + descriptive statistics** in a Jupyter Notebook.

## What this project does
- Loads a raw CSV dataset: `global_freelancers_raw.csv`
- Cleans & standardizes key fields (gender, hourly rate, satisfaction, active status)
- Handles missing values (mostly using median imputation)
- Exports a cleaned dataset: `global_freelancers_cleaned.csv`
- Generates and saves figures:
  - `categorical_skill_distribution.png`
  - `hourly_rate_distribution.png`
- Prints descriptive statistics and a 95% confidence interval for hourly rate

## Project files
- `Global_Freelance(Dup).ipynb` — main notebook
- `global_freelancers_raw.csv` — input dataset (you must have this in the same folder as the notebook by default)
- Outputs created after running:
  - `global_freelancers_cleaned.csv`
  - `categorical_skill_distribution.png`
  - `hourly_rate_distribution.png`

## Dataset requirements
Your `global_freelancers_raw.csv` should include at least these columns (used by the notebook):
- `gender`
- `hourly_rate (USD)`
- `client_satisfaction`
- `is_active`
- `age`
- `years_of_experience`
- `rating`
- `primary_skill`

> Note: The notebook expects the column name to be exactly **`hourly_rate (USD)`** (including the space and parentheses).

## Setup

### 1) Clone the repository
```bash
git clone <your-repo-url>
cd <your-repo-folder>
