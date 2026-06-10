# Fitness Analytics: Calorie Burn Prediction & Workout Clustering

##  Project Overview
This project combines **supervised regression** and **unsupervised clustering** techniques to analyze workout data.  
The goal is to predict **calories burned during workouts** and to identify **patterns in workout intensity** using PCA + KMeans.

## Objectives
- Predict **calorie burn** using multiple regression models.
- Cluster workouts into **High, Moderate, Low intensity** groups.
- Provide **business insights** for wearable fitness apps, coaching, and health platforms.

## Dataset
The dataset includes features such as:
- Age, Gender, Weight, Height  
- Heart Rate metrics (Max, Avg, Resting BPM)  
- Session Duration, Fat Percentage, Water Intake  
- Workout Frequency, BMI, MET values  
- Calories Burned (target variable for regression)  
- One‑hot encoded categorical features (Workout Type, Experience Level, Age Group, Intensity)

##  Methodology
1. **Data Preprocessing**
   - Scaling with StandardScaler
   - One‑hot encoding for categorical features
   - PCA for dimensionality reduction

2. **Supervised Learning (Regression)**
   - Linear Regression, Ridge, Lasso
   - Decision Tree, Random Forest
   - KNN, SVR, XGBoost
   - Evaluation metrics: MAE, RMSE, R²

3. **Unsupervised Learning (Clustering)**
   - PCA (2 components for visualization)
   - KMeans clustering
   - Silhouette score for evaluation
   - Cluster analysis (feature means)

4. **Visualization**
   - Scatter plots (PCA1 vs PCA2)
   - Boxplots & Histograms for PCA distributions
   - Cluster centroid analysis

## Business Insights
# 1. Wearable Fitness Apps
- Real‑time calorie burn prediction during workouts.
- Enables smartwatches and trackers to provide **instant feedback**.
# 2. Personalized Fitness Coaching
- Clusters guide **custom workout recommendations**.
- Coaches can tailor duration and intensity suggestions.
# 3. Health Monitoring Platforms
- Predicted energy expenditure supports **nutrition and diet planning**.
- Helps users maintain calorie balance for weight management.
# 4. User Segmentation
- Clustering identifies **workout behavior patterns without labels**.
- Segments like “Weekend Warriors” vs. “Daily Moderate Exercisers.”
# 5. Product Optimization
- Feature importance provides **insights for device manufacturers**.
- Guides improvements in sensors, algorithms, and user interfaces.

## Results
- **Regression models** achieved R² scores up to ~0.85 (Random Forest, XGBoost).  
- **Clustering** produced 3 meaningful groups with silhouette score ≈ 0.42.  
- PCA visualization clearly separated High, Moderate, and Low intensity workouts.
