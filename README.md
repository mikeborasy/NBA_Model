# NBA Game Outcome Prediction

## Introduction  
Sports analytics is a rapidly growing industry, especially with the rise of sports betting. In 2018, the U.S. gross gaming revenue was around $400 million, and by 2023, this figure skyrocketed to over $11 billion, primarily due to the legalization of sports betting in individual states.  
North Carolina legalized sports betting in March 2024, generating over $60 million in tax revenue within the first six months.

### Project Goal  
The goal of this project is to create a predictive model for determining the outcome of NBA games. Achieving a prediction success rate above 50% would demonstrate the model’s practical value for sports betting markets and potentially for team strategy optimization.

---

## Data Source  
The primary dataset used in this project is the NBA Database from Kaggle, containing game outcomes and detailed statistics from 1947 to 2023.  
**Dataset link**: [NBA Database on Kaggle](https://www.kaggle.com/datasets/wyattowalsh/basketball)

After reviewing the available tables, the key datasets used for model building were `game.csv` and `team.csv`.

---

## Data Preprocessing  
Steps taken during data preprocessing include:  
- Handling incomplete data and NaN values  
- Dropping unnecessary columns  
- Converting data types for compatibility  
- Creating new features such as rolling averages to enhance prediction accuracy  
- Merging relevant columns from different datasets  

---

## Modeling Approach  
The project uses various machine learning models and feature selection techniques, including:  
- Logistic Regression  
- Recursive Feature Elimination (RFE)  
- Standardization and normalization techniques (StandardScaler, MinMaxScaler, etc.)

