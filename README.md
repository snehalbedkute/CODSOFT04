#  CodSoft Internship - Task 4: Sales Prediction using Linear Regression

---

##  Aim
The aim of this task is to develop a machine learning model using linear regression to predict product sales based on advertising budgets across three marketing channels: TV, Radio, and Newspaper.

---

##  Dataset
The dataset consists of **200 entries** and **4 continuous numerical columns**:

- **Features**: `TV`, `Radio`, `Newspaper` (advertising budgets in thousands of dollars)  
- **Target**: `Sales` (units sold in thousands)

Data source: `advertising.csv`

---

##  Libraries Used
The following Python libraries were used for data analysis, visualization, and modeling:

- `pandas`
- `matplotlib.pyplot` & `seaborn` 
- `sklearn.model_selection` 
- `sklearn.linear_model` 
- `sklearn.metrics` 

---

## Summary of the Task

1. **Data Loading & Exploration**  
    Loaded the advertising dataset using pandas  
    Verified the structure, data types, and absence of missing values

2. **Data Visualization**  
    Plotted pairplots, scatter plots, and a correlation heatmap  
    Analyzed how each advertising channel correlates with sales

3. **Preprocessing**  
    No missing values found  
    Split the dataset into training and testing sets (80/20 split)

4. **Model Building**  
    Trained a `LinearRegression` model on the training data  
    Predicted sales using the test data

5. **Model Evaluation**  
    Evaluated performance using:
      Mean Absolute Error (MAE)
      Mean Squared Error (MSE)
      R-squared Score (R²)

---

## Conclusion

This project successfully applies linear regression to predict sales based on advertising spending. The model performed well, especially with TV and Radio features showing strong predictive power. This kind of analysis helps in optimizing marketing budget allocation for better ROI.

**Name:** Snehal Bedkute  
**Internship:** CodSoft - Data Science Internship  

#CodSoft
