# Spyder Equity Protection Stop

*Spyder Equity Protection Stop* is an Expert Advisor (EA) designed to protect your trading account from excessive drawdown. It closes all positions when the account equity falls below a predefined loss level, which is set at 5% by default. This EA can be a valuable tool for risk management and preserving your trading capital.

## Features

- **Predefined Loss Level**: The EA allows you to set a predefined loss level, which represents the percentage of your account balance at which all positions will be closed. By default, this level is set at 5%.
- **Threshold**: You can also set a threshold, which represents the percentage of your account balance at which a warning message will be printed. This can serve as an early indication of potential drawdowns.

## How it Works

1. The EA is initialized with the predefined loss level and threshold values.
2. On each tick, the current account equity is obtained.
3. If the account equity falls below the predefined loss level (calculated as a percentage of the account balance), all positions are closed, and a message is printed.
4. If the account equity falls below the threshold level, a warning message is printed.

The EA uses the `AccountInfoDouble()` function to retrieve the current account equity and balance. It then compares the equity against the predefined loss level and threshold to determine the necessary actions.

## Usage

To use the *Spyder Equity Protection Stop* EA, follow these steps:

1. Install the EA on your MetaTrader 5 platform.
2. Set the desired values for the predefined loss level and threshold in the global variables section of the code.
3. Run the EA on the desired trading chart.
4. Monitor the account equity and check for any warning messages or position closures.

Please note that *Forex Robot Easy* is not the official developer of this product. We provide this sample code as an example of how the EA can work based on the product description. For detailed reviews and trading results of this product, you can visit [this link](https://forexroboteasy.com/forex-robot-review/spyder-equity-protection-ea-review-shield-your-forex-trades/). To find the official developer of this product, please refer to MQL5.

For any issues or questions related to this code or the EA itself, please consult the official developer or refer to the documentation provided with the product.
