# Mike Piehl's Star Notary - Blockchain Project #5

Welcome to Star Notary.  This project uses the rinkeby test network on ethereum to allow you to create, buy, exchange and transfer stars.
This project is constantly growing, so please checkback often to see the latest updates.

The project uses Ethereum (rinkeby test network), Infura, Metamask and Truffle.  The project used the Truffle box:  webpack to get started and used an ERC-721 Token 
	Token Name: MDP-StarToken
	Token Symbol: MDPSTAR
	Token Address: 0xed22bAC3E99bC3b582B782bf85322Ef4999b0DC5

	Truffle Version:  5.0.2
   "openzeppelin-solidity": "^2.1.2",
    "truffle-hdwallet-provider": "^1.0.3",
    "web3": "^1.0.0-beta.37"


## How to use the project?
From the project folder, you will need to get into the ../app/ folder
Execute:  npm run dev
this will execute the project to run on your local machine.
From there, go you browser:
http://localhost:8080/

Be sure your Metamask is enabled on your browswer and connected to the Rinkeby test network.
Pick your user on Metamask.
Create yourself a star.
Once the block has been mined, you will be able to see the description by entering in your token ID.
