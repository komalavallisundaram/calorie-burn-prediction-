# Fitbit: Calorie Burn Prediction & Workout Pattern Clustering

## 📌 Overview
This project leverages **machine learning** to enhance fitness analytics by:
- Predicting calories burned per workout session using supervised regression.
- Identifying hidden workout patterns and user segments using unsupervised clustering.

By combining predictive modeling and pattern discovery, the project demonstrates how wearable fitness data can power intelligent, real-world health applications.

---

## 🎯 Objectives
1. **Calorie Burn Prediction (Regression)**
   - Target: `Calories_Burned`
   - Models: Linear/Ridge/Lasso Regression, KNN, Decision Tree, Random Forest, SVR, XGBoost
   - Metrics: MAE, RMSE, R²
   - Goal: Achieve **R² ≥ 0.80**

2. **Workout Pattern Clustering (Unsupervised Learning)**
   - PCA for dimensionality reduction
   - KMeans clustering (optional: DBSCAN, Hierarchical)
   - Metric: Silhouette Score ≥ 0.15
   - Goal: Identify meaningful workout intensity clusters

##  Dataset
**Features include:**
- Demographics: Age, Gender, Weight, Height, BMI, Fat Percentage
- Physiological: Max_BPM, Avg_BPM, Resting_BPM
- Workout Context: Session_Duration, Workout_Type, Water_Intake, Workout_Frequency, Experience_Level
- **Target:** Calories_Burned

## Skills & Tools
- **Data Preprocessing & Feature Engineering**
- **Regression Modeling** (Linear, Ridge, Lasso, KNN, Decision Tree, Random Forest, SVR, XGBoost)
- **Clustering** (KMeans, DBSCAN, Hierarchical)
- **Dimensionality Reduction** (PCA)
- **Evaluation Metrics** (MAE, RMSE, R², Silhouette Score)
- **Visualization** (Matplotlib, Seaborn)

##  Repository Structure
