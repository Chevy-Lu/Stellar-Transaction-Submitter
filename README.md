# Stellar-Transaction-Submitter

## Uses:
- Submits pre-signed transactions to the Stellar Network.
  
- Query the Network for previous submitted transactions.

## How to use: 
  In order to use this app you'll need to provide the pre-signed transaction in XDR format.
  If you have multisig enabled in your wallet once you signed a transaction in a SDEX e.g StellarX they will provide you with
  the pre-signed transaction in XDR format. Otherwise, you can get a transaction in XDR format from the Stellar 
  Laboratory "Build Transaction" tab. Once you are done adding the extra signatures ([Stellar-Offline-Signing.html](https://github.com/Chevy-Lu/Stellar-Offline-Signing)) to the pre-signed XDR you can submit it to the Network using this 
  tool. Just paste your signed transaction into the "Signed Transaction XDR:" textarea and click the submit button. 

## Side Notes:
- Submitted transactions take between 1-6 seconds to receive feedback from the network.

- To query the network for previous submitted transactions just re-input a previously used XDR. 

- This is a satandalone app meaning that it can run just using an internet browser. It doesn't require any dependencies and is OS agnostic. 

This tool is meant to complement [Stellar-Offline-Signing.html](https://github.com/Chevy-Lu/Stellar-Offline-Signing)
