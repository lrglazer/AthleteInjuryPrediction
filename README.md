# Athlete Injury Prediction (ML)

## Overview
A machine learning model that predicts athlete injury risk using training load, fatigue, and recovery data.

## Motivation
As a former student-athlete and engineer, I'm interested in using data to prevent injuries before they happen — especially in high-performance sports like golf.

## What I learned
- Data preprocessing (handling missing + noisy data)
- Feature selection (what actually predicts injury?)
- Model comparison (logistic regression vs decision trees)
- Overfitting vs generalization

## How to run
1. Clone repo
2. Install dependencies:
   ```sh
   pip install pandas numpy scikit-learn matplotlib jupyter
   ```
3. Run notebook:
   ```sh
   jupyter notebook Athlete_Injury_Prevention.ipynb
   ```

## Evaluation

Training and evaluation are documented in `Athlete_Injury_Prevention.ipynb`. Compare held-out results when changing the feature set or model.

## Future improvements
- Add wearable sensor data
- Use time-series models (LSTM)
- Deploy as a real-time injury monitoring tool
