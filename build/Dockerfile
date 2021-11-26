FROM freqtradeorg/freqtrade

COPY config_binance.example.json /freqtrade/user_data/config.json
COPY sample_strategy.py /freqtrade/user_data/strategies/sample_strategy.py

ENTRYPOINT ["freqtrade"]
CMD [ "trade", "--strategy=SampleStrategy" ]
