
freqtrade download-data -p ETH/USDT -t 1d --timerange 20210701-20220501 --exchange binance


freqtrade backtesting --strategy SimpleMA_strategy -i 1d -p ETH/USDT --timerange 20210701-20220501 --starting-balance 1000
