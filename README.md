#  Earthquake Magnitude Prediction using Machine Learning and MLflow

## Project Overview

This project develops a machine learning system for predicting earthquake magnitude using geographical features. Multiple regression algorithms were trained, evaluated, and compared, while **MLflow** was used to track experiments, model parameters, evaluation metrics, and trained models in an organized and reproducible workflow.

---

## Objectives

- Predict earthquake magnitude using machine learning regression models.
- Compare the performance of multiple regression algorithms.
- Evaluate models using several regression metrics.
- Track experiments and models with MLflow.
- Select and save the best-performing model.

---

## Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling using StandardScaler
- Multiple regression models
- Model comparison
- Cross-validation
- Feature importance analysis
- Predicted vs Actual visualization
- MLflow experiment tracking
- Best model selection and saving

---

## Dataset

The dataset contains numerical information describing earthquake events.

### Input Features

- Latitude
- Longitude
- Depth

### Target Variable

- Earthquake Magnitude

---

## Data Preprocessing

The preprocessing pipeline includes:

- Missing value handling
- Feature and target separation
- Train/Test split (80% / 20%)
- StandardScaler normalization

---

## Exploratory Data Analysis

EDA includes:

- Correlation Heatmap
- Data Distribution Visualization
- Feature Relationship Analysis

---

## Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- K-Nearest Neighbors (KNN)
- XGBoost Regressor

---

## Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Adjusted R²
- Model Accuracy

Models were ranked according to their overall performance.

---

## MLflow Integration

MLflow was used to manage the complete machine learning workflow by tracking:

- Dataset information
- Model parameters
- Evaluation metrics
- Trained models
- Visualizations
- Experiment history

This enables reproducible experiments and simplifies model comparison.

---

## Model Validation

The selected model was further validated using:

- Predicted vs Actual Plot
- 5-Fold Cross Validation
- Feature Importance Analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- MLflow
- Matplotlib
- Seaborn

---

## Project Structure

```text
Earthquake-Magnitude-Prediction/
│
├── earthquake_prediction.ipynb
├── mlruns/
├── saved_model/
└── README.md
```

---

## How to Run

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost mlflow
```

Run the notebook:

```bash
jupyter notebook earthquake_prediction.ipynb
```

Launch MLflow UI:

```bash
mlflow ui
```

---

## Results

Multiple regression models were compared to identify the best-performing model. Ensemble methods such as Random Forest and XGBoost achieved superior predictive performance, while MLflow provided efficient experiment tracking and model management.

---

## Learning Outcomes

This project demonstrates practical experience with:

- Machine Learning
- Regression Analysis
- MLflow
- Feature Engineering
- Data Preprocessing
- Cross Validation
- Model Evaluation
- Experiment Tracking

---

## Future Improvements

- Include additional seismic features.
- Perform hyperparameter optimization.
- Deploy the model as a web application.
- Integrate real-time earthquake data.
- Automate model retraining.

---

## Author

**Farah Jouda**

Bachelor of Computer Science and Information Systems

Major: Artificial Intelligence

---

