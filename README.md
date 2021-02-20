# Binance Truffle Box

### Install truffle
https://www.trufflesuite.com/docs/truffle/getting-started/installation

Download ("unbox") the Binance Truffle Box:
Binance

`truffle unbox aadorian/BinanceTruffleBox`

rename .env.example to .env and configure

```
MNEMONIC =
URL_BINANCE_TESTNET =
URL_BINANCE_MAINNET =
BINANCE_API_KEY =
```
### Install dependencies
`npm install`



Migrate your contract to the Binance Smart Chain
`truffle migrate --network binance`
Also you can very the deployed contract

`truffle run verify Migrations --network binance`

## Video

[![asciicast](https://asciinema.org/a/ut5GGBPsxZcq7ANTfGZ6a5ONn.svg)](https://asciinema.org/a/ut5GGBPsxZcq7ANTfGZ6a5ONn)


*NOTE:* BINANCE_API_KEY is the generated key api for verify constracts (optional)
https://bscscan.com/myapikey
