# Chart Viewer
Display your custom charts exported from anywhere in TradingView.

## Test
Download `script.pine` and change `candles`:
> `var Candle[] candles = array.from(...)`

For Instance:
> `var Candle[] candles = array.from(Candle.new(2.0, 4.0, 1.0, 3.0), Candle.new(3.0, 5.0, 2.0, 4.0))`