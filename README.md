# Three-Statement Financial Modeling | Apex Solutions Inc.

A five-year financial forecasting project built in **Microsoft Excel** for **Apex Solutions Inc.**, a fictional technology company operating across Software, Hardware, and IT Services.

This is an independent case-study project based on materials from **WallStreetMojo**. My goal was to understand how the **Income Statement, Balance Sheet, and Cash Flow Statement** work together and how business assumptions affect profitability, cash flow, and financial position.

## Project Overview

Using three years of historical financial information as a starting point, I prepared five years of projections. The model combines segment-level revenue forecasts with assumptions about operating costs, working capital, capital expenditure, depreciation, borrowing, and interest.

**Model units:** USD millions, unless stated otherwise. The forecast periods are labeled **Year 1–Year 5**, rather than specific calendar years.

## What I Worked On

- Forecasted revenue separately for Software, Hardware, and IT Services using the growth assumptions in the case study.
- Projected operating expenses, EBITDA, EBIT, taxes, and net income.
- Built supporting schedules for working capital, capital expenditure and depreciation, and debt and interest.
- Linked the financial statements to forecast cash balances, assets, liabilities, and shareholders' equity.
- Reviewed profitability, liquidity, leverage, and cash flow using financial ratios and statement checks.

## Excel Workbook Structure

| Worksheet | What it covers |
| --- | --- |
| `Index` | Navigation to the model's worksheets |
| `Apex Solutions IS` | Segment revenue forecasts, expenses, EBITDA, EBIT, and net income |
| `Apex Solutions BS` | Forecast assets, liabilities, equity, and financial ratios |
| `Apex Solutions CF` | Operating, investing, and financing cash flows |
| `Dep Capex` | Capital expenditure, depreciation, and fixed-asset projections |
| `Working Capital` | Receivables, inventory, payables, and the cash conversion cycle |
| `Debt` | Borrowing, repayments, interest expense, and interest income calculations |

## Key Forecast Assumptions

| Driver | Forecast assumption |
| --- | --- |
| Software revenue growth | 20% per year |
| Hardware revenue growth | 18% per year |
| IT Services revenue growth | 16% per year |
| Cost of sales | 50% of Software revenue; 48% of Hardware revenue; 50% of IT Services revenue |
| Selling, general and administrative expenses | 15% of total revenue |
| Receivables collection period | 19 days |
| Inventory processing period | 70 days |
| Supplier payment period | 48 days |
| Planned annual capital expenditure | $10,000m; $11,500m; $13,000m; $13,500m; $15,000m |
| Annual term-loan repayments / new borrowing | $2,000m / $1,000m |
| Term-loan interest rate | 9% |
| Interest rate on cash deposits | 3% |

The workbook also uses an effective tax rate of **23.4%** and depreciation of **4.5% of revenue** in the forecast.

## Forecast Highlights

The table below summarizes selected **model outputs**, not actual company results.

| Metric | Last Historical Year | Forecast Year 5 |
| --- | ---: | ---: |
| Revenue | $38,800m | $90,976m |
| EBITDA | $13,700m | $32,404m |
| Net income | $7,950m | $20,655m |
| Net profit margin | 20.5% | 22.7% |
| Cash and equivalents | $1,400m | $16,529m |
| Total debt | $25,200m | $20,200m |

**Main takeaway:** Under the model's assumptions, revenue increases at approximately **18.6% annually** over five forecast years, while projected profitability and liquidity improve and outstanding debt decreases.

The working-capital assumptions imply a **41-day cash conversion cycle** (19 days receivables + 70 days inventory − 48 days payables).

## How the Three Statements Connect

1. **Income Statement:** Revenue and expense forecasts determine net income.
2. **Supporting schedules:** Working capital, CapEx/depreciation, and debt schedules calculate changes that affect the financial statements.
3. **Cash Flow Statement:** Net income is adjusted for non-cash items and working-capital movements, then combined with investing and financing cash flows to calculate ending cash.
4. **Balance Sheet:** Ending cash, projected operating assets, debt, and retained earnings are reflected in the forecast balance sheet.

The balance-sheet check line shows **zero differences** in the five forecast periods of this version.

## How to Explore the Model

1. Download the [Excel financial model](./Financial_Modeling_Template_without_solutions_St.xlsx).
2. Open it in Microsoft Excel and start with the `Index` worksheet.
3. Review `Apex Solutions IS` for the revenue and profitability forecasts.
4. Explore `Working Capital`, `Dep Capex`, and `Debt` to understand the assumptions feeding the financial statements.
5. Review `Apex Solutions CF` and `Apex Solutions BS` for projected cash flows, financial position, and ratios.

## Scope and Limitations

This is a **learning project**, not a valuation report or investment recommendation. Apex Solutions Inc. is a **fictional case-study company**, and the results depend on the assumptions provided.

Some later-year forecast values are manually entered rather than fully formula-driven, and the interest-income figures in the Income Statement do not yet fully reconcile with the Debt schedule. Historical cash flows are not populated in the workbook. These areas would need refinement before presenting the model as fully automated or using it for a real financial decision.

## Skills Practiced

**Three-statement modeling · Financial forecasting · Excel · Working capital analysis · Cash flow forecasting · CapEx and depreciation modeling · Debt scheduling · Financial ratio analysis**

## Credits

Case-study scenario and original training materials: [WallStreetMojo](https://www.wallstreetmojo.com/). This repository is an independent educational exercise and is not affiliated with or endorsed by WallStreetMojo. The original training materials remain the property of their respective copyright holder; ensure you have permission before publicly redistributing the supplied template or case-study PDF.

## Author

Rahed Hussain
