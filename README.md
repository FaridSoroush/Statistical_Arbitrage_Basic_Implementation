# Statistical Arbitrage Basic Implementation

This project demonstrates a basic implementation of a statistical arbitrage strategy, specifically focusing on pairs trading, using historical data of the S&P and DJX indexes. The essence of statistical arbitrage lies in identifying and exploiting the temporary inefficiencies between two closely related financial instruments. Our approach uses the concept of mean reversion, where we calculate the historical price ratio of these indexes, identify deviations from the mean, and execute trades based on these deviations.

## Strategy Overview

The strategy involves:

- Calculating the daily closing price ratio of the S&P index to the DJX index.
- Determining the historical mean and standard deviation of this ratio.
- Identifying entry points for trades when the ratio deviates by more than 2 standard deviations from its historical mean.
- Executing trades with the expectation that the ratio will revert to its mean, thus capturing profits from these inefficiencies.

## Repository Structure

- `main.ipynb`: The Jupyter notebook that contains the full implementation of the statistical arbitrage strategy, including data loading, analysis, and visualization.

## How to Use

1. Clone the repository.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Open `main.ipynb` in Jupyter to view the implementation.
4. The notebook is annotated with comments for ease of understanding and can be modified to test different parameters or strategies.

## Requirements

- Python 3
- pandas
- matplotlib
- numpy (optional for further analysis)

## Disclaimer

This project is for educational purposes only and is not intended as financial advice. The implementation does not account for transaction costs, market impact, or other real-world trading factors.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](#) if you want to contribute.

## License

[MIT](LICENSE)

