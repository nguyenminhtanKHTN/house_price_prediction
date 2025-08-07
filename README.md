# House Price Prediction

  This project predicts house prices using Linear Regression on the California Housing dataset. It is part of my ML learning journey to master regression tasks.

  ## Learning Goals
  - Understand regression with Linear Regression and metrics (MSE, R²).
  - Preprocess numerical data (scaling, outlier handling).
  - Deploy models via Flask API.
  - Manage ML projects with GitHub.

  ## Directory Structure
  ```
  house-price-prediction/
  ├── data/
  │   ├── raw/california_housing.csv
  │   └── external/
  ├── notebooks/
  │   ├── data_exploration.ipynb
  │   └── data_preprocessing.ipynb
  ├── results/
  │   ├── feature_distribution.png
  │   ├── correlation_matrix.png
  │   ├── boxplot_medhouseval.png
  │   └── median_house_value_distribution_postprocessed.png
  ├── requirements.txt
  ├── README.md
  ├── LICENSE
  └── .gitignore
  ```

  ## Progress
  - [x] Data exploration: Analyzed feature distributions and correlations
  - [x] Data preprocessing: Handle null values, encode categorical, scale features, split train/test
  - [x] Model training: Linear Regression with R2 ~ 0.6
  - [ ] API deployment

  ## Setup
  1. Install dependencies: `pip install -r requirements.txt`
  2. Run notebooks: `jupyter notebook`