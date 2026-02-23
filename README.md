🔍 1. Project Overview <br/>
      The aim of this project is to understand how Japanese food prices evolved over almost a decade and to build a predictive model for local food prices using available features.
      
📊 2. Data Exploration <br/>
      Missing Values
      * The dataset contained missing entries in the market column.
      * These were filled using reference information from other rows (e.g., product‑to‑market consistency).

      Correlation Analysis
      * A heatmap revealed weak correlations between most variables.
      * This indicates that the dataset is largely independent across features and may benefit from feature engineering.

🤖 4. Machine Learning Objective
  The primary prediction task is:

  Predicting the local price of food items

  Reasons for choosing this target variable:

  It is the most relevant for real‑world pricing analysis.
  It has sufficient data for training and evaluation.


🛠 5. Machine Learning Workflow
  ✔ Train‑Test Split
  Divided the dataset to evaluate generalization.
  ✔ Models Tested

✔ Evaluation Metrics

  MAE – Mean Absolute Error
  RMSE – Root Mean Squared Error
  R² Score

  ✔ Model Interpretation
  Performance was compared across all models to determine the best predictor for local prices.

  📈 6. Results (Summary)

  Models were successfully trained and evaluated.
  Tree‑based models performed better due to their ability to capture nonlinear relationships.
  The dataset’s low cross‑correlation limited the performance ceiling, but results remained consistent and meaningful.
