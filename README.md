# ML Movie Rating Prediction: Linear Regression vs. Random Forest
This repository features a supervised learning project that predicts movie ratings by analyzing complex datasets. The project focuses on feature engineering and comparing the performance of linear models against ensemble methods to achieve the highest predictive accuracy.

# Project Overview
Predicting a movie's success is a multi-dimensional challenge involving variables like budget, genre, director influence, and runtime. This project solves that complexity by transforming raw data into a predictive engine, providing a data-driven approach to understanding audience reception.

Key Technical Achievements
- Engineered a robust data pipeline using Pandas and NumPy for cleaning, handling missing values, and encoding categorical variables (e.g., genre, language).
- Implemented and compared dual methodologies:
    - Linear Regression: Established a baseline for linear feature correlations.
    - Random Forest Regressor: Leveraged ensemble learning to capture non-linear relationships and reduce overfitting, resulting in significantly            lower Mean Squared Error (MSE).
- Conducted Exploratory Data Analysis (EDA) to identify high-impact features, utilizing Matplotlib and Seaborn for statistical visualization.
- Optimized Model Performance through hyperparameter tuning and cross-validation within the Google Colab environment.

# Technology Stack
- Language: Python
- Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
- Environment: Google Colab / Jupyter Notebooks

# Impact & Results
- Model Accuracy: Achieved a competitive R-squared (R^2) score, demonstrating a strong correlation between predicted and actual audience ratings.
- Insights: Successfully identified that "Budget" and "Genre" were the top predictors of rating variance through Feature Importance analysis.
- Scalability: The model architecture is designed to integrate additional API data (like IMDb or Rotten Tomatoes) for real-time predictive updates.

# Repository Structure
- notebooks/: The complete Google Colab .ipynb file with step-by-step logic.
- data/: Link to the dataset used (or sample CSV).
- requirements.txt: List of dependencies for local environment setup.5README.md: Project documentation and results.

# How to Run
Clone this repository.Install dependencies: pip install -r requirements.txt.Open the notebook in Google Colab or Jupyter to view the analysis and training steps.
