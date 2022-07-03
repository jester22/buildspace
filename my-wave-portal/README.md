# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Some notes
Run and test locally
Command: npx hardhat run scripts/run.js

Re-deploy flow
So, now that we've updated our contract we need to do a few things:
1. We need to deploy it again.
npx hardhat run scripts/deploy.js --network rinkeby
2. We need to update the contract address on our frontend.
3. We need to update the abi file on our frontend. 
