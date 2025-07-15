#  Health Insurance Price Prediction

This project uses machine learning to estimate individual health insurance charges based on demographic and lifestyle attributes. Built and tested on Google Colab, it helps insurance providers price plans more effectively.

---

##  Project Overview

Accurate insurance pricing requires understanding the factors that drive costs. This model identifies those factors and predicts charges using regression algorithms.

---

##  Project Structure

- `insurance_model.ipynb` – Google Colab notebook with full pipeline: EDA → Modeling
- `insurance.csv` – Dataset with features like age, BMI, smoker status, etc.
- `presentation.pptx` – Slide deck summarizing the project, analysis, and results

---

##  Features Used

- Age  
- Gender  
- BMI  
- Smoking Status  
- Number of Children  
- Region

---

##  Modeling Approach

- Data Cleaning: Encoded categorical values, checked for outliers, scaled inputs
- Algorithms used:
  - Linear Regression
  - Ridge Regression
  - Random Forest Regressor
- Evaluation: R², MAE, RMSE

---

##  Key Insights

- **Smoker status** is the most influential variable
- **BMI and age** are positively correlated with charges
- Best model achieved an **R² of ~0.86**

---

##  Tech Stack

- **Platform**: Google Colab
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

##  Dataset

The dataset contains over 1,300 entries with insurance-related data points.

---

##  Presentation

The presentation summarizes:
- Problem statement
- Data overview
- Model comparisons
- Business insights

---

## Future Enhancements

- Add more medical history features (e.g., cholesterol, activity level)
- Deploy as a premium calculator tool for users
