# CapstoneProject
<img width="643" alt="Screenshot 2025-07-02 at 2 51 38 AM" src="https://github.com/user-attachments/assets/10a8e67e-4fd4-41e1-bbac-392d21531b8e" />
<p><strong>Abstract</strong></p>

<p>
  This project utilizes time-series data from Fitbit wearable devices to develop predictive models for physical activity, with a focus on step count and heart rate analysis. The dataset, publicly available and sourced from Mechanical Turk participants, was aggregated, cleaned, and structured across multiple time periods to create a cohesive foundation for machine learning applications. It includes detailed metrics such as minute-by-minute step counts and heart rate values spanning several weeks.
</p>

<p>
  A significant portion of the work was dedicated to research, exploratory data analysis, and model evaluation. An initial set of six machine learning models—including Linear Regression, Decision Trees, Random Forests, K-Nearest Neighbors, Support Vector Regression, and XGBoost—were tested for forecasting and regression performance. Based on iterative testing, cross-validation, and evaluation using metrics such as Root Mean Squared Error (RMSE) and R² score, three models emerged as the most suitable: Random Forest, Gradient Boosting, and Linear Regression.
</p>

<p>
  These models were selected due to their effectiveness in handling non-linear patterns, resistance to overfitting, and consistent performance across users with varying activity levels. Feature engineering played a critical role in enhancing model input quality, incorporating techniques such as time-window aggregation, activity-level classification, and temporal feature extraction including time of day and weekday versus weekend patterns.
</p>

<p>
  The outcomes illustrate the potential of machine learning to analyze wearable device data for predicting physical activity and identifying behavioral trends. This work emphasizes the importance of both robust model selection and a deep understanding of the temporal, user-centered nature of the data. Future advancements for this project may involve real-time model deployment or expanding the predictive scope to additional health indicators such as sleep quality and calorie intake.
</p>
