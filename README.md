# :pizza: Ethereum and React: An introduction to building your first web dApp

## Getting Started
* Have [node](https://nodejs.org/en/) installed. If you run into trouble, this was created with `v8.9.4`
* Install and run [Ganache](http://truffleframework.com/ganache/)
* Install [MetaMask](https://metamask.io/)
  1. Create and connect to a custom RPC network using the Ganache RPC server (currently `http://127.0.0.1:7545`)
  2. Import a new account and use the private key provided by Ganache from account 1.
* Install the [Truffle Framework](http://truffleframework.com/)
  * `npm install -g truffle`
* Clone or download the repo
* Type `npm install`
  * If you get an error on install, don't panic. It should still work.
* Type `npm run start`
* Type `truffle compile` and `truffle migrate`
* Put on a pair of sunglasses and bask in your blockchain glory. :beer:

### Testing
Type `truffle test` to test.

## Troubleshooting Tips
* Is Ganache running?
* Is your MetaMask account unlocked?
* Are you using the MetaMask account associated with your Ganache account (the one we created above)?
* Are you using your custom RPC network in MetaMask?
* If MetaMask can't find your RPC network, try switching to the Main Ethereum Network and back.
* Did you `truffle compile` and `truffle migrate` whenever starting your local network or making changes to your smart contract?
* Transaction error? Try resetting the MetaMask account you created under settings.
* Is `truffle migrate` showing stale settings? Try `truffle migrate --reset`
