# VCTPredictor
# Predictive Model for Match Outcomes Using ML and AI

## Project Overview
This project aims to predict match outcomes between two teams using machine learning and AI. The predictions will be based on historical data, team statistics, individual player stats, and other relevant metrics from VLR.gg. The model will be used for yearly competition predictions.

## Steps to Build the Predictive Model

### 1. Data Collection
Use the VLR.gg API to collect relevant data:
- Historical match data
- Team statistics
- Individual player statistics
- Map win rates and other metrics

### 2. Data Preprocessing
Clean and organize the collected data:
- Handle missing values
- Normalize numerical features
- Encode categorical variables (e.g., team names)

### 3. Feature Engineering
Extract and create features to improve model performance:
- Aggregate player stats to team-level metrics
- Calculate historical win rates for teams on specific maps
- Derive recent performance trends (e.g., win streaks)

### 4. Model Selection
Choose appropriate models such as:
- Neural Networks
- Gradient Boosting Machines (e.g., XGBoost, LightGBM)
- Ensemble methods

### 5. Model Training
Train the model using historical data:
- Split data into training and validation sets
- Train the model and tune hyperparameters

### 6. Model Evaluation
Evaluate the model's performance:
- Use metrics such as accuracy, precision, recall, F1-score
- Perform cross-validation for robustness

### 7. Prediction
Use the trained model to predict outcomes of upcoming matches:
- Input upcoming match data
- Generate predictions based on trained model

### 8. Iteration
Refine the model iteratively:
- Incorporate more data over time
- Improve features and retrain

## Upcoming Matches to Predict
- THU, AUGUST 1, 2024: Gen.G vs Sentinels
- THU, AUGUST 1, 2024: FunPlus Phoenix vs Team Heretics
- FRI, AUGUST 2, 2024: DRX vs KRÜ Esports
- FRI, AUGUST 2, 2024: FNATIC vs Bilibili Gaming
- SAT, AUGUST 3, 2024: Leviatán vs Talon Esports
- SAT, AUGUST 3, 2024: Team Vitality vs Trace Esports
- SUN, AUGUST 4, 2024: G2 Esports vs Paper Rex
- SUN, AUGUST 4, 2024: EDward Gaming vs FUT Esports
