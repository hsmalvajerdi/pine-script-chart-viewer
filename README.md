# Pine Script Chart Viewer
Display your custom charts exported from anywhere in TradingView.

## Test
Download `script.pine` and put your candles on `candles`:
<br>`var Candle[] candles = array.from(...)`

<br>For instance:
<br>`var Candle[] candles = array.from(Candle.new(2.0, 4.0, 1.0, 3.0), Candle.new(3.0, 5.0, 2.0, 4.0))`

<br>Candle details:
<br>`Candle.new(open_1, high_1, low_1, close_1)`

<br>Screenshot:
![screenshot](https://github.com/hsmalvajerdi/pine-script-chart-viewer/blob/master/screenshot.png?raw=true)