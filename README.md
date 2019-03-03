# CryptoStar Dapp on Rinkeby Network

In this project, a smart contract based on the ERC-721 standard is implemented, enabling the creation, exchange and transfer of stars from one account to another. The __*truffle_config.js*__ file of this project is configured to deploy the smart contract in the Rinkeby network.  The __Infura__ and __Metamask__ are utilised in order to deploy the smart contract.

The ___Token name___ of the deployed token through the deployed smart contract is, __TokenStar__.

The ___Token symbol___ of the deployed token through the deployed smart contract is, __TST__.

The ___Token address___ is __0xEE3B9851051f15Bb6384c3c6A881813e5395e69B__.

The ___Truffle___, ___Solidity___ and ___Node___ versions of this project are the following:
```
Truffle v5.0.4 (core: 5.0.4)
Solidity v0.5.0 (solc-js)
Node v11.6.0
```


### Configuring your project

- Use NPM to initialize your project and install system specific software dependencies enclosed to package.json. Dependencies of this project are, truffle-hdwallet-provider, openzeppelin-solidity, etc.
```
npm install
```

## Usage

To test code follow the steps:

1: Open a command prompt or shell terminal after installing node.js and the dependencies.

2: In the project's folder, type the command:
```
truffle migrate --reset --network rinkeby
```
3: Next, enter the folder ___/app___ and type the command in order to deploy the front-end:
```
npm run dev
```



## Testing

Having deployed the smart contract, then we should connect the Metamask in the Rinkeby network in order to approve/reject the transactions that are implemented through the front-end.
