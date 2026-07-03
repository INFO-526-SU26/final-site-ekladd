# Data

- **weekly_gas_prices**: The dataset is from the TidyTuesday github repo from 2025-07-01. It looks at the weekly US gas prices for both regular and diesel. The date range of this data set is from Aug 1990 to June 2025." The data comes from the U.S. Energy Information Administration (EIA), which publishes average retail gasoline and diesel prices each Monday."
- **VIX_History**: The Cboe Volatility Index® (VIX®Index) is a leading measure of market expectations of near-term volatility conveyed by S&P 500 Index®(SPX) option prices.

# Codebook for weekly_gas_prices Dataset

## Variable Names and Descriptions:

- **date**: Data is collected every Monday. The date range of this data set is from Aug 1990 to June 2025.
- **fuel:** Gasoline or diesel
- **grade:** regular, all, premium, midgrade, low_sulfur, ultra_low_sulfur
- **formulation**: all, conventional, reformulated
- **price**: Average retail prices

## Data Types:

- **date**: date
- **fuel:** chr
- **grade:** chr
- **formulation**: chr
- **price**: dbl

# Codebook for VIX_History Dataset

## Variable Names and Descriptions:

- **DATE**: Data is collected every business day. The date range of this data set is from Jan 1990 to June 2026.
- **OPEN:** Price at Open
- **HIGH:** High Price
- **LOW**: Low Price
- **CLOSE**: Price at Close

## Data Types:

- **DATE**: chr
- **OPEN:** dbl
- **HIGH:** dbl
- **LOW**: dbl
- **CLOSE**: dbl
