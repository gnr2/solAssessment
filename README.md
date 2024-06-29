# Solidity MyToken Project
This MetaCrafters project is a simple implementation of an ERC20-like token named "META" with the abbreviation "MTA". It includes functionalities for minting and burning tokens.

## Description
The MyToken contract allows for the creation of a token with the name "META" and abbreviation "MTA". It supports basic token operations such as minting new tokens and burning existing ones. The contract keeps track of token balances for different addresses and updates the total supply of tokens accordingly. This contract is a great starting point for understanding how token contracts work on the Ethereum blockchain.

## Getting Started
### Installing
**How to Download**:

- You can run and compile this contract using Remix, an online Etherium IDE.
- Visit [Remix](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js), create a new file and copy-paste the [contract](https://github.com/gnr2/solAssessment/blob/main/GEMD_SOLTest) code into it.


### Executing Program
**How to Run**:

1. Open [Remix](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js).
2. Create a new file and paste the Solidity code provided.
3. Compile the contract using the Solidity compiler version 0.8.18.
4. Deploy the contract to an Ethereum test network or the Remix VM (JavaScript VM).

Once deployed, play away with the contract's functions. The contract has functions to `mint`, `burn`, and `view total supply` of tokens.

## Help

**Common Problems and Solutions**:

- Ensure you have the correct Solidity compiler version (0.8.18).
- Make sure the address used in the mint and burn functions is valid and correctly formatted.
- If the burn function fails, check if the address has enough balance to burn the specified amount.

## Authors
- **gnr**
  - GitHub: **@gnr2**
  - Email: gemdavid@mymail.mapua.edu.ph
