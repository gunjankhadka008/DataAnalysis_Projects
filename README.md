# Restaurant Operations: Predictive Analytics

> Can we predict the size of a dining group just from their bill?

A complete data analysis and machine learning project exploring customer spending patterns at a restaurant -- from raw data exploration to a trained classification model.

---

## Project Overview

This project analyses the classic **Tips dataset** (244 real restaurant transactions) to:

- Understand how spending varies by time, day, group size, and customer demographics
- Engineer meaningful features from transaction data
- Build and evaluate a **Logistic Regression** model that classifies whether a group is *small* (1-2 people) or *large* (3+ people)

**Result:** The model achieves ~98% accuracy on the test set.

---

## Key Findings

| Finding | Detail |
|---|---|
| Dinner earns more | Average dinner bill is ~$3 higher than lunch |
| Weekends peak | Saturday and Sunday see the highest average spend |
| Bill predicts size | Total bill has 0.60 correlation with group size |
| Tip behaviour | Smokers and non-smokers both tip around 16% |

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.9+ | Core language |
| Pandas | Data loading and manipulation |
| Seaborn / Matplotlib | Visualisation |
| Scikit-Learn | Logistic Regression, preprocessing, metrics |

---

## Repository Structure

```
DataAnalysis_Projects/
|
|-- restaurant_analysis.ipynb   # Main notebook: EDA + ML model
|-- requirements.txt            # Python dependencies
|-- .gitignore                  # Files excluded from version control
|-- README.md                   # This file
```

---

## How to Run

**1. Clone the repository**

```bash
git clone https://github.com/gunjankhadka008/DataAnalysis_Projects.git
cd DataAnalysis_Projects
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Launch Jupyter**

```bash
jupyter notebook restaurant_analysis.ipynb
```

**4. Run all cells**

In Jupyter: `Kernel -> Restart & Run All`

> **Note:** The dataset loads automatically via `seaborn.load_dataset('tips')` -- no manual download needed.

---

## Notebook Sections

| Section | What it covers |
|---|---|
| 1. Setup & Data Loading | Import libraries, load dataset |
| 2. Data Inspection & Cleaning | Shape, types, missing values, distributions |
| 3. Exploratory Data Analysis | Spending by time/day/size, correlations, tip behaviour |
| 4. Feature Engineering | New features, encoding, target variable definition |
| 5. Machine Learning Model | Train/test split, scaling, Logistic Regression, evaluation |
| 6. Results & Conclusions | Summary table, next steps |

---

## Model Results

| Metric | Score |
|---|---|
| Accuracy | ~98% |
| Precision (Large group) | 1.00 |
| Recall (Large group) | 0.94 |
| F1-Score | 0.97 - 0.98 |

---

## Next Steps

- Try Random Forest / XGBoost and compare
- Predict exact group size (multi-class problem)
- Build a Streamlit dashboard for interactive exploration
- Collect more data -- 244 rows is a small sample

---

## Author

**Gunjan Khadka**  
[GitHub](https://github.com/gunjankhadka008)
