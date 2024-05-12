# MyToken

## Overview

MyToken is a simple Solidity smart contract that implements a basic ERC20-like token. It allows users to mint new tokens and burn existing tokens. The contract includes functions to manage token details such as name, abbreviation, and total supply, as well as functionalities to interact with token balances.

## Purpose

The purpose of MyToken is to provide a starting point for developers interested in creating their own ERC20-compatible tokens on the Ethereum blockchain. It serves as a learning resource and a template for understanding fundamental concepts in Solidity smart contract development, such as state variables, mappings, and functions.

## Functionality

### Public Variables

- `name`: Stores the name of the token.
- `abbrv`: Stores the abbreviation of the token.
- `totalSupply`: Stores the total supply of the token.

### Public Functions

- `mint(address _recipient, uint _value)`: Allows users to mint new tokens and assign them to a specific recipient.
- `burn(address _owner, uint _value)`: Allows users to burn existing tokens owned by a specific address.

## Getting Started

To deploy and interact with the MyToken contract, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/my-token.git
```

2. Navigate to the root folder of the project:

```
cd my-token
```

3. Deploy the contract to an Ethereum-compatible network using tools like Remix, Truffle, or Hardhat.

4. Once deployed, interact with the contract using Ethereum wallets or through scripts using web3.js or ethers.js.

## License

This project is licensed under the [MIT License](LICENSE).
