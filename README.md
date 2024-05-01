## Weapon DEFI 

I have successfully deployed my weapon defi token to the avalanche subnet created locally .

## Description

This repository contains a Solidity smart contract for an ERC20 token deployed on the Avalanche local subnet with chain ID 6969. The contract provides basic functionalities for a standard ERC20 token, including transferring tokens, approving spending, and burning tokens. Additionally, it implements a custom purchase function allowing users to purchase in-game weapons using token burning as a payment method.

## Contract Details

- Name: xdron's games Token
- Symbol: GMG7
- Decimals: 18
- Total Supply: Initially set to 0, can be increased through minting
- Announcement: Provides a list of available in-game weapons for purchase
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
 
## Authors
 
G Mohith
 
m0hithgggg@gmail.com
 
## License
 
This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
