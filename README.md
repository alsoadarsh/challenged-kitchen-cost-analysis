# Challenged Kitchen Co. — Make vs. Buy Analysis

![Type](https://img.shields.io/badge/Type-Financial_Analysis-blue)
![Tools](https://img.shields.io/badge/Tools-Excel_·_Monte_Carlo-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

**Live site:** https://alsoadarsh.github.io/challenged-kitchen-cost-analysis

---

## The Decision

Challenged Kitchen Co. is launching a new product line and must choose between
building in-house production or outsourcing manufacturing. The choice locks in
unit economics for four years.

---

## Recommendation: In-House Production

| Metric | In-House | Outsource |
|--------|----------|-----------|
| NPV (4-year) | **$1,304,949** | $1,089,212 |
| NPV Advantage | **$215,737** | — |
| Year 1 Cash Flow | $385,980 | $243,320 |
| Cost per Unit | $7 variable | $18 fixed |
| Break-Even | 3,030 units/yr | No fixed costs |

Year 1 projected demand is 14,000 units — break-even is at 3,030.
The investment pays back in Year 1 under virtually any realistic demand scenario.

---

## Monte Carlo Validation

1,000 iterations varying Year 1 demand (mean 14,000, SD 1,000) and
annual growth rate (mean 20%, SD 3%):

- In-house preferred in **100% of iterations**
- In-house NPV range: $878K–$1.75M
- Outsource NPV range: $805K–$1.38M
- NPV advantage consistent at $154K–$220K across all iterations

---

## Key Parameters

| Parameter | Value |
|-----------|-------|
| Selling price | $40/unit (fixed 4 years) |
| In-house variable cost | $7/unit |
| Outsource cost | $18/unit |
| Initial investment | $400,000 |
| Depreciation | $100,000/year (straight-line) |
| Year 1 demand | 14,000 units |
| Annual growth rate | 20% |
| Tax rate | 21% |
| Discount rate | 7% |

---

## Files

| File | Description |
|------|-------------|
| `index.html` | GitHub Pages case study site |
| `Challenged_Kitchen_Memo.pdf` | Full business memorandum |
| `Challenged_Kitchen_Model.xlsx` | Excel financial model with Monte Carlo simulation |

---

## Author

**Adarsh Shukla**
MS Business Analytics · University of Dayton
[LinkedIn](https://linkedin.com/in/adarshhshukla) · [GitHub](https://github.com/alsoadarsh)
