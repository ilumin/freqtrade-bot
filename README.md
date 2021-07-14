# freqtrade-bot

```sh
# build image
docker compose build

# install 
yarn 

# download historical data
yarn ft download-data -c user_data/config-BTCBUSD.json --exchange binance --days 90 -t 1h

# run backtest 
yarn ft backtest -c user_data/config-BTCBUSD.json --strategy SampleStrategy -i 1h 
```
