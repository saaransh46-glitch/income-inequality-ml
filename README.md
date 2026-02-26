# Predicting Income Inequality with Machine Learning

## Research Question
Can demographic characteristics (age, education, occupation, etc.) predict 
whether an individual earns above or below $50,000 per year?

## Dataset
UCI Adult Dataset — automatically loaded from the web in the notebook.
No manual download required.

## Requirements
Make sure you have Python and the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Reproduce
1. Clone this repository:
```bash
git clone https://github.com/saaransh46-glitch/income-inequality-ml.git
```

2. Open the notebook:
```bash
jupyter notebook analysis.ipynb
```

3. Run all cells from top to bottom (Cell → Run All)

## Models Used
- Logistic Regression (baseline)
- Random Forest Classifier (final model)

## Key Findings
- Random Forest achieved 85% accuracy and AUC-ROC of 0.898
- Capital gain, age, and education were the strongest predictors of high income
