# ERC-20 Token Crowdsale

In this project, I will be creating a new monterary system and cryptocurrency.  This new system will be based on blockchain technology and solidity programming language.  Our cryptocurrency will be named KaseiCoin or KAI.
KaseiCoin will be a fungible token that’s ERC-20 compliant. The creation of the new cryptocurrency will also be followed by a crowdsale that will allow people to purchase KaseiCoin.

## Steps and smart contracts deployed:

- Create the KaseiCoin Token Contract (name, symbol, initial supply)

- Create the KaseiCoin Crowdsale Contract

- Create the KaseiCoin Deployer Contract

- Deploy and Test the Crowdsale on a Local Blockchain


The crowdsale contract created will manage the entire crowdsale process. This process will allow users to send ether to the contract and receive KaseiCoin tokens, or KAI, in return. The contract will automatically mint the tokens and distribute them to a buyer in one transaction.

In order to have our token as ERC-20 compliant, I imported  the following contracts from the OpenZeppelin Library

- ERC20

- ERC20Detailed

- ERC20Mintable

- Crowdsale

- MintedCrowdsale

## Deploy and Test of the Crowdsale on a Local Blockchain:
I performed real-world, preproduction test of the crowdsale. To do so, the following steps were completed and can be found in the testing folder:


- Deploy the crowdsale to a local blockchain by using Remix, MetaMask, and Ganache


- Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances of those accounts


- Review the total supply of minted tokens and the amount of wei that the crowdsale contract has raised

![image](https://user-images.githubusercontent.com/98672852/180325041-d4b6b233-7c3d-4cc1-b669-8911ee35f5ca.png)

