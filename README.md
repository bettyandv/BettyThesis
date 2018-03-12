# 分析师荐股质量——基于社会资本视角
## The quality of the stock recommendation of analytist -- based on social capital prospect

---

### 1. Data Preprocessing
- Load data from xls(x) files, transformed as pandas Dataframe object
- Clean and process variable values by columns according to demand (PLZ see details in notebook files)
- Construct the variable matrix  

### 2. Modelling
- Build 3 linear regression models with 4 groups of response variables
- Implement with statsmodels Ordinary Least Squares (OLS)
- Calculate the t-statistics and p-values for analysising  

### 3. Result Analysis
- Analysis based on p-values,t-statistics, descriptive statistics and correlation-coefficient matrix
- Use group verification to test the robustness of the model