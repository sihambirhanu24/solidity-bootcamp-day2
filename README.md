# solidity-bootcamp-day2

# TokenRegistry Smart Contract

## Overview
A Solidity smart contract that allows users to register and manage tokens.

## Features
- Register tokens with name and symbol
- Store token data using mapping
- Track all token IDs using an array
- Deactivate tokens (owner only)

## Functions

### registerToken(string name, string symbol)
Registers a new token with a unique ID.

### deactivateToken(uint256 id)
Deactivates a token (only the owner can call this).

### getToken(uint256 id)
Returns token details.

### getAllTokenIds()
Returns all registered token IDs.

## Events
- TokenRegistered: emitted when a new token is added
