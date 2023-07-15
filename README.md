# Decentralised-Finance-Yield-Farming
A DeFi app, which provides staking &amp; farming functions are deploy-able with a website, for yield farming.

This repository presents practices about:

Setup a blockchain:
Develop Ethereum smart contracts.
Write tests for the developed Ethereum smart contracts.
Develop a client-side website so people can actually use this application.



ToDos:
Add OpenZeppelin Contracts to minimize risks.
Develop a new feature to keep track of the rewards.
Implement a method to withdraw the rewards automatically when certain conditions are met (it is triggered manually in the current version).


Installation
Setup
Node.js

sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
nvm install 12.18.3
node -v
Truffle

sudo npm install -g truffle@5.1.39 --unsafe-perm=true
Ganache installation guide can be found in here.

MetaMask installation guide can be found in here.

Commands
Install necessarily Node.js packages

npm install
Deploy smart contracts to the Ethereum blockchain

truffle migrate --reset
Deploy and run the front-end application

npm start run
Run the scripts to issue tokens

truffle exec scripts/issue-tokens.js
Demo of the DApp with the screenshots can be found on this wiki page.

