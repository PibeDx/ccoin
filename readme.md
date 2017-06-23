# ccoin [![Build Status](https://travis-ci.org/crypti/ccoin.svg?branch=master)](https://travis-ci.org/crypti/ccoin) [![Coverage Status](https://coveralls.io/repos/github/crypti/ccoin/badge.svg?branch=master)](https://coveralls.io/github/crypti/ccoin?branch=master)

> Convert and fetch the price conversions of cryptocurrencies within your terminal

![screenshot](media/screenshot.png)

## Install

```
$ npm install --global @crypti/ccoin
```

## Usage

```
Usage
  $ ccoin -f=[fromSymbols] -t=[toSymbols]

Options
  -f, --from     A comma-delimited list of symbols to convert from
  -t, --to       A comma-delimited list of symbols to convert to

Examples
  $ ccoin -f=BTC -t=ETH,USD,LTC
  $ ccoin --from=BTC,ETH --to=USD,LTC,EUR
```

**Tip:** For a list of 3-letter symbols you can use with this module see [cryptocurrencies](https://github.com/radiovisual/cryptocurrencies).

## Related

[eth-price](https://github.com/crypti/eth-price) - Fetch and compare current ETH price to other currencies/cryptocurrencies in your terminal.

## License

MIT © [Crypti Team](https://github.com/crypti/ccoin)
