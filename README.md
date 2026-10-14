# Healthcare Data Exploratory Data Analysis (EDA)

## Project Overview
This project explores a healthcare dataset using Python. It focuses on understanding patient information, admission patterns, medical conditions, billing amounts, and relationships between numerical variables.

## Objectives
- Inspect the dataset structure and summary statistics.
- Check for missing values and clean selected columns.
- Convert admission and discharge dates to datetime format.
- Calculate the length of each patient's stay.
- Explore admission types, medical conditions, gender, and billing amounts.
- Visualize patterns and relationships in the data.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset
The notebook loads a CSV file named `healthcare_data_for_task - healthcare_data_for_task.csv`.

Place the CSV file in the notebook's working directory, or update the file path in the data-loading cell before running the notebook.

The notebook uses fields including:
- `Age`
- `Medical_Code`
- `Admission_Type`
- `Date_of_Admission`
- `Discharge_Date`
- `Billing_Amount`
- `Medical_Condition`
- `Gender`

## Workflow
1. Import the required Python libraries.
2. Load and inspect the dataset using `head()`, `shape`, `info()`, `describe()`, and `columns`.
3. Check missing values and fill missing `Medical_Code` values with `Unknown`.
4. Standardize `Admission_Type` text by trimming spaces and applying title case.
5. Convert admission and discharge dates to datetime values.
6. Calculate `Stay_Days` from discharge date minus admission date.
7. Explore billing statistics, average age by medical condition, and medical-condition counts by gender.
8. Create visualizations:
   - Admission type count bar chart
   - Stacked billing totals by medical condition and admission type
   - Billing amount distribution by medical condition (violin plot)
   - Monthly patient admissions line chart
   - Correlation heatmap for numerical columns

<img width="353" height="275" alt="Screenshot 2026-10-14 093333" src="https://github.com/user-attachments/assets/243db09e-9b24-40f5-8f8d-8537c7a442e5" />
<img width="584" height="294" alt="Screenshot 2026-10-14 085031" src="https://github.com/user-attachments/assets/c4c9cdf4-f58e-41ec-9f1d-8fb700dc17cb" />
<img width="578" height="254" alt="Screenshot 2026-10-14 085006" src="https://github.com/user-attachments/assets/1e4d3e69-9f4b-4ea8-93c3-98d51c79109c" />
<img width="581" height="248" alt="Screenshot 2026-10-14 084945" src="https://github.com/user-attachments/assets/e56f632e-9c55-41ee-88e2-122c7246f8b0" />


