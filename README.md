# FundMe Smart Contract
## Overview

The FundMe Smart Contract is a decentralized application (DApp) developed in Solidity, allowing users to contribute Ether (ETH) to a fund. The contract utilizes Chainlink's decentralized oracle network to fetch the conversion rate of Ether to USD, ensuring a minimum contribution threshold in USD.
## Features
- Users can send Ether to the fund through the fund function.
- Only the contract owner can withdraw funds using the withdraw function.
- Minimum contribution threshold: 5 USD.
- Utilizes Chainlink Price Feeds for accurate conversion rates.
- Written in Solidity for Ethereum blockchain.
