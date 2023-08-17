# Token creation contract
This Solidity program is a simple "Token Creation" program that demonstrates the basic token creation and functionality of the Solidity programming language. 
The purpose of this program is to show how mint and burn function works in Blockchain and demonstrates what in intitialy and total supply is.
## Description
This Solidity smart contract exemplifies the creation and management of a basic token on the Ethereum blockchain. The contract includes features such as minting and burning tokens, demonstrating essential token-related functions.

* Token Details: The contract stores essential information about the token, including its name, abbreviation, and the total supply that will ever exist.

* Balances Mapping: This mapping connects Ethereum addresses to their respective token balances, creating a virtual ledger to monitor ownership.

* Mint Function: The mint function allows anyone to generate new tokens by specifying an address and an amount. This action increases both the total supply and the balance of the specified address.

* Burn Function: On the other hand, the burn function enables token destruction. Users can reduce the total supply and their balance by providing an address and an amount, provided the address has a sufficient balance.

* Safety Measure: The burn function includes a 'require' statement to ensure that the burning address holds enough tokens for the desired action, preventing any malicious activities.

This contract acts as a simplified illustration of token creation and control on the Ethereum blockchain, serving as a starting point for understanding more intricate smart contract implementations.
## Getting started
### Execution
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., token.sol). Copy and paste the code provided in the repository.
To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile token.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "token" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the functions. Click on the "token" contract in the left-hand sidebar, and then click on the  functions respectively. Finally, click on the "transact" button to execute the function.
## Author
Prakash
@Hackprakas
