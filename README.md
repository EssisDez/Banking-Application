# Banking-Application
This project applies mathematical optimization and financial analytics techniques to maximize Net Interest Income (NII) in banking while considering borrower default risk.

      AI-Driven Interest Rate Optimization for Banking Profitability

Using Python and Jupyter Notebook, the model analyzes how changes in interest rates affect bank profitability and identifies the optimal lending rate that balances revenue generation and credit risk.

The project demonstrates the integration of:

- Banking concepts
- Credit risk modeling
- Optimization techniques
- Data analysis
- Financial visualization

      Business Problem
  
Commercial banks generate revenue primarily through interest earned on loans. However, increasing interest rates can also increase the probability of borrower default.
The challenge is to determine:

**What interest rate maximizes profitability while minimizing credit risk?**

This project addresses that challenge through a derivative-based optimization model.

      Objectives
      
- Model the relationship between interest rates and default probability
- Optimize Net Interest Income (NII)
- Analyze banking profitability using Python
- Visualize sensitivity of NII to interest rate changes
- Demonstrate financial analytics techniques for banking applications


| Current Banking Practice                    | Gap                                  | Solution                                                            |
| ------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------- |
| Loan interest rates often set heuristically | May not maximize net interest income | Derivative-based optimization to find exact optimal rates           |
| Limited understanding of NII sensitivity    | Hard to balance risk and return      | Sensitivity analysis on interest rates and default probabilities    |
| Manual allocation of loans                  | Suboptimal profits                   | Algorithmic allocation using calculus ensures maximum profitability |

      Mathematical Model

**Optimal Interest Rate**
 
 r* = (1 - d0) / (2 * k)
 
Where:

- r* = optimal interest rate
- d0 = base default probability
- k = sensitivity of default risk to interest rate

**Net Interest Income Equation**

NII_optimal = loan_amount * optimal_rate * (1 - (d0 + k*optimal_rate))

Where:

- L = loan amount
- r = interest rate
- d0 + kr = adjusted probability of default

       Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Financial computation     |
| Jupyter Notebook | Interactive development   |
| NumPy            | Mathematical calculations |
| Pandas           | Data manipulation         |
| Matplotlib       | Data visualization        |



    Author

**ESSIS Desiree**

MBA in Data Science & Artificial Intelligence
Focused on Banking Analytics, Financial Optimization, and AI Applications in Finance
















