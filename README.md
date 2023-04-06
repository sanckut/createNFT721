# Sample NFT Smart Contract

How to create nft in base goerli with Hardhat

1. Create File .env
2. Add WALLET_KEY=<YOUR_PRIVATE_KEY> and BLOCKSCOUT_KEY=<YOUR_API_KEY> in .env

You can find API KEY here: https://base-goerli.blockscout.com/account/api_key

Try running some of the following tasks:

```shell
npm install
npx hardhat compile
npx hardhat run scripts/deploy.ts --network base-goerli
npx hardhat verify --network base-goerli <deployed address>
```
