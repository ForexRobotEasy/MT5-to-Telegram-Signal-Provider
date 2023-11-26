# MT5 to Telegram Signal Provider

This code provides a solution for sending trading signals from MetaTrader 5 (MT5) to a Telegram chat, channel, or group. It utilizes the TelegramAPI library to establish a connection with Telegram's API and authenticate the user. The TradeAPI library is used to execute trades in the MT5 platform, while the ChartAPI library allows for capturing and attaching screenshots of the chart to each executed order.

## Usage

To use this code, you need to have a Telegram token and chat ID. Replace `'your_telegram_token'` and `'your_chat_id'` with your own token and chat ID in the code.

The `SendSignal` function is responsible for sending signals to the Telegram chat, channel, or group. It takes a `signal` parameter and sends a message to Telegram using the established connection. It also captures a screenshot of the chart using the `ChartCapture` function and attaches it to the message.

The `CustomizeOrderDetails` function is used to customize the order details for different subscription tiers. It takes two parameters: `subscriptionTier` and `signal`. Based on the subscription tier, it sets the `orderDetails` variable accordingly and calls the `SendSignal` function to send the customized order details to Telegram.

The `ChartCapture` function captures a screenshot of the chart and attaches it to each executed order. It saves the screenshot as `screenshot.png` and uses the `SendPhoto` function of the TelegramAPI library to send the screenshot to Telegram.

In the example usage section, the `CustomizeOrderDetails` function is called with different subscription tiers and signals to demonstrate how to send signals for different subscription tiers.

## Product Description

[MT5 to Telegram Signal Provider](https://forexroboteasy.com/forex-robot-review/mt5-to-telegram-signal-provider-review-download-and-real-results/) is a powerful tool that allows traders to receive trading signals directly in their Telegram chat, channel, or group. It provides seamless integration between the MT5 trading platform and Telegram, making it easy for traders to stay updated on market opportunities.

With MT5 to Telegram Signal Provider, traders can customize their order details based on their subscription tier. The code provided in this product allows for easy customization of order details and sending signals to Telegram. It also captures and attaches screenshots of the chart to each executed order, providing visual confirmation of the trading signals.

Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to the MQL5 platform.
