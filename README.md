# My Token

This Solidity program is a simple Token program that demonstrates the basic syntax and functionality of the Solidity programming language as well as basic functionalities of a custom Token.

## Description

This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has two function that add and remove from the balance of an account and total stack of the token. This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code contained in HealthToken.sol:

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile HealthToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "My Token" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint and burn function as well as cheking the value of the public variables present in the contract. Click on the "My Token" contract in the left-hand sidebar, and then click on the "mint" function, copy an address from the list of accouts provided by remix on the top of the left-hand sidebar, insert the account and value, separated by a coma. Finally, click on the "transact" button to execute the function and add the amount of tokens to the selected account. Do the same thing to the "burn" function for the oposite effect.

## Authors

Henrique Siva


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
