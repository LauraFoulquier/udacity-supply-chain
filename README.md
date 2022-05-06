# Supply chain & data auditing

## UML documents
PDF available [here](./docs/images/Udacity_Supplychain_testing.png)

## Versions and Libraries
- node : 14.19.0
- Truffle: 5.4.3
- Solidity: ^0.8.1
- @truffle/hdwallet-provider: 6.14.16 (used for deploying to rinkeby to provide wallet mnemonics)

## Unit test and transaction history checks
![Unit test](./docs/images/Udacity_Supplychain_testing.png)

![Transaction history](./docs/images/transactionhistory.png)

## Transaction ID and contract address
- transaction ID:
- Contract address: 

## Additional notes
1. The unit tests had to be adadpted to the newer versions of Solidity
2. Used secrets.json file to setup Infura project ID and account mnemonics.
To run on your machine, rename the file secrets-template.json to secrets.json and change the variables with your own.
