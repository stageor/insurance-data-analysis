# Insurance Data Analysis

## 1. Project Overview

This project analyzes an insurance dataset to identify the primary factors driving medical insurance charges. It emphasizes determining which variables most significantly impact cost variations using structured exploratory data analysis and clear, focused visualizations.

The dataset contains demographic and lifestyle attributes including age, BMI, smoking status, number of dependents, gender, and region, along with the corresponding insurance charges.

---

## 2. Business Objective

Insurance providers require a clear understanding of the factors driving medical costs to accurately assess risk and set appropriate policy pricing.

Key objectives include:

- Understanding cost drivers  
- Identifying high-risk customer segments  
- Supporting more accurate pricing strategies  
- Detecting patterns that influence claim amounts  

Key analytical questions:

- How does smoking affect insurance charges?  
- Does BMI significantly influence cost?  
- Are there regional differences in charges?  
- What is the distribution of insurance charges?

---

## 3. Dataset Description

Dataset features:

- `age` – Age of the individual  
- `sex` – Gender  
- `bmi` – Body Mass Index  
- `children` – Number of dependents covered by insurance  
- `smoker` – Smoking status (yes/no)  
- `region` – Residential region  
- `charges` – Medical insurance cost (target variable)

---

## 4. Tools and Technologies Used

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

Observations:

- Insurance charges are right-skewed  
- Most individuals fall within lower charge ranges  
- A smaller group generates significantly higher costs

Insight: High-cost outliers are predominantly linked to smokers and individuals with elevated health risk factors.

---

### 5.2 BMI vs Charges

File: `bmi_vs_charges.png`

Observations:

- Positive relationship between BMI and insurance charges  
- Higher BMI values tend to correspond with higher costs  
- The relationship becomes stronger among smokers

Insight: BMI contributes to financial risk, particularly when combined with smoking.

---

### 5.3 Charges by Smoking Status

File: `charges_by_smoker.png`

Observations:

- Smokers incur significantly higher insurance charges than non-smokers  
- The difference in cost is large and consistent

Insight: Smoking status is the strongest predictor of elevated insurance costs.

---

### 5.4 Charges by Region

File: `boxplot_by_region.png`

Observations:

- Some variation exists across regions  
- Median charges differ slightly between regions

Insight: Regional location has limited influence compared to lifestyle-related variables.

---

## 6. Key Findings

1. Smoking status is the most influential variable affecting insurance charges  
2. BMI shows a positive correlation with medical costs  
3. Insurance charges have a strongly right-skewed distribution  
4. Regional differences exist but have limited impact  
5. High-cost individuals are primarily concentrated among smokers

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
2. Install required libraries
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
