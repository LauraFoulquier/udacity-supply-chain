# Supply chain & data auditing

## UML documents
PDF available [here](./docs/images/Udacity_Supplychain_testing.png)

## Versions and Libraries
- node : 14.19.0
- Truffle: 5.5.13
- Solidity: ^0.8.1
- @truffle/hdwallet-provider: 6.14.16 (used for deploying to rospten to provide wallet mnemonics)
- truffle-assert: 6.14.16 (Used for checking role based access in unit testing)

## Unit test and transaction history checks
![Unit test](./docs/images/Udacity_Supplychain_testing.png)

![Transaction history](./docs/images/transactionhistory.png)

## Transaction ID and contract address
- transaction ID:0xc54dd65cfd8be012c1ef1a67d944c4ded6f45bfb8aaf7819f6e755391e363dff
- Contract address: 0xB1126df0c32Db5dd98E05aA32cE452584414c4Ee
(https://ropsten.etherscan.io/address/0xB1126df0c32Db5dd98E05aA32cE452584414c4Ee)

## Additional notes
1. The unit tests had to be adadpted to the newer versions of Solidity
2. The contract was deployed to the testnet Ropsten as I had some issues with Rinkeby (probably linked to an old version of Truffle)
3. Used secrets.json file to setup Infura project ID and account mnemonics.
To run on your machine, rename the file secrets-template.json to secrets.json and change the variables with your own.
