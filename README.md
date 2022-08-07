# Coins4Mars

This projects consists of a set of Solidity Smart Contracts that create 

* KaseiCoin, an ERC20 token for an eventual Mars colony
* a crowdsale contract to manage the sale of KaseiCoin
* a deployer smart contract to deploy these.

---

## Technologies

* **Solidity** - A language used to develop smart contracts on the Ethereum blockchain and other Ethereum Virtual Machine (EVM) compatible blockchains.
* **Remix IDE** - A hosted Intdgrated Development Environment (IDE) that facilitates the development, testing and deployment of smart contracts written in Solidity. The Remix IDE is available at https://remix.ethereum.org/.
* **OpenZeppelin** - an opensource library of Solidity contracts that facilitate the development of safe ERC 20 tokens.
* **Ganache** - a utility to locally deploy and test smart contracts.
* **MetaMask** - an ERC20 wallet.

---

## Evaluation Evidence
### Compiling KaseiCoin
![KaseiCoin compile](./images/kaseicoin%20compile.png)
### Compiling KaseiCoinCrowdsale
![KaseiCoinCrowdsale compile](./images/kaseicoincrowdsale%20compile.png)
### Compiling KaseiCoinCrowdsaleDeployer
![KaseiCoinCrowdsaleDeployer compile](./images/kaseicoin%20crowdsale%20deployer%20compile.png)
### Deploying KaseiCoin
![KaseiCoin Deployment-1](./images/KaseiCoin%20Deployment-1.png)
![KaseiCoin Deployment-1](./images/KaseiCoin%20Deployment-2.png)
![KaseiCoin Deployment-1](./images/KaseiCoin%20Deployment-3.png)
### Buying 1 KaseiCoin (MARS) from Crowdsale Using First Account
![buying 1 MARS from Crowdsale](./images/buying%201%20MARS%20from%20crowdsale.png)
![confirm 1 MARS buy](./images/confirm%20buy%201%20MARS.png)
![balance 1 mars](./images/Balanca%201%20Mars.png)
### Buying 5 KaseiCoin (MARS) from Crowdsale Using Second Account
![buying 5 MARS from Crowdsale](./images/buying%205%20MARS%20from%20crowdsale.png)
![confirm 5 MARS buy](./images/confirm%20buy%205%20MARS.png)
![balance 5 mars](./images/Balance%205%20Mars.png)
### Crowdsale Weis Raised
6 Ether was raised, which is equivilantly 6000000000000000000 weis.
![Crowdsale Weis Raised](./images/Crowdsale%20weis%20raised.png)
### KaseiCoin Total Supply
A total supply of 6 KaseiCoin (MARS) was minted through the crowsdale, which is equivilantly 6000000000000000000 KaseiCoin bits.
![KaseiCoin Total Supply](./images/KaseiCoin%20Total%20Supply.png)

### Enchanced Crowsale

In the following screenshots, the crowdsale contract was enhanced by inheriting:

* CappedCrowdsale
* TimedCrowdsale
* RefundablePostDeliveryCrowdsale

#### Compiling the Enhanced Crowdsale Contract
![Compiling the Enhanced Crowdsale Contract](./images/Comnpiling%20Enhanced%20Crowdsale.png)

#### Deploying the Enhanced Crowdsale Contract
![Deploying the Enhanced Crowdsale Contract](./images/Deploying%20Enhanced%20Crowdsale.png)

#### Buying 12 Mars
![Buying 12 Mars](./images/Crowdsale%20-%20buying%2012%20MARS.png)

#### Open Crowdsale Meets Goal
![Open Crowdsale Meets Goal](./images/Crowdsale%20-%20goal%20reached.png)


#### Crowdsale Finalized - Meets Goal
![Crowdsale Finalized - Meets Goal](./images/Crowdsale%20closed%20-%20goal%20reached.png)

---

## Contributors

*  **Martin Smith** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* msmith92663@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="images/LI-In-Bug.png" alt="in" width="20"/>](https://www.linkedin.com/in/smithmartinp/)


---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)