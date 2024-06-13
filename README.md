# MyToken
This Solidity program is a assessment program that deploy on the Ethereum blockchain. It demonstrates basic functionalities of a cryptocurrency token, which includes declaring, mininting and burning tokens and also with the basic safety checks.

## Description
MyToken contracts is the baisc cryptocurrency token contracts that has been deployed on the Ethereum. It allows user to create a simple token with specific name, abbreviation nad total supply. Includes public variables for storing the token details, mapping the address of balances to its values and fucntion for mint and burn the token. Mint function increases the total supply and the balances of a specified address, while burn function decreases the total supply and the balances of the specified address with a check to ensure suffient balance.

## Getting Started
### Installing
1) Clone the repository to your local machine using:
```
git clone https://github.com/Rahulsharmauppal/Solidity-
```

2) Ensure you have the necessary developmemt environment for Solidity like Remix IDE.You can use Remix as it is an online IDE for Solidity. To get started, go to the Remix website at https://remix.ethereum.org/.
   
4) Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol). Copy and paste the  code into the file which has been provided in the ETH PROOF Assessment file.

### Executing Program
To compile and deploy the MyToken contract:
1) Open the file MyToken in Remix IDE.
2) On the left side the taskbar Solidity Compiler icon is there, click on it and then click on ``Compile MyToken.sol``.
3) On the same taskbar there Deploy and Run Transacrtion icon, click on it and then click on the `Deploy` option.
4) Put the address value after deploying it and then click on the mint and burn function.

## Authors
Rahul Sharma

## License
This project is licensed under the MIT License - see the LICENSE.md file for details
