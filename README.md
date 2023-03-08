# TET-Bot
Tri-Indicator Equities futures Trading Bot MACD, Double Stochastics (DS), and Relative Spread Strength (RSS) built for NinjaTrader 8

Best results on Mini Dow Jones Ind ($YM) 23 minute candles

![4a2d1c07-49a0-4529-b87a-cd435e61ada1_1238x699](https://user-images.githubusercontent.com/119662508/223690863-cf9d7933-e42e-495d-bec7-29c358065a30.png)

To enter a long position, wait for the MACD plot to cross above the MACD Average plot, using a 2-period look back. Additionally, the DS with an RSS input series must be greater than 90. To exit the long position, wait for the MACD plot to cross below the MACD Average plot.

To enter a short position, wait for the MACD plot to cross below the MACD Average plot, using a 2-period look back. Also, the DS with an RSS input series must be less than 10. To exit the short position, wait for the MACD plot to cross above the MACD Average plot.

The MACD indicator should be set up with a Slow parameter of 26, Smooth of 9, and Fast of 12. The RSS indicator should be configured with an EMA1 of 10, EMA2 of 40, and Length of 5.

