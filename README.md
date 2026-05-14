# Bank Loan Default Analysis
**Tools:** Power BI · DAX · Power Query | 
**Dataset:** Credit Risk Dataset (Kaggle) | 
**Records:** 28,632 loans

---

## Dashboard Pages
| Page | Focus |
|---|---|
| Overview | KPIs and default summary |
| Borrower Profile | Who is defaulting |
| Loan Analysis | Loan characteristics vs default |
| Risk Analysis | Risk factors and credit history |

---

## Key KPIs
| Metric | Value |
|---|---|
| Total Loans | 28,632 |
| Total Defaults | 6,202 |
| Default Rate | 21.66% |
| Avg Loan Amount | $9,589 |
| Avg Income | $66,426 |
| Avg Interest Rate | 11.04% |

---

## Key Findings

### Borrower Profile
- Age 22-25 has highest defaults — young borrowers are biggest risk group
- Renters default the most (4,544) — property ownership = financial stability
- Medium income borrowers (31-70K) default the most — not just low income people default
- Newly employed (0 years) have highest defaults at 1,046

### Loan Analysis
- Medical loans default the most (1,421) — desperation borrowing is high risk
- Debt consolidation loans default second (1,296) — already indebted borrowers are risky
- Grade D loans have highest defaults (1,922) — poor credit grade = high default
- High interest loans (12-16%) default the most (2,881)

### Risk Analysis
- Borrowers with NO prior default record still default more (4,276) than those with YES (1,926)
- Short credit history (2-4 years) has highest defaults — inexperienced borrowers are riskier
- Medium loan to income ratio (20-40%) has highest defaults at 2,803

---

## Top 5 Default Risk Factors
1. High interest rate (12-16%)
2. Poor loan grade (D and below)
3. Renting vs owning property
4. Medical and debt consolidation loan intent
5. Short employment history (0-2 years)

---

## Tools Used
- Power BI Desktop
- DAX (calculated measures)
- Power Query (data cleaning and binning)

## Data Source
[Credit Risk Dataset — Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
