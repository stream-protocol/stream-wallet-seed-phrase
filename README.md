# Stream Wallet Seed Phrase

This tool enables creating and converting mnemonic-phrases, public key and private key for Stream Wallet accounts.

### Install
```js
npm i stream-wallet-seed-phrase
```

### Usage
```js
const { parseSeedPhrase, generateSeedPhrase } = require('stream-wallet-seed-phrase');

// to create a seed phrase with its corresponding Keys
const {seedPhrase, publicKey, secretKey} = generateSeedPhrase()

// To recover keys from the seed phrase
const { publicKey, secretKey } = parseSeedPhrase(seedPhrase);
```
