# A Dialogic and Dynamic NFT System

## Installation procedure
```shell
git clone git clone https://github.com/matprime/ERC-1155-NFT-demo
cd ERC-1155-NFT-demo
npm install
```
## Compiling smart contract, deployment to blockchain and test
```shell
truffle compile
truffle migrate --reset
truffle test
```
Before deploying smart contracts to blockchain "truffle migrate --reset", you need to make sure that local Ethereum blockchain is running.
Demo was tested with ganache-cli local blockchain, and Matic Mumbai testnet. <br/>
To run tests on local Ethereum blockchain then first run ganache-cli with command "ganache-cli"
and you will get 10 Ethereum test account filled with 100 test Ether to use for testing of demo.
## Starting demo
```shell
npm run start
```
Browser window will open and demo will be started. For use of demo you need to use Metamask wallet,
configure it to work with local blockchain and import one of test accounts which ganache generated.
