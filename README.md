# Quantifying-Climate-Change-Impacts-on-Global-GDP
This project builds a predictive modelling framework to assess how climate change affects global GDP. Using World Bank, OWID, and ERA5 data, it applies econometric and machine learning methods to forecast GDP growth under scenarios (Baseline, RCP 2.6, RCP 4.5, −30% CO₂), with rolling-origin validation and uncertainty analysis.

📂 Contents

1. code.ipynb – Jupyter Notebook implementing the full modelling pipeline:

   - Data acquisition (World Bank GDP, OWID CO₂, ERA5 temperature anomalies)

   - Preprocessing and feature engineering (log transforms, lagged terms, panel structuring)

   - Model training (fixed-effects regression, Gradient Boosting)

   - Evaluation (MAE, RMSE, R², rolling-origin validation, uncertainty bands)

   - Scenario forecasting (Baseline, RCP 2.6, RCP 4.5, −30% CO₂ policy)

2. artifacts.zip – Exported plots used in the dissertation (scatterplots, histograms, scenario comparisons, uncertainty bands).

3. requirements.txt – Python dependencies.

4. Datasets.zip – Placeholder folder for input data (not included here; sourced from World Bank, OWID, ERA5).

🔧 Installation

1. Clone the repository:

    git clone https://github.com/YourUsername/Climate-GDP-Forecast.git
    cd Climate-GDP-Forecast

2. Create a virtual environment (recommended):

    python -m venv venv
    source venv/bin/activate    # Mac/Linux  
    venv\Scripts\activate       # Windows

3. Install dependencies:

    pip install -r requirements.txt

4. Launch Jupyter Notebook:

    jupyter notebook
