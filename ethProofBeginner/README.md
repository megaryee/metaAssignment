# megCoin Project

## Description

The megCoin project is a simple Solidity smart contract that implements a basic ERC20-like token. It allows for token minting and burning functionalities, enabling users to create and destroy tokens.

## Getting Started

### Prerequisites

- Ethereum development environment (e.g., Remix, Truffle)
- Solidity compiler (version 0.8.18)

### Installing

1. Clone the repository to your local machine:
git clone https://github.com/megaryee/metaAssignment/new/main/ethProofBeginner

2. Open the Solidity contract file (e.g., `megCoin.sol`) in your preferred development environment.

3. Compile the contract using a Solidity compiler (e.g., Remix, Truffle).

### Executing Program

1. Deploy the `megCoin` contract to an Ethereum testnet or a local blockchain environment.

2. Interact with the contract using its mint and burn functions through a user interface or directly in a development environment.

## Usage

### Minting Tokens

To mint new tokens and allocate them to an address, use the `mint` function:

function mint(address receiver, uint amount) public
receiver: The Ethereum address that will receive the minted tokens.
amount: The amount of tokens to be minted and added to the receiver's balance.


Burning Tokens
To burn (destroy) tokens and reduce the token supply and a specific address's balance, use the burn function:

function burn(address from, uint amount) public
from: The Ethereum address from which the tokens will be burned.
amount: The amount of tokens to be burned.
Please note that the burn function checks if the balance of the from address is sufficient for burning the specified amount.

Authors
Meg

License
This project is licensed under the MIT License
