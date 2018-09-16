# wallet-coin


Generate wallet for bitcoin and altcoins with CLI.

## Supported Coins
* Bitcoin (BTC)
* Bitcoin Cash (BCH)
* Bitcoin Gold (BTG)
* Dash (DASH)
* Decred (DCR)
* Dogecoin (DOGE)
* EOS (EOS)
* Ethereum Classic (ETC)
* Ethereum (ETH)
* Litecoin (LTC)
* Monacoin (MONA)
* Qtum (QTUM)
* Reddcoin (RDD)
* Zcash (ZEC)

## Installation
```bash
npm install wallet-coin -save
```

## Usage
```bash
var walletCoin = require('wallet-coin');
```
```bash
walletCoin.wallet('btc|bch|btg|dash|dcr|doge|eos|eth|ltc|mona|qtum|rdd|zec');
```
```bash
console.log(walletCoin.wallet('btc'));
```

<h3>function return:</h3>
```bash
{ publicAddress: '18cgqTpken7wkYqFgWaZ2ZK86pgPb7Q5F4',
  privateKey: 'KxNHvT2FgiSedTSG5NfRKJA9sVHkR45QZd31zcsgmsmW2WpFCoYz' }
```

## Secure Offline Paper Wallet Generation

It's recommended to use an air-gapped computer for high value wallet coin generation. 

* Download and install the latest Node.js binaries from https://nodejs.org/en/

* Install this cli tool from npm

* Disconnect from network

* Generate and print the wallet coin


## Donations

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KRPG68JZFXGQG)