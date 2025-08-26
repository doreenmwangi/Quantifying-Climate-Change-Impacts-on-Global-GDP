# Quantifying-Climate-Change-Impacts-on-Global-GDP
This project builds a predictive modelling framework to assess how climate change affects global GDP. Using World Bank, OWID, and ERA5 data, it applies econometric and machine learning methods to forecast GDP growth under scenarios (Baseline, RCP 2.6, RCP 4.5, −30% CO₂), with rolling-origin validation and uncertainty analysis.

📂 Contents

1. code.ipynb – Jupyter Notebook implementing the full modelling pipeline:

2. Data acquisition (World Bank GDP, OWID CO₂, ERA5 temperature anomalies)

3. Preprocessing and feature engineering (log transforms, lagged terms, panel structuring)

4. Model training (fixed-effects regression, Gradient Boosting)

5. Evaluation (MAE, RMSE, R², rolling-origin validation, uncertainty bands)

6. Scenario forecasting (Baseline, RCP 2.6, RCP 4.5, −30% CO₂ policy)

/artifacts – Exported plots used in the dissertation (scatterplots, histograms, scenario comparisons, uncertainty bands).

requirements.txt – Python dependencies.

/datasets – Placeholder folder for input data (not included here; sourced from World Bank, OWID, ERA5).
