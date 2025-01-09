# E-Car Loan Pricing Optimization: Nomis A and B Case Study

## Overview
Case study on pricing and revenue optimization for auto loans using logistic regression and pricing models.

This project focuses on applying customized pricing strategies to optimize the profitability of e-Car loans for an online lender. By leveraging logistic regression and advanced data analysis, the study identifies the optimal Annual Percentage Rates (APRs) to maximize loan conversion probabilities and overall expected profit.

---

## Objectives
1. **Loan Conversion Probability**:
   - Estimate the probability of loan acceptance at different APRs (e.g., 5.00%, 6.00%, 7.00%).
2. **Profit Maximization**:
   - Identify the optimal APR for individual loans to maximize expected profit.
   - Develop strategies to optimize APRs across all loan applicants for maximum profitability.
3. **Key Variable Analysis**:
   - Explore the relationship between loan acceptance (binary outcome) and independent variables such as FICO score, term length, and loan amount.
4. **APR-Profit Tradeoff**:
   - Analyze the balance between higher APRs (lower acceptance probability but higher profit per loan) and lower APRs (higher acceptance probability but lower profit per loan).

---

## Dataset
The dataset includes the following variables:
- **Loan Tier**: Segmentation based on customer creditworthiness.
- **Term Length (Months)**: Duration of the loan in months.
- **Loan Amount**: Principal amount of the loan.
- **FICO Score**: Credit score of the customer.
- **Competition Rate (Comp. APR)**: Published competitor rates.
- **Prime Rate (Cost of Funds)**: Baseline funding cost for the lender.
- **Partner Bin**: Categorization of lending partners.
- **Loan Acceptance**: Binary dependent variable indicating whether the loan was accepted (1) or not (0).

---

## Tools & Techniques
1. **Logistic Regression**:
   - Modeled the probability of loan acceptance based on independent variables.
   - Achieved **78.77% accuracy** in predicting loan acceptance.
2. **Programming Languages**:
   - Python or R for regression analysis and data visualization.
   - Optional: Excel with XLSTAT add-in for logistic regression.
3. **Profit Analysis**:
   - Evaluated how APR impacts loan acceptance probability and profitability.

---

## Methodology
1. **Data Preprocessing**:
   - Cleaned and prepared the dataset for analysis.
2. **Logistic Regression Analysis**:
   - Modeled the relationship between independent variables and loan acceptance.
   - Identified significant factors influencing conversion probabilities (e.g., FICO score, loan amount, and APR).
3. **Profit Analysis**:
   - Quantified the impact of APR changes on expected profit.
   - Developed optimal pricing strategies using advanced techniques from Dr. Phillips' *Customized Pricing*.

---

## Key Insights
- **Data-Driven Pricing Strategies**:
  - Balanced loan acceptance probabilities with profitability by analyzing APR elasticity.
- **Endogeneity and Customized Pricing**:
  - Incorporated advanced concepts from Dr. Phillips' *Customized Pricing* book.
- **Optimization**:
  - Recommended segment-based and dynamic APR strategies to maximize profit.

---

## Results
1. **Model Accuracy**:
   - Logistic regression model achieved **78.77% accuracy**.
2. **Optimal APR Recommendations**:
   - Recommended APRs to maximize profit for individual and overall loans:
     - For an $18,000 loan, **5.5% APR** maximized profit.
     - For a $25,000 loan, **4.5% APR** yielded the highest expected contribution.
3. **APR-Profit Tradeoff**:
   - Demonstrated the tradeoff between higher APRs (lower conversion rates) and lower APRs (higher acceptance rates).

---

## References
1. Dr. Phillips, *Customized Pricing* (focus on Equation 13.1, page 343).
2. Logistic regression tutorials and resources.
3. Course: OPM-6600-01: Pricing and Revenue Analytics, Saint Louis University.

---

## Contact
For inquiries or collaboration, contact Jinal Patel: jinalpat06@gmail.com

