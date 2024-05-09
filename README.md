##  DEFI - ERC20 and Vault

I have successfully deployed my ERC20 contract and my vault contract defi token to the avalanche subnet created locally .

## Description

This repository contains a Solidity smart contract for an ERC20 token deployed on the Avalanche local subnet with chain ID 6969. The contract provides basic functionalities for a standard ERC20 token, including transferring tokens, approving spending, and burning tokens. The ERC20 contract address deployed to is also used to pass to the vault contract so that it is able to deposit and withdraw the xdron games tokens.

## Contract Details

- Name: xdron's games Token
- Symbol: GMG7
- Decimals: 18
- Total Supply: Initially set to 0, can be increased through minting
## Getting Started
 
### Executing the code
 
* You need to deploy this contract on remix
* But make sure to change the environment to injected provider
* connect your metamask 

To create a subnet, we run :

```cmd
avalanche subnet create mySubnet
```

* Subnet-EVM

* ChainId: 6969

* Token symbol: MOMO


Then we deploy :

```CMD
avalanche subnet deploy mySubnet
```

Connect the network in metamask

Change the environment to injected provider and connect your metamask account.

## Remix Interaction

* Deploy the ERC20 contract
* Copy the contract address and pass it to vault contract and deploy it.
* Mint some tokens in ERC20 contract
* Approve the vault contract address some tokens to be able to spend.
* You will be able to deposit and withdraw tokens in the vault contract.
 
## Authors
 
G Mohith
 
m0hithgggg@gmail.com
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
