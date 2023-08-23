[# Get currency

# Task

Write to the sqlite3 database using raw queries all available data in the `MONOBANK_API_URL`.
Currency codes should be presented in the `ISO` format.
Fields in the database: `CURRENCY_CODE`, `CURRENCY_UAH_CODE`, `RATE_BUY`, and `RATE_SELL`.
You can follow the links `MONOBANK_API_URL`, and `WIKI_ISO_GUIDE_URL` in the browser if necessary.


```python
MONOBANK_API_URL = "https://api.monobank.ua/bank/currency"
WIKI_ISO_GUIDE_URL = "https://en.wikipedia.org/wiki/ISO_4217"
```
