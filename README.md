# Open-Source-Finance-Coinbase-Valuation

This file contains a valuation model for Coinbase that accompanies the detailed discussion and analysis published on Open Source Finances' blog post (https://opensourcefinance.substack.com/p/coinbase-deep-dive-part-3). Using a discounted cash flow (DCF) model, it forecasts Coinbase's future cash flows up to 2026 and discounts this back to the present date (30 April 2021) to arrive at an estimate of Coinbase's value and share price.

The model is divided into three sections:
 1. **Output**: which contains the DCF model output and valuation results
 2. **Analysis**: which contains all of the intermediate analysis performed to forecast Coinbase's revenues and costs, and estimate its discount rate
 3. **Data**: which contains a copy of the underlying data relied upon in the analysis, which references to their source

The sections contain the following tabs:
 1. **DCF**: a summary of the DCF and valuation results
 2. **Transaction revenues**: an analysis of the correlation between Monthly Transacting Users (MTUs), transaction volumes, average revenue per transacting user (ARPTU), and Bitcoin's price
 3. **Asset-based revenues**: an analysis of the correlation between Assets on Platform, subscription and service revenues, and Bitcoin's price
 4. **Bitcoin price**: a Bitcoin price forecast based on the Stock-to-Flow (S2F) model, with adjustments for the extent of over- and under-valuation and diminishing volatility over time
 5. **Revenue forecast**: a forecast of revenues based on my modelling assumptions
 6. **Discount rate**: an estimate of Coinbase's discount rate, using Bitcoin's monthly returns as a proxy
 7. **IS (Annual)**: Coinbase's income statement for the years ending 31 December 2019 and 31 December 2020, obtained from its S-1 filing
 8. **IS (Quarterly)**: Coinbase's quarterly income statement for each quarter from Q1 2019 to Q1 2021, obtained from its S-1 and 8-K filings
 9. **BS**: Coinbase's balance sheet for the years ending 31 December 2019 and 31 December 2020, obtained from its S-1 filing
 10. **Operational**: operational metrics for Coinbase, obtained from its S-1 filing
 11. **CFS**: Coinbase's cash flow statement for the years ending 31 December 2019 and 31 December 2020, obtained from its S-1 filing
 12. **Forecasts**: management forecasts from Coinbase's Q1 2021 earnings call
 13. **BTCUSD**: historical price and other on-chain data for Bitcoin
 14. **SPY**: historical price data for the S&P 500 index

As a visual guide, cells that contain hard-coded inputs have been shaded in light grey. The key model outputs have been shaded in light orange.

The model is freely available for download and (non-commercial) use. All rights and intellectual property belong to Open Source Finance. 

Copyright © 2021 Open Source Finance.
