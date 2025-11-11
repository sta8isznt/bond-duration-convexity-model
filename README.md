# Bond Pricing and Interest Rate Sensitivity

## Overview
This project explores the relationship between **bond prices** and **interest rates**, illustrating how changes in the yield to maturity (YTM) affect the value of a bond. It includes calculations for **price**, **duration**, and **convexity**, as well as a graphical representation of **price sensitivity**.

## Objectives
- Understand how bond prices are determined.  
- Analyze how interest rate changes impact bond prices.  
- Calculate key bond risk measures such as **Macaulay Duration**, **Modified Duration**, and **Convexity**.  
- Visualize the inverse relationship between price and yield.  

## Dependencies
- Python 3.x  
- `numpy`  
- `matplotlib`  
- `ipywidgets` (for interactive visualization)

Install dependencies with:
```bash
pip install numpy matplotlib ipywidgets
```

## Usage
Run the Jupyter Notebook or Python script.
Adjust the maturity, coupon rate, and payment frequency parameters.
Observe the impact on bond price as interest rates vary.
View the generated chart titled "Bond Price Sensitivity to Interest Rates".

## Findings
The plot demonstrates that bond prices move inversely to interest rates. As rates rise, bond prices fall due to the decreasing present value of future cash flows. The curve’s shape reflects convexity, showing that price gains from rate decreases are larger than losses from equivalent rate increases.

## Author
Created for educational purposes to illustrate fixed-income valuation and interest rate risk concepts.
