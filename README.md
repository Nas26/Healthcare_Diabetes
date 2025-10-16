# 🩺 Diabetes Data Analysis
##Overview
This project analyzes a healthcare dataset related to diabetes using R and R Markdown. The analysis focuses on understanding patterns among patients, including relationships between key health indicators such as Glucose, BMI, and Age, as well as the likelihood of diabetes occurrence.

The project demonstrates essential data analysis and visualization techniques in R, from data cleaning and transformation to descriptive statistics and correlation analysis.

## 📂 Dataset  
**File:** `Healthcare-Diabetes.csv`  

**Main attributes:**  
- `Pregnancies`  
- `Glucose`  
- `BloodPressure`  
- `SkinThickness`  
- `Insulin`  
- `BMI`  
- `DiabetesPedigreeFunction`  
- `Age`  
- `Outcome` (1 = Diabetic, 0 = Non-diabetic)

---

## ⚙️ Analysis Workflow  
1. **Data Import & Exploration**  
   - Loaded CSV file using `read.csv()`  
   - Inspected structure, column names, and data summary  

2. **Descriptive Statistics**  
   - Calculated mean BMI, Age, and Glucose  
   - Identified dependent (`Outcome`) and independent variables  

3. **Data Cleaning & Preparation**  
   - Removed missing and duplicate entries  
   - Renamed columns for clarity (`BloodPressure` → `BP`, etc.)  
   - Added new variables (e.g., `Glucose_Double = Glucose * 2`)  

4. **Data Manipulation**  
   - Filtered patients above specific ages  
   - Split data into training (70%) and testing (30%) sets  

5. **Visualization & Correlation**  
   - Scatter and bar plots using **ggplot2**  
   - Calculated Pearson correlation between **Glucose** and **Age**  

---

## 🧰 Tools & Libraries  
| Package | Purpose |
|----------|----------|
| `tidyverse` | Data manipulation |
| `ggplot2` | Visualization |
| `dplyr` | Filtering & transformation |
| `tinytex` | PDF rendering for R Markdown |

---

## 🚀 How to Run  

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-data-analysis.git
   cd diabetes-data-analysis







   
