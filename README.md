# 🏠 House Prices - Advanced Regression Techniques

Kaggle Challenge: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Project Description

The goal of this project is to predict house prices based on various features (such as size, year built, condition, etc.). This is a regression task where the objective is to build a model that accurately predicts the sale price of a house.

## Project Structure


## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (Linear Regression, Ridge, Lasso)  
- XGBoost / LightGBM  
- GridSearchCV for hyperparameter tuning  
- Feature Engineering and missing data handling  
- Model ensembling (Stacking, Averaging)

## Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Check and handle missing values  
   - Analyze distributions of the target and features  
   - Visualize correlations and feature distributions  

2. **Data Preprocessing**  
   - Impute missing values (median, mode, custom values)  
   - Encode categorical variables (Label Encoding, One-Hot Encoding)  
   - Scale/normalize features if needed  
   - Create new features (feature engineering)

3. **Model Training**  
   - Experiment with different algorithms: linear regression, decision trees, gradient boosting  
   - Use cross-validation to evaluate model performance  
   - Tune hyperparameters with GridSearchCV  
   - Ensemble multiple models to improve accuracy

4. **Final Predictions and Submission**  
   - Predict prices on the test set  
   - Generate a `submission.csv` file in the format required by Kaggle

## Results

- Best RMSE on public leaderboard: ~0.12  
- Stable and accurate predictions due to thorough preprocessing and model ensembling

## How to Run

1. Clone the repository and navigate to the project folder  
2. Install dependencies (preferably in a virtual environment):

```bash
pip install -r requirements.txt
