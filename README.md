# Nifty Wallet Inpage Provider

Used to initialize the inpage ethereum provider injected by MetaMask.

## Installation

`yarn add metamask-inpage-provider`

## Usage

```javascript
// Create a stream to a remote provider:
var niftywalletStream = new LocalMessageDuplexStream({
  name: 'inpage',
  target: 'contentscript',
})

// compose the inpage provider
var inpageProvider = new MetamaskInpageProvider(niftywalletStream)
```
