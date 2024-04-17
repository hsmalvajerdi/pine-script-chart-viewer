# Pine Script Chart Viewer
Display your custom charts exported from anywhere in TradingView.

## Test
- Hide main chart
- Download `script.pine` and put your candles on `candles`:
<br>`var Candle[] candles = array.from(...)`
- Put your orders on `orders`:
<br>`var Order[] orders = array.from(...)`

<br>For instance:
- `var Candle[] candles = array.from(Candle.new(2.0, 4.0, 1.0, 3.0), Candle.new(3.0, 5.0, 2.0, 4.0))`
- `var Order[] orders = array.from(Order.new(1, 4, 5.4, 1.5, 1), Order.new(6, 8, 1, 2.5, 3))`

<br>Details:
- `Candle.new(open_1, high_1, low_1, close_1)`
- `Order.new(left_1, right_1, green_value_1, middle_value_1, red_value_1)`

<br>Screenshot:
![screenshot](./screenshot.png?raw=true)

<br>Tradingview link:
<br>https://www.tradingview.com/script/dQLsHoIx-Pine-Script-Chart-Viewer/