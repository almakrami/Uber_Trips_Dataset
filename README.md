# Uber Trip Analysis and Classification

## Project Description
This project analyzes Uber trip data to uncover patterns and build a machine learning model to classify trips into distance categories (`Short`, `Medium`, `Long`). It includes data preprocessing, visualization, and modeling using Python and Jupyter Notebook.

---

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and normalizes numerical data.
- **Visualizations**: Includes histograms, boxplots, correlation heatmaps, and feature importance charts.
- **Machine Learning**: Trains a Random Forest Classifier for trip classification.
- **Insights**: Provides data-driven insights into trip purposes and distances.

---

## Key Visualizations

### 1. Distribution of Trip Distances
![Trip Distance Distribution](images/trip_distance_distribution.png)  
*This histogram shows that most trips are under 20 miles, with very few exceeding 50 miles. The distribution is heavily right-skewed.*

### 2. Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)  
*This heatmap shows that `MILES` has the strongest correlation with the target variable `DISTANCE_CATEGORY`, while other features like `HOUR` and `CATEGORY_ENCODED` have weaker relationships.*

### 3. Feature Importance
![Feature Importance](images/feature_importance.png)  
*This bar chart displays the importance of features in the Random Forest Classifier. `MILES` is the most important predictor, followed by `PURPOSE_ENCODED`.*

---

## Requirements
Python 3.8 or higher is required. Install the required Python libraries by running:

```bash
pip install -r requirements.txt
