## Simple Vue.js + Vuex + Metamask

### Summary
The goal of this test is to make you code a small VueJS app.

The app will have three views, real time updated orderbook, a small dashboard with a graphic view and Metamask form interaction. Each view can be acceded via a link in a top navbar at the top of the app. The top navbar should read "RT Orderbook", "Candlesticks graphic" and "Wallet integration".

#### 1. Realtime orderbook

For the first tab, the dev will have to create an orderbook, as seen on any exchange, with price level, colored amounts, side, real time update, etc.
For this you can check the FTX WS/API (https://docs.ftx.com/) to fetch proper data, any pair will be ok, suggested btc/usd.

The order book will need to update real time and reflect proper updates by flashing the side / level that changed (with flash we say background color momentarily changed)

Finally, the price on each level should be clickeable, and the click event will have to fetch said price and show it on a alert or any div/tag/input on the same page.

#### 2. Candlesticks graphic view

The Candlesticks graphic should have an OHLCV chart (we recommend trading-vue-js) and it should be filled with proper formatted data. An example source can be:

https://api-pub.bitfinex.com/v2/candles/trade:1h:fUSD:a30:p2:p30/hist


* Information should also be updated real time coming from a websocket and the graph component should react to reflect changes properly.

Useful links:

- https://infura.io/
- https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=es
- https://developers.rsk.co/rsk/public-nodes/
