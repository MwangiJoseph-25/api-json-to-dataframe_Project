# api-json-to-dataframe_Project

This project demonstrates a complete **API to DataFrame to CSV** workflow using Python and Jupyter notebooks.

The main goal is to:

- Fetch data from public API endpoints.
- Convert the JSON response into structured pandas `DataFrame` objects.
- Clean and inspect the data.
- Export the final structured output to CSV files for reporting and further analysis.

In short, each notebook shows how raw API data is transformed into analysis-ready tabular datasets.

## Project files (ordered: notebook followed by CSV)

1. `01_Api_json_dataframe_hospital-project.ipynb`
2. `02_Patient_data.csv`

3. `03_carts_endpoint.ipynb`
4. `04_carts_endpoint.csv`

5. `05_Dummy.python_assignment.ipynb`
6. `06_dummy_data.csv`

7. `07_products_endpoint.ipynb`
8. `08_products_data.csv`

9. `09_Staff_assignment.ipynb`
10. `10_employees-3.csv`

## Workflow used in this project

1. Send request to API endpoint.
2. Parse JSON response.
3. Normalize data into a pandas `DataFrame`.
4. Perform basic checks (shape, columns, preview, nulls).
5. Save output with `DataFrame.to_csv()`.

## Why this project matters

- Shows practical API data extraction and transformation skills.
- Creates reusable CSV datasets from dynamic API sources.
- Provides transparent notebook-based steps for reproducibility and learning.
