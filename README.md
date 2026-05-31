# Restaurant Operations: Predictive Analytics

## View the Notebook
👉 [Click here to view the notebook](https://nbviewer.org/github/gunjankhadka008/DataAnalysis_Projects/blob/main/restaurant_analysis.ipynb)

## Project Overview
This project analyzes customer spending patterns to understand the relationship between total bill amounts and group sizes. The goal was to build a machine learning model to predict whether a group is small (1-2 people) or large (3+ people) based on their transaction value.

## Tech Stack
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Seaborn, Matplotlib
- **Machine Learning:** Scikit-Learn (Logistic Regression)

## Results
- **Key Insight:** Dinner has higher bills and more variance than Lunch. Saturday and Sunday generate the highest average spend.
- **Strongest Predictor:** Total bill correlates with group size at r = 0.60
- **Model Performance:** 98% accuracy in predicting group size (small vs large)

## Files
- `restaurant_analysis.ipynb` — Main notebook with analysis and ML model
- `requirements.txt` — Python dependencies
