# Insurance Data Analysis

## 1. Project Overview

This project analyzes an insurance dataset to understand the key factors influencing medical insurance charges. The objective is to identify which variables have the strongest impact on costs and derive actionable insights using exploratory data analysis (EDA) and visualization.

The dataset includes demographic and lifestyle attributes such as age, BMI, smoking status, number of children, sex, and region, along with corresponding insurance charges.

---

## 2. Business Objective

Insurance companies need to:

- Understand cost drivers
- Identify high-risk customer segments
- Price policies more accurately
- Detect patterns that influence claim amounts

This analysis focuses on answering:

- How does smoking affect insurance charges?
- Does BMI significantly influence cost?
- Are there regional differences in charges?
- What is the overall distribution of charges?

---

## 3. Dataset Description

Features in the dataset:

- `age` – Age of the individual  
- `sex` – Gender  
- `bmi` – Body Mass Index  
- `children` – Number of dependents  
- `smoker` – Smoking status (yes/no)  
- `region` – Residential region  
- `charges` – Medical insurance cost (target variable)

---

## 4. Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 5. Exploratory Data Analysis

### 5.1 Distribution of Insurance Charges

File: `charges_distribution.png`

- Charges are right-skewed.
- Majority of customers fall into lower charge ranges.
- A smaller group has extremely high costs.

Insight: High-cost outliers are likely associated with smokers or high-risk profiles.

---

### 5.2 BMI vs Charges

File: `bmi_vs_charges.png`

- Positive correlation between BMI and charges.
- Higher BMI tends to increase insurance costs.
- Relationship is stronger among smokers.

Insight: BMI increases financial risk, especially when combined with smoking.

---

### 5.3 Charges by Smoking Status

File: `charges_by_smoker.png`

- Smokers have significantly higher charges than non-smokers.
- The cost gap is substantial and consistent.

Insight: Smoking status is the strongest predictor of high insurance charges.

---

### 5.4 Charges by Region

File: `boxplot_by_region.png`

- Regional differences exist but are not extreme.
- Some regions show slightly higher median charges.

Insight: Region has limited influence compared to lifestyle factors.

---

## 6. Key Findings

1. Smoking status is the most influential variable.
2. BMI positively correlates with insurance charges.
3. Charges are heavily right-skewed.
4. Region has relatively minor impact.
5. High-cost individuals are concentrated among smokers.

---

## 7. Project Structure
insurance-data-analysis/

├── Insurance Report.ipynb
├── Insurance_Report.pdf
├── bmi_vs_charges.png
├── boxplot_by_region.png
├── charges_by_smoker.png
├── charges_distribution.png
└── README.md

---

## 8. How to Run

1. Clone the repository  
2. Install required libraries:
pip install pandas numpy matplotlib seaborn
3. Open `Insurance Report.ipynb` in Jupyter Notebook  
4. Run all cells  

---

## 9. Future Improvements

- Build regression model to predict charges  
- Perform correlation heatmap analysis  
- Add statistical testing  
- Apply machine learning models  
- Implement feature engineering  

---

## 10. Conclusion

The analysis confirms that smoking and BMI are primary drivers of insurance costs. These insights align with real-world actuarial risk factors. Further modeling can convert these findings into a predictive pricing framework.
