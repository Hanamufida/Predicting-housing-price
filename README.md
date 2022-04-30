# Predicting-housing-price
This project is a Dibimbing bootcamp assignment project using regularized regression model to predict the housing price in Boston. In this analysis i want to evaluate three types of regression model such as base model, Lasso Model, and Ridge Model. The conclusion part will explain which model are the best to use in predicting the housing price

# File description
There are only 3 files in this repository.

- The notebook is a .ipynb which can be run on Google Colab (with GPU for faster training). It contains the code to predict housing price using Ridge and Lasso regression.
- 'boston.csv' is the data that used in this analysis.The data is taken from the following link: https://github.com/pararawendy/dibimbing-materials/blob/main/boston.csv
- 'HW_REGRESSION_Hana Mufida Nur A.ipynb' is the python file to deploy the regression model analysis.


#Step by Step
1. Import file and libraries
2. Split train test
3. Calculate VIF
4. Creat heatmap correlation 
   To find out whether there are variables that need to be removed or not (because of redundancy)
6. Drop redundant features 
7. Choosing the best lamda to use to calculate the model
8. Model Evaluation
9. Diagnostic study
10. Residual analysis
11. Training and testing error

# Conclusion
Based on the analysis using three type of regressin, Ridge model has the better result in explaining the dependent variable.

The model is:
Model Ridge --> medv = 14.626 - 0.098 crim + 0.028 zn - 0.105 indus + 1.86 chas + 4.707 rm - 0.011 age - 1.17 dis + 0.042 rad - 0.758 pratio + 0.013 black - 0.539 istat

Diagnostic Study
From the ridge regression model, the r square indicates 65.1% combination of independent variables jointly affect (give contribution) to the value of the dependent variable.


