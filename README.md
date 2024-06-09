# metacrafters_ETH_PROOF_Project
This report contains project assessment code for the ETH PROOF: Beginner EVM course under metacrafter.

# Code outline

- Public variables to store token details
- A mapping to track balances.
- A mint function to add tokens.
- A burn function to destroy tokens, with a check to ensure the sender has enough balance.

# MyToken Smart Contract

# Description
This smart contract implements a simple token system with mint and burn functionalities. It is built on the Ethereum blockchain using Solidity.

# Features
  - Public variables to store token details:
  - `tokenName`: The name of the token (e.g., "matic").
  - `tokenAbbrv`: The abbreviation of the token (e.g., "mtc").
  - `totalToken`: The total supply of the token.
- A mapping to store the balance of each address.
- `mint` function to create new tokens and assign them to an address.
- `burn` function to destroy tokens from an address, with a check to ensure sufficient balance.

# Functions

# mint
solidity
function mint(address _address, uint _val) public

- Increases the total token supply by _val
- Adds _val tokens to the balance of _address

# Burn
- function burn(address _address, uint _val) public
- Decreases the total token supply by _val.
- Deducts _val tokens from the balance of _address.
- Ensures that _address has at least _val tokens before burning.

# Deployment

- Ensure you have Solidity 0.8.18 installed.
- Compile the contract using a Solidity compiler.
- Deploy the contract to your preferred Ethereum network.

# Usage

- Use the mint function to create new tokens and assign them to a specific address.
- Use the burn function to destroy tokens from a specific address, ensuring the address has enough tokens to burn.

# Project by

- Anshuman Roshan
