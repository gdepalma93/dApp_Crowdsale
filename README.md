# Crowdsale dApp
---

This decentralized application was built using

1. Solidity: Solidity is a smart contract programming language that runs on many blockchains, namely, Ethereum (EVM) compatible chains. It is heavily inspired by Javascript, C++, and Python
2. Ethereum: Global, open-source platform for decentralized applications
3. Remix: Open Source IDE that helps your write Solidity contracts straight from the browser
4. Ganache: Personal blockchain for rapid Ethereum dApp development
5. 
    
This decentralized application is currently made up of 2 smart contracts

* [`Crowdsale.sol`](Crowdsale/Crowdsale.sol)  

    - Function: Manage crowd funding process    
    - Smart Contract Detail: This contract leverages open zeppelin libraries to const  
    
* [`PupperCoin.sol`](Crowdsale/PupperCoin.sol)   
    - Function: Construct an ERC 20 Token  
    - Smart Contract Detail: This contract allows users to send ETH and get back PUP (PupperCoin).This contract will mint the tokens automatically and distribute them to buyers in one transaction.

You will need to create an ERC20 token that will be minted through a `Crowdsale` contract that you can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin).
This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will need to inherit `Crowdsale`, `CappedCrowdsale`, `TimedCrowdsale`, `RefundableCrowdsale`, and `MintedCrowdsale`.

You will conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.
