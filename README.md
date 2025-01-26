# Survival Analysis: Customer Lifetime Value (CLV) Model for Telecommunication Company

This project, completed as part of the **DS223 Marketing Analytics** course at the **American University of Armenia**, focuses on developing a **Customer Lifetime Value (CLV)** model for a telecommunication company using parametric models. The goal is to estimate the long-term value of customers, which is crucial for improving customer retention strategies, marketing efforts, and business decision-making.

### Project Overview

The approach begins by building **Accelerated Time Failure (ATF)** models using various distributions to model the time until a customer's relationship with the company ends. These distributions include:
- **Weibull**
- **Lognormal**
- **Loglogistic**
- **Exponential**
- **Generalized Gamma**

Each model is evaluated and compared using various metrics such as **AIC**, **BIC**, and **log-likelihood** to determine the best-fitting model. The selected model is then used to calculate the CLV for each customer.

### Methodology

1. **Model Development**:
   - The initial step involves fitting the ATF models to the data using the selected distributions.
   - A detailed comparison of the model performances is made based on key metrics.
   
2. **CLV Calculation**:
   - Using the best-performing model, CLV is calculated for each customer.
   - The calculation process is clearly documented with code and explanations in the Jupyter Notebook.

3. **Customer Segmentation**:
   - The CLV values are analyzed across different customer segments to identify high-value customer groups and inform business strategies.
   
4. **Insights & Recommendations**:
   - The project concludes with actionable insights based on the analysis of customer lifetime value, segmented by demographics or behavior.

### Deliverables

- **Jupyter Notebook**: Contains all code, detailed explanations for each modeling step, and analysis processes.
- **Final Report**: A comprehensive report summarizing the methodology, results, and actionable insights derived from the CLV calculations.
