# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

# To run the test, execute the following command from the the merkle-trees directory.
```shell
npx hardhat test
```

If all your tests pass, then your Merkle Tree is working as expected! Your Solidity contract can verify the presence of a value inside a Merkle Tree using simply the root and the Merkle Proof + original values of the leaf.
