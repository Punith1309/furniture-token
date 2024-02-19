# FurnitureToken Contract

## Overview
The FurnitureToken contract is an ERC20 token smart contract implemented on the Ethereum blockchain. It allows users to mint, transfer, redeem furniture, and burn tokens. The contract also keeps track of furniture prices and the last purchased furniture type.

## Features
- Minting tokens: Only the contract owner can mint tokens and assign them to designated addresses.
- Transferring tokens: Users can transfer tokens to other addresses.
- Redeeming furniture: Users can redeem furniture by exchanging tokens for specific furniture types (tables or chairs) based on their token balance.
- Burning tokens: Users can burn their tokens to permanently remove them from circulation.
- Determining furniture type: The contract determines the type of furniture (table or chair) based on the token amount provided for redemption.
- Retrieving balance and last purchased furniture: Users can check their token balance and the last purchased furniture type.

## Usage
1. Deploy the contract to the Ethereum blockchain.
2. Mint tokens to designated addresses using the `mintTokens` function.
3. Transfer tokens to other addresses using the `transferTokens` function.
4. Redeem furniture by calling the `redeem_Furniture` function with the desired token amount.
5. Burn tokens using the `burnTokens` function.
6. Check token balance and last purchased furniture type using the `getBalance` and `getLastPurchasedFurniture` functions respectively.

## Auhor

Punith Raj v

## License
This project is licensed under the MIT License. See the LICENSE file for details.
