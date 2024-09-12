# F1-Driver-Championship-Prediction-Model

This project uses an ensemble of machine learning models to predict the number of championships won by Formula 1 drivers based on their historical performance metrics. The dataset used includes drivers' achievements such as Race Wins, Pole Positions, Podiums, Fastest Laps, and more, sourced from the [Kaggle F1 Drivers Dataset](https://www.kaggle.com/datasets/petalme/f1-drivers-dataset/data).

### Key Features of the Project:
- Ensemble Learning: The project implements a voting classifier combining five models:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Support Vector Machine (SVM)
- Class Imbalance Handling: Used RandomOverSampler to balance minority and majority classes, ensuring accurate prediction across all championship categories (0 to 7 championships).
- Performance Metrics: The model achieves a high level of accuracy (~99.66%), and detailed classification metrics (precision, recall, F1-score) show that the model effectively predicts even the least represented classes.

Technologies Used:
- Python: For data processing and modeling.
- Pandas: Data manipulation and analysis.
- Scikit-learn: Model implementation and evaluation.
- XGBoost: Powerful gradient boosting algorithm.
- Imbalanced-learn: Handling class imbalance with oversampling techniques.
- Plotly: Interactive visualizations.

 Feel free to leave comments and remarks on my LinkedIn page [Artem Lyubarskiy ](https://www.linkedin.com/in/artem-lyubarskiy-1b4797207/). 
