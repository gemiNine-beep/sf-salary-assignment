# SF Salary Assignment

Analyzes SF city employee salary data using Python and R.

## Files

- `sf_salary_assignment.ipynb` — Python notebook: imports data, looks up employees, processes stats with a dictionary, handles errors, exports employee details to a zipped CSV
- `unzip_and_display.R` — R script that unzips the exported folder and displays the data
- `Employee Profile.zip` — Sample output: one employee's exported CSV

## How to Run

**Python:** Open `sf_salary_assignment.ipynb` in [Google Colab](https://colab.research.google.com), upload the salary CSV (from [Kaggle](https://www.kaggle.com/datasets/kaggle/sf-salaries)), then Runtime → Run all.

**R:** Open `unzip_and_display.R` in RStudio (with `Employee Profile.zip` in the same folder), update the `setwd()` path, then run.
