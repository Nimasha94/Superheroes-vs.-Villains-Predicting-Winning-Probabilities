# Superheroes vs. Villains – Predicting Winning Probabilities  

This project was developed for the **Knowledge Discovery & Data Mining** course of my Master’s program.  
The goal is to **predict the winning probabilities** of various superheroes and villains using a synthetic dataset designed to mimic real-world challenges.  

## Objectives
- Perform **Exploratory Data Analysis (EDA)** and preprocessing  
- Build and train predictive models for **winning probabilities**  
- Evaluate models using appropriate metrics  
- Tackle two additional tasks:
  - **Task 2:** Predict winning probabilities for unseen heroes/villains and decide fight outcomes  
  - **Task 3:** Explain why a villain with a probability of 1.0 always wins  

## Repository Structure

#### Jupyter notebook with analysis
- Superheroes_vs_Villains.ipynb

#### Datasets (synthetic, provided for coursework)
- Data.csv
- Task2_superheroes_villains.csv
- Task3_villains.csv

#### Project documentation
- README.md

## Methods & Tools
- **Data Splitting:** Train/test split = 80/20
- **Language:** Python
- **Encoding:** one-hot encoding
- **Machine learning libraries:**
   **scikit-learn:**
    -  train_test_split– Splitting data for training and testing
    -  StandardScaler, RobustScaler– Feature scaling tools
    -  cross_val_score, KFold– Cross-validation tools
    -  make_scorer, r2_score, root_mean_squared_error– Evaluation metrics
- **Model:** xgboost
- **Approach:** Supervised Learning – mapping from inputs (power_level, age, etc.) to a known output (win_prob)
