# Project overview for Airbnb Price Prediction Project

## Overview
This project focuses on analyzing Airbnb listings in Berlin, utilizing various data science techniques to predict rental prices. The architecture is modular, with distinct components for data processing, modeling, and evaluation.

## Project Structure
- **data/**: Contains raw and processed datasets.
  - **raw/**: Original data files, e.g., `berlin_listings.csv`.
  - **processed/**: Cleaned and transformed datasets ready for analysis.
- **notebook/**: Jupyter notebooks for data exploration and modeling.
  - `01_data_wrangling.ipynb`: Data cleaning and preprocessing.
  - `02_ols_lasso.ipynb`: Implementation of OLS and Lasso regression models.
  - `03_rf_boosting.ipynb`: Random Forest and Boosting models.

## Key Components
- **Data Processing**: The data is cleaned and transformed in `01_data_wrangling.ipynb`. Ensure to follow the data cleaning steps to maintain consistency.
- **Modeling**: Different modeling techniques are implemented in separate notebooks. Each notebook contains specific instructions on how to run the models and interpret results.

## Developer Workflows
- **Running Notebooks**: Use Jupyter Notebook to run the analysis. Ensure all dependencies are installed as specified in the environment setup.
- **Testing**: While there are no formal tests, ensure to validate model outputs against known benchmarks.
- **Debugging**: Use print statements and Jupyter's interactive features to debug issues in data processing or modeling.

## Conventions and Patterns
- **Naming Conventions**: Follow consistent naming for variables and functions. Use snake_case for variables and functions, and CamelCase for classes.
- **Documentation**: Each notebook should have a header comment explaining its purpose and usage.

## Integration Points
- **Data Sources**: The project relies on external datasets, primarily from Airbnb listings. Ensure to update the `data/raw/berlin_listings.csv` file with the latest data as needed.
- **Dependencies**: Key libraries include pandas, scikit-learn, and statsmodels. Ensure these are installed in your Python environment.

## Example Usage
To run the data wrangling notebook:
1. Open `01_data_wrangling.ipynb` in Jupyter.
2. Execute each cell sequentially to clean the data.

## Conclusion
This document serves as a guide to understand the project structure, workflows, and conventions. For further assistance, refer to the individual notebooks for detailed instructions on specific tasks.
