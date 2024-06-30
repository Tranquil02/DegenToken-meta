# DegenToken 

DegenToken is an ERC20 token created using Solidity and deployed using the Remix IDE. This token allows the contract owner to mint tokens, and any user to burn and transfer tokens. Additionally, users can redeem different types of cards using the tokens they possess.

## Contract Details

### Contract Name: DegenToken

### Token Details
- **Name**: DegenGaming
- **Symbol**: DGN

### Features
1. **Minting**: The contract owner can mint tokens for players.
2. **Burning**: Any user can burn their tokens.
3. **Transferring**: Users can transfer tokens to others.
4. **Redeem Cards**: Users can redeem different types of cards by burning tokens.

## Installation

1. Clone the repository or create a new file in Remix IDE.
2. Copy and paste the contract code into your new file.


## Usage
Deploy the contract: Deploy the DegenToken contract using Remix IDE.

Mint Tokens: Only the owner can call mintToken to mint tokens for players.

Transfer Tokens: Use the transferDegen function to transfer tokens to other addresses.

Redeem Cards: Call redeemCards with the appropriate card type to redeem cards by burning tokens.

Check Balance: Use checkBalance to view the balance of tokens.

## Enum - Cards
Basic

Rara

Epic

Legendary


## License
This project is licensed under the MIT License - see the LICENSE file for details.
