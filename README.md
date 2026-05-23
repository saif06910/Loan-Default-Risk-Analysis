# Loan Default Risk Analysis

Credit risk analysis identifying the key drivers of loan defaults across a portfolio of 600+ personal loans, with actionable underwriting recommendations.

## Business Context
A mid-size consumer lending company is experiencing a default rate well above its 12% target. Management needs data-driven insights to improve the underwriting process.

## Questions Answered
- What is the overall default rate by credit score bucket?
- Is there a relationship between DTI ratio and default likelihood?
- Which loan purposes and employment statuses carry the highest risk?
- What thresholds should the underwriting team use?

## Tech Stack
- Python (Pandas, NumPy, Matplotlib)
- SQL

## Key Findings
- Portfolio default rate significantly exceeds the 12% target
- Credit scores below 650 show disproportionately high default rates
- DTI ratios above 40% are a strong early warning signal
- Recommended thresholds: minimum credit score 650, maximum DTI 40%

## Files
| File | Description |
|------|-------------|
| `notebook/loan_default_analysis.ipynb` | Full analysis notebook |
| `data/borrower_profiles.csv` | Borrower demographics and financials |
| `data/loan_applications.csv` | Loan details and repayment outcomes |