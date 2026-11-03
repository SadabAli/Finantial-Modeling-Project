# Integrated Three-Statement Financial Model

An Excel-based financial model that connects the **Income Statement,
Balance Sheet, and Statement of Cashflows**, supported by a fixed assets
schedule.

## Project overview

This workbook models annual financial periods from **2022 to 2026** and
includes an opening Balance Sheet position dated **31 December 2021**.
It uses operating and financing assumptions to calculate revenue, costs,
profitability, working capital, debt, capital expenditure, depreciation,
and cash flow.

## Workbook structure

  -----------------------------------------------------------------------
  Worksheet                           Purpose
  ----------------------------------- -----------------------------------
  Income Statement                    Calculates revenue, COGS, gross
                                      profit, operating expenses, EBITDA,
                                      EBIT, EBT, taxes, and net income.

  Balance Sheet                       Tracks assets, liabilities, equity,
                                      retained earnings, debt, and the
                                      balance check.

  Statement of Cashflows              Calculates operating, investing,
                                      and financing cash flows and net
                                      cash flow.

  Fixed Assets                        Tracks capital expenditure, useful
                                      lives, annual depreciation, and
                                      total D&A.
  -----------------------------------------------------------------------

## Key model drivers

-   Cups sold and average selling price
-   Discounts and cost ratios
-   Operating expense ratios
-   Corporate tax rate
-   Accounts receivable, accounts payable, and deferred revenue
    assumptions
-   Borrowings, debt repayments, and interest rate
-   Capital expenditure and asset useful lives

## How the statements are connected

-   **Net Income** flows into Retained Earnings and is the starting
    point of the Cash Flow Statement.
-   **Depreciation** reduces Income Statement profit, is added back in
    Operating Cash Flow, and reduces the carrying value of fixed assets.
-   **Capital expenditure** increases Fixed Assets and is recorded as an
    Investing Cash Flow outflow.
-   **Borrowings and repayments** change the Balance Sheet debt balance
    and appear in Financing Cash Flow.
-   **Working-capital movements** adjust Operating Cash Flow.

## Validation and review notes

The workbook includes a formula-based Balance Check calculated as
**Total Assets minus Total Liabilities and Equity**. The uploaded
workbook's cached results show zero for the opening Balance Sheet and
each displayed year from 2022 to 2026.

The model also has items that should be reviewed before treating it as a
finished professional forecast:

1.  The 2022 cash roll-forward produces a negative cash balance of
    approximately **-\$2,871.68**. This should be explained as a funding
    gap or explicitly modelled as an overdraft/financing facility.
2.  The Lemon Crusher has a stated useful life of three years, but its
    depreciation formula continues into later periods. The depreciation
    schedule should stop depreciation when the asset is fully
    depreciated.
3.  The workbook does not clearly label which years are historical
    actuals and which are forecast. Confirm and label the period split
    before describing it as an actual-versus-forecast model.
4.  Interest is calculated using the period-end debt balance. An
    average-debt approach may be more suitable if debt changes during
    the year.

A zero Balance Check confirms that the accounting equation ties
arithmetically; it does **not** prove that every assumption,
classification, or formula is correct.

## Tools and concepts

-   Microsoft Excel
-   Financial modelling
-   Three-statement integration
-   Assumption-driven calculations
-   Fixed assets and depreciation schedule
-   Working capital and debt modelling

## Short project description

An Excel-based three-statement financial model linking profitability,
financial position, and cash flow through operating assumptions and
supporting schedules.
