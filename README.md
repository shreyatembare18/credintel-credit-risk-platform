# CredIntel: FinTech Credit Risk & Business Intelligence

FinTech credit risk and customer analytics: logistic regression default model, segmentation, Excel workbook and live dashboard (simulated data)
🔗 **Live demo:** https://credintel-platform.netlify.app/

## Overview
End-to-end credit risk and customer analytics on simulated data
(200 loan records, 200 user records).

## Key results
- Default rate: 27.5% (55 of 200 loans), NPA exposure ₹30.9L
- Logistic regression: 93.3% test accuracy, 0.993 AUC-ROC,
  83.3% precision, 93.8% recall
- Top drivers: loan-to-income ratio and credit history (35% each)
- All 27 loans with LTI > 1.5 defaulted
- High Spenders: 31% of users, 54% of spend
- K-Means silhouette about 0.16–0.19, so rule-based segments were used

## What's inside
| File | Purpose |
|---|---|
| index.html | Interactive dashboard |
| analysis/*.xlsx | Formula-driven workbook (data, assumptions, metrics) |
| docs/ | LinkedIn carousel and screenshots |

## Tech stack
Python, scikit-learn, Excel, HTML/CSS/JavaScript

## Limitations
- All data is simulated.
- The hold-out test set has only 60 rows (16 defaults), so metrics are
  indicative, not production-grade.
- Some dashboard tabs (Unit Economics, A/B Testing, Personas, Churn,
  Benchmarking) use illustrative assumptions and are labelled as such.

## Run locally
Open `index.html` in any browser.

## Author
Shreya Tembare 
