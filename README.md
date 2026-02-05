# Airbnb Price Prediction – Data Analysis 3

This project develops and evaluates predictive models for Airbnb listing prices using data from Inside Airbnb. The objective is to compare different modeling approaches and assess how well they generalize across time and across markets.

---

## Project Structure

- `data/raw/`  
  Raw Airbnb listings data downloaded from Inside Airbnb.

- `data/processed/`  
  Cleaned and preprocessed datasets used for modeling.

- `notebooks/`  
  Jupyter notebooks containing the full analysis:
  - `01_data_wrangling.ipynb` – data cleaning and feature engineering  
  - `02_linear_models.ipynb` – OLS, LASSO, Elastic Net  
  - `03_tree_models.ipynb` – Random Forest and Gradient Boosting  
  - `04_model_comparison.ipynb` – horserace and performance comparison  
  - `05_validity_analysis.ipynb` – temporal and geographical validity checks  

---

## Methods

The following predictive models are implemented and compared:

- Ordinary Least Squares (OLS)  
- LASSO  
- Elastic Net  
- Random Forest  
- Gradient Boosting  

Model performance is evaluated using out-of-sample RMSE and R².

---

## Validity Analysis

Model validity is assessed in two dimensions:

- Temporal validity:applying the models to a later snapshot of Berlin listings (2025 Q1).  
- Geographical validity: applying the same models to listings from Geneva to evaluate transferability across markets.

This setup allows an assessment of whether pricing relationships remain stable over time and across cities.

---

## Reproducibility

The analysis is fully reproducible.  
All notebooks can be run sequentially from `01` to `05`, starting from the raw data and ending with the validity analysis.

---

## Environment / Requirements

All required dependencies are listed in `requirements.txt`.

To install them, run:

```bash
pip install -r requirements.txt

