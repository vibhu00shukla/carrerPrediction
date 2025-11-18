# Career Prediction using RIASEC Model

## Description
This project implements a career prediction system based on the RIASEC (Realistic, Investigative, Artistic, Social, Enterprising, Conventional) personality model. It uses machine learning algorithms to analyze personality traits and predict suitable career paths. The project includes data preprocessing, feature engineering, and evaluation of multiple regression models.

## Features
- Data loading and cleaning from CSV dataset
- Handling missing values and outliers
- Feature scaling and normalization
- Correlation analysis for feature selection
- Implementation of multiple machine learning models:
  - Linear Regression
  - Decision Tree Regressor
  - K-Nearest Neighbors (KNN)
  - XGBoost
  - Random Forest Regressor
- Model evaluation using MSE, RMSE, and R² score
- Visualization of model predictions and comparisons

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- scipy

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/career-prediction-riasec.git
   cd career-prediction-riasec
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Ensure the dataset `data-final.csv` is in the project directory.
2. Open and run the `RIASEC.ipynb` Jupyter notebook.
3. Follow the cells to execute data preprocessing and model training.
4. View the evaluation metrics and visualizations for each model.

## Data Description
- **Dataset**: `data-final.csv` (tab-separated values)
- **Features**: 48 columns representing RIASEC personality traits (R, I, A, S, E, C with 8 questions each)
- **Target**: Predicting RIASEC scores based on other traits
- **Preprocessing**: Filling missing values, removing outliers, scaling features

## Models and Results
The notebook evaluates the following models:

- **Linear Regression**: R² score ≈ [insert from notebook]
- **Decision Tree Regressor**: R² score ≈ [insert from notebook]
- **K-Nearest Neighbors**: R² score ≈ [insert from notebook]
- **XGBoost**: R² score ≈ [insert from notebook]
- **Random Forest Regressor**: R² score ≈ [insert from notebook]

Detailed metrics (MSE, RMSE) and scatter plots comparing predictions are included in the notebook.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
