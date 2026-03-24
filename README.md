# IFRS 17 Insurance Profitability Model

## Overview
This project demonstrates a simplified implementation of IFRS 17 using Python. The objective is to model insurance contract profitability by estimating expected cashflows and applying the Contractual Service Margin (CSM) framework.

The model builds on actuarial pricing outputs and extends them into financial reporting, bridging the gap between actuarial modelling and accounting under IFRS 17.

---

## Key Concepts

### 1. Expected Cashflows
The model estimates:
- Premiums received from policyholders
- Expected claims (from pricing model)
- Expected expenses

### 2. Contractual Service Margin (CSM)
CSM represents the unearned profit of the insurance contract.

CSM = Premium − Expected Claims − Expected Expenses

This profit is not recognized immediately but is released over the coverage period.

### 3. Profit Recognition
Profit is recognized gradually over time rather than upfront, reflecting the provision of insurance services.

---

## Methodology

The model follows these steps:

1. Calculate pure premium using frequency–severity modelling  
2. Add expense and profit loadings to determine premiums  
3. Estimate expected claims and expenses  
4. Compute Contractual Service Margin (CSM)  
5. Simulate CSM release over a 12-month coverage period  

---

## Example

Premium: 405  
Expected Claims: 300  
Expenses: 75  

CSM = 30  

Monthly Profit Recognition = 30 / 12  

---

## Tools & Technologies

- Python  
- Pandas  
- Actuarial modelling concepts  
- IFRS 17 framework  

---

## Project Structure

- `ifrs17_model.ipynb` → IFRS 17 modelling code  
- `IFRS17_Presentation.pdf` → Summary slides  

---

## Why This Project Matters

This project demonstrates:

- Understanding of IFRS 17 principles  
- Ability to translate actuarial models into financial reporting  
- Practical implementation of insurance profitability analysis  

This is a key skill for actuarial, insurance, and financial reporting roles.

---

## Author

Catherine Akoth  
Actuarial Science Graduate
