# Seasonal Analysis of Potato and Sugar Consumption in Bulgaria (2021–2025)

Quarterly analysis of average household consumption of potatoes and sugar per person in Bulgaria. It measures seasonal fluctuations with seasonal indices and looks at the long-term trend. Built in Microsoft Excel.

## Objective

To find out whether household consumption of potatoes and sugar follows a seasonal pattern within the year and how it has changed from 2021 to 2025.

## Data

- **Indicator:** average consumption per household member, kg per quarter
- **Period:** Q1 2021 – Q4 2025 (20 quarters)
- **Source:** National Statistical Institute of Bulgaria (NSI), Household Budget Survey
- **File:** `potato_sugar_consumption_bg_2021_2025.csv`

## Tools

**Microsoft Excel**: data structuring, averages, seasonal indices, line charts

## Methodology

1. Time series of quarterly consumption for both products
2. Average consumption for each quarter (Q1–Q4) across all years
3. Overall average for the whole period
4. **Seasonal indices** = quarterly average / overall average
5. Charts of the series to visualise trend and seasonality

## Results

**Seasonal indices** (1.00 = average level)

| Quarter | Potatoes | Sugar |
|---|---|---|
| Q1 | **1.017** | **1.024** |
| Q2 | 0.985 | 0.997 |
| Q3 | 0.990 | 0.983 |
| Q4 | 1.008 | 0.997 |

**Change over time** (annual average per quarter)

| Product | 2021 | 2025 | Change |
|---|---|---|---|
| Potatoes | 7.03 kg | 6.70 kg | −4.6% |
| Sugar | 1.65 kg | 1.23 kg | **−25.8%** |

## Key Findings

- **Seasonality is weak** for both products. Quarterly consumption differs from the average by less than ±2.5%.
- **Potatoes** are eaten most in the **winter quarters** (Q1 and Q4) and least in Q2, likely because of more fresh vegetables in spring and summer and more heavy winter meals.
- **Sugar** consumption peaks in **Q1** and is lowest in **Q3**.
- The main pattern is a **long-term decline**. Sugar consumption fell by about a quarter in five years, which may reflect healthier eating habits and higher prices.

## Possible Next Steps

- Remove the trend before computing seasonal indices (for example, with ratio-to-moving-average). This matters for sugar, whose strong downward trend can affect the indices.
- Forecast 2026 consumption with Holt–Winters exponential smoothing.

## Author

**Viktoria Vutova**: [LinkedIn](https://www.linkedin.com/in/viktoria-vutova-964294247)
