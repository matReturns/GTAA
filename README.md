# GTAA
Meb Faber's Global Tactical Asset Allocation, Replication


# Global Tactical Asset Allocation (GTAA) Strategy Replication

This repository contains R code to replicate the Global Tactical Asset Allocation (GTAA) strategy. The GTAA strategy is an investment approach that dynamically allocates capital across different asset classes based on their recent performance.

## Strategy Overview

The GTAA strategy is designed to identify and allocate to the top-performing asset classes while avoiding underperforming ones. This code aims to replicate the GTAA strategy based on the principles outlined in its theoretical framework.

## How the Code Works

The code is structured as a function that takes parameters such as start and end dates, as well as other relevant inputs, to simulate the GTAA strategy's asset allocation decisions. The key steps of the replication code include:

1. Retrieving historical price data of different asset classes using their respective ETF tickers.
2. Calculating performance metrics to assess the momentum of each asset class.
3. Selecting the top-performing asset classes based on their momentum.
4. Allocating capital to the selected asset classes based on the GTAA strategy rules.
5. Evaluating the performance of the GTAA strategy and benchmarking it against relevant benchmarks.

## Getting Started

To run the GTAA strategy replication code:

1. Clone or download this repository.
2. Open the R script containing the replication code.
3. Modify parameters such as start and end dates, look-back period, and other relevant inputs as needed.
4. Run the code to execute the GTAA strategy replication.
5. Analyze the results and visualizations generated by the code.

## Requirements

- R environment with required libraries installed (PerformanceAnalytics, quantmod, etc.).
- Internet connection to fetch historical price data.

## Disclaimer

This code is for educational and illustrative purposes only. It attempts to replicate the GTAA strategy as described in relevant literature, but its performance may vary based on various factors. Users are encouraged to thoroughly understand the strategy and code before making any investment decisions.

## Resources

- [Original GTAA Strategy Paper](link-to-the-original-paper)
- [Investopedia: Global Tactical Asset Allocation (GTAA)](link-to-relevant-article)

## Contribution

Feel free to contribute improvements, bug fixes, or additional features to enhance the replication code. Please create a pull request if you'd like to contribute.

---

*Disclaimer: This repository is not financial advice. Use the code and information at your own risk.*



























