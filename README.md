# 1InchDailyVolumePairs

This repo contains a python notebook which fetches the total volume for all pairs on 1inch. There is a sample output in csv format which contains 3-4 days worth of transactions.

## How to use

1. Get your API keys from [Etherscan](https://etherscan.io/) and [Ethplorer](https://ethplorer.io/).
2. Replace the API keys where appropriate
3. Run the rest of the notebook
4. Change block numbers as required.

Note: There are rate limits on the API calls, the exact numbers can be found on the respective websites. The daily volume may change depending on the timezone used as they may cut off at different times.


## How it works

Transactions hashes were taken from [1Inch V3 Contract](https://etherscan.io/address/0x11111112542d85b3ef69ae05771c2dccff4faa26) and parsed transaction by transaction.
