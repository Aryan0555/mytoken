# Loom Cryptocurrency

This is a simple token contract written in Solidity. The contract has two public variables, `tokenName` and `nickName`, which are set to "LOOM" and "LM" respectively. The contract also has a public variable `tokenSupply` which is initially set to 0.

The contract has a mapping variable `balances` which maps addresses to their token balances.

The contract has two functions:
1. `mint(address _address, uint _value)`: This function mints `_value` number of tokens and assigns them to the address `_address`.
2. `burn(address _address, uint _value)`: This function burns `_value` number of tokens from the address `_address`.

## Deployment

To deploy this contract in Remix, follow these steps:
1. Open Remix in your browser.
2. Create a new file and copy-paste the code from this repository.
3. Compile the code by clicking on the "Solidity Compiler" tab on the left-hand side of the screen.
4. Click on the "Compile MyToken.sol" button.
5. Once the code is compiled successfully, click on the "Deploy & Run Transactions" tab.
6. Select "MyToken" from the dropdown menu.
7. Click on the "Deploy" button.

Your contract should now be deployed on the blockchain!

## Author
Aryan Dange
