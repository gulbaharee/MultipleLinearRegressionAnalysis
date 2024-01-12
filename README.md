# Multiple Linear Regression for Housing Prices

## Overview
This repository contains the code and documentation for a comprehensive study on factors influencing housing prices using Multiple Linear Regression (MLR). The primary goal is to investigate factors influencing the housing prices using multiple linear regression.

## Results
The final model, `Model 5`, provides efficient results for predicting housing prices. The equation for the model is:
```
Log(Sale_Price) = 2.4534 + 0.1601 * Log(Lot_Area) + 0.0209 * Overall_Cond + 0.0039 * Year_Built + 0.1002 * Log(Total_Bsmt_SF) + 0.1753 * Full_Bath + 0.1383 * Fireplaces
```

Key findings:
- `Lot_Area` and `Full_Bath` are identified as the most influential factors.
- Model validation metrics (homoscedasticity, P-P plot, Durbin-Watson, VIF, Cook's distance) confirm the model's reliability.

## Conclusion
This analysis successfully utilizes Multiple Linear Regression to unveil the intricate dynamics of housing price influences. Stakeholders can leverage these findings for informed decision-making in the real estate market. The repository provides a transparent and replicable framework for future analyses.
