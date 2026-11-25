
# GST 2.0 Financial Performance Analysis

### A Comparative Analysis of Selected Indian Companies Across Pre, Implementation and Post-GST 2.0 Periods

## 1. Project Overview

This project examines the financial performance of 16 selected Indian companies across four industry categories during the Pre-GST 2.0, Implementation and Post-GST 2.0 periods.

The study uses quarterly financial data from September 2024 to June 2026 to analyse Sales, Sales Growth, Operating Profit Margin (OPM) and Net Profit Margin (NPM).

The analysis uses Microsoft Excel for data preparation, descriptive analysis and regression analysis, while Microsoft Power BI is used to develop interactive dashboards for overall, company-wise and category-wise comparisons.

## 2. Objectives of the Study

- Analyse financial performance across the three GST 2.0 study periods.
- Compare Sales and Sales Growth across periods.
- Examine Operating Profit Margin and Net Profit Margin.
- Compare financial performance across four industry categories.
- Identify company-wise differences in financial performance.
- Examine Sales differences using regression analysis.
- Present financial insights through interactive Power BI dashboards.

## 3. Study Coverage

- Companies selected: 16
- Industry categories: 4
- Study period: September 2024 – June 2026
- Data frequency: Quarterly
- Data type: Secondary financial data

### Industry Categories

| Category | Selected Companies |
|---|---|
| Automobile | MARUTI, HEROMOTOCO, TVSMOTOR, M&M |
| Consumer Durables | VOLTAS, HAVELLS, BLUESTARCO, DIXON |
| FMCG & Staples | HINDUNILVR, BRITANNIA, NESTLEIND, DABUR |
| Sin & De-merit Goods | ITC, VBL, VSTIND, GODFRYPHLP |

## 4. Period Classification

| Period | Coverage |
|---|---|
| Pre-GST 2.0 | September 2024 – June 2025 |
| Implementation | September 2025 |
| Post-GST 2.0 | December 2025 – June 2026 |

## 5. Tools & Technologies

- Microsoft Excel – Data preparation, calculations, PivotTables and regression analysis.
- Microsoft Power BI – Interactive dashboard development and financial data visualisation.

## 6. Key Financial Indicators

- Sales
- Sales Growth
- Operating Profit Margin (OPM)
- Net Profit Margin (NPM)

## 7. Key Findings

### Overall Financial Performance

- Average Sales increased from ₹11,320.41 in the Pre period to ₹13,738.56 in the Post period.
- Average Sales Growth changed from 10.82% in the Pre period to -1.30% during Implementation and 7.59% in the Post period.
- Average OPM remained relatively stable, increasing from 16.67% to 17.02%.
- Average NPM increased slightly from 11.89% to 12.07%.
  
![Overall Financial Performance](./Screenshot%20(359).png)
### Category-wise Findings

- Automobile recorded the highest increase in average Sales between the Pre and Post periods at 31.71%.
- Consumer Durables recorded a 12.55% increase.
- FMCG & Staples recorded a 9.69% increase.
- Sin & De-merit Goods recorded a 1.93% increase.
  
![Category-wise Dashboard](./Screenshot%20(369).png)
### Company-wise Findings

- M&M recorded the highest average Sales at ₹47,362.25.
- GODFRYPHLP recorded the highest average Sales Growth at 63.50%.
- ITC recorded the highest average OPM at 33.46%.
- TVSMOTOR recorded the highest average NPM at 51.66%.

![Company-wise Dashboard](./Screenshot%20(372).png)
![Company-wise Dashboard](./Screenshot%20(373).png)

## 8. Regression Analysis

A simple multiple linear regression model was conducted using Sales as the dependent variable, with Implementation and Post period dummy variables and Pre-GST 2.0 as the reference category.

| Variable | Coefficient | p-value |
|---|---:|---:|
| Intercept (Pre period) | ₹11,320.41 | <0.001 |
| Implementation Period | ₹850.91 | 0.8285 |
| Post Period | ₹2,418.16 | 0.3638 |

- Number of observations: 128
- R-squared: Approximately 0.65%
- Neither period coefficient was statistically significant at the 5% level.

## 9. Project Outcome

The study provides a descriptive assessment of financial performance changes among the selected companies around the GST 2.0 implementation period.

The findings show that financial performance varied across companies and industry categories. The results do not establish a direct causal effect of GST 2.0 because other company-specific and economic factors may also have influenced performance.

## 10. Project Files

Project documentation and analysis files are provided in this repository.

## 11. Limitations

- The study covers only 16 selected companies.
- The Post-GST 2.0 period includes only three completed quarters.
- The analysis is based on secondary financial data.
- The regression model does not control for company-specific and broader economic factors.
- The findings do not establish causality.
