# Rainfall Prediction in the Melbourne Region

This project predicts whether it will rain on a given day in the Melbourne area using historical weather data.  
It includes data cleaning, feature engineering, model training, and evaluation. Two models are compared to see which works best.

---

## Dataset

The data comes from the Australian Bureau of Meteorology (2008–2017).  
For this project, I focused on three nearby locations to capture local weather patterns:

- Melbourne
- Melbourne Airport
- Watsonia

---

## Approach

- **Data Cleaning:** removed missing values, filtered relevant locations  
- **Feature Engineering:** added a season feature, scaled numeric data, encoded categorical variables  
- **Modeling:** pipeline with preprocessing and training using GridSearchCV  
- **Evaluation:** accuracy, precision, recall, F1-score, confusion matrices

---

## Models

- **Random Forest:** captures complex patterns; best overall performance  
- **Logistic Regression:** simpler baseline; good overall accuracy but misses some rainy days

---

## Tools

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

---

## Future Improvements

- Impute missing values instead of dropping rows  
- Test other models like XGBoost or Gradient Boosting  
- Address class imbalance  
- Add more meteorological features

---

## Sources / References

- Australian Bureau of Meteorology, [Climate Data Online](http://www.bom.gov.au/climate/dwo/)  
- Kaggle dataset: [Weather Dataset – Rattle Package](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)  
- Column definitions: [BOM Data Documentation](http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml)  

---

## Author

Madani Chaib
