# xfi

### Description
This is a protocol for margin spot trading that allows users to trade using liquidity pools from different DEXs and leverage.
The protocol includes mechanisms for managing positions, collateral, loans, and position liquidation.
The liquidity pools provided by protocol users, specifically x-fi, are used as credit assets.
Features

### Main features of the protocol:

* Leverage trading: The ability to open positions with borrowed funds, both long and short.
* Partial position liquidation: Loss protection through automatic liquidation in the event of unfavorable price changes, with the remaining balance sent to the user's account.
* Flexibility in setting credit limits: Users can adjust credit parameters based on their needs.
* Support for multiple assets: The protocol supports TON and various tokens from the TON network.
* Omniston is used as the liquidity aggregator for swaps and position liquidation.
* X-fi operates on the top of Farmix.tg smart contract for issuing credits for leverage.
