# Linear Regression Analysis of Cancer Mortalities Data

This project identified key factors contributing to cancer mortality rates across American counties. Using a linear regression model, we predicted the TARGET_deathRATE, the mean number of cancer deaths per 100,000 people, based on a range of demographic, socioeconomic, and healthcare-related variables. These include factors such as the types of health coverage available, median age by gender, median income, employment status, and education levels, all of which may influence cancer outcomes through both cancer risk and the quality of available treatment.

![EDA 1](https://github.com/user-attachments/assets/7a627d11-328f-4f12-9c6c-68d3806d6006)

![EDA 2](https://github.com/user-attachments/assets/2da28369-e569-456c-9a34-572d17105936)

![EDA 3](https://github.com/user-attachments/assets/5e2bde4f-0fec-418a-972d-421ba1a74fe9)

![EDA 4](https://github.com/user-attachments/assets/347caebb-1f37-4d02-a5c0-ad28d0ba58a0)

**Final Regression Model Formula** 

Predicting the Transformed Mean per Capita (100,000) Cancer Mortalities from these set of predictors:

1. incidenceRate: Mean per capita (100,000) cancer diagnoses

2. MedianAgeMale: Median age of male county residents

3. PctPrivateCoverage: Percent of county residents with private health coverage

4. PctEmpPrivCoverage: Percent of county residents with employee-provided private health coverage

5. PctPublicCoverage: Percent of county residents with government-provided health coverage

![Regression Coefficients Table](https://github.com/user-attachments/assets/ae7e0bdd-5b0e-4c26-8623-20a88d73c3a8)

![Diagnostic Plot (Transformed Regression Model)](https://github.com/user-attachments/assets/fa9b60dc-c314-4067-843a-3e3a1f7288b6)

When the residuals of a regression model have constant variance, it means the model satisfies the homoscedasticity assumption. This ensures that the variability of the errors is consistent across all levels of the predicted values, leading to more reliable standard errors, confidence intervals, and hypothesis tests. It also indicates that the model's predictions are equally precise across the range of the response variable, avoiding biased parameter estimates.

*Performing Variable Selection, Diagnostics, Correcting Model Assumptions, Final Inferences, and Concluding Thoughts are discussed in the HTML Report

## Technology Used: R Programming Language
## Project Code is located in the qmd file
## Project Report is located in the html file (Download raw file)
## Project Data is located in the csv file (Download raw file)
## Project Data Description is located in the docx file (Download raw file)
