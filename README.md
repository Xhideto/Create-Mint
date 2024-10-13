# Create & Mint - Batcave

The smart contract creates an ERC 20 token called "BatCave" using the symbol "BAT". There were also functionalities of minting new tokens and burning tokens and pausing/unpausing token transfers.

## Description

This smart contract ensures that only the owner can `mint`, `burn` tokens, `pause`, or `unpause`, `transfers`, providing control and flexibility.

## Functions

- `mint()`: Allows the owner to create new tokens and assign them to a specified address.
- `burn()`: Allows everyone to burn tokens.
- `update()`: Overrides its own function to integrate `ERC20Pausable` functionalty.
- `pause()`: Allows the owner to pause all token transfers.
- `unpause()`: Allows the owner to resume token transfers.
- `transfer`: Allows everyone to transfer tokens to other adresses.

## Getting Started

### Installing

To use this contract, This can be done using the online version of the Solidity IDE, known as Remix.

1. Go to the Remix website at Remix Ethereum.
2. Create a new file by clicking on the “+” icon in the left-hand sidebar.
3. Save the file with a .sol extension

### Executing program

1. Copy and paste the code `Batcave.sol` file

### Compile the code

- Click on the “Solidity Compiler” tab in the left-hand sidebar.
- Ensure the “Compiler” option is set to a compatible version.
- Click on the "Compile `Batcave`" button or check the "Auto-compile" for automatic compiling of the code.

### Deploying and run the contract

- Click on the “Deploy & Run Transactions” tab in the left-hand sidebar.
- Make sure the "contract" is set to "SmartContract" with your file.
- Before deploying, make sure the account address has been copied and paste beside of the deploy button.
- Click on the “Deploy” button.

### Contract interaction

- Click on the drop-down deployed “BATCAVE” contract.
- Mint a token(Owner only)
- Use the `Puase` and `Unpause` functions to pause or resume the transactions.
- Use `transfer` to transfer token another address.
- Lastly, `burn` tokens with any specified amount.

## Help

- Check your Solidity compiler version.

- Check if the address has been set besides the deploy button to start deploying.

## Author

Jairell Louis J. Ignacio
https://github.com/Xhideto

## License

This project is licensed under the MIT
