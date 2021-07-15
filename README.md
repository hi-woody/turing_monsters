# Babaylan.eth: A dapp collectible card game featuring mythical creatures nft, farm tokens for defi, will be deployed soon on evm-based networks.

<!-- <img src="./screenshots/fighting_tab.png" alt="" width="1000em" height="500em">
 -->
 <img src="./screenshots/babaylan.eth.ss2.png" alt="" width="1000em" height="500em">

***

This project was developed as a module coursework.

Thanks to Stamatis Kourkotas from

**Imperial College London:** MSc in Computing (Software Engineering)<br />
**Module:** Principless of Distributed Ledgers<br />
**Project Description:** Found in included [report](./report.pdf)<br />

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps for deployment and use of our DApp

- Firstly, deploy our smart contract found in src/contract.sol (babaylan.eth.sol). We tested this localy on a private blockchain using [Ganache](https://www.trufflesuite.com/ganache)
- In the main file of our user interface src/App.js specify the address where you deployed the contract in the constant CONTRACT_ADDRESS.
- Install the [metamask](https://metamask.io/) extension on your browser to handle your provate blockchain account. the project has been tested with the Chrome and Mozilla browsers.
- In the project directory run:

    **`npm install`** This installs all the necessary dependencies to build our application
    
    **`npm start`** This runs the app in development mode.<br />

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You can see all the Cryptoships owned by the current metamask account and play the game.

## Remaining Tasks

- Change naming e.g. cryptoMons to babaylan.eth..ok..6/28
- Change to 8bit theme for ui..ok..07/02
- Fix ui responsiveness and css, etc..ok..07/14
- Change game context, rules, arts from cryptomons to familiars or creatures..
- Improve or re-design breeding function
- Improve or re-design fighting function
- Add token or erc20, tokenomics, for buying cards, staking, farming, etc
- Add defi or yield farming, then rewards token will be used in buying cards, etc (feature)
- Deploy to matic, bsc, moonbeam or ethereum compatible test networks
- Deploy to matic, bsc, moonbeam or ethereum compatible main networks
- Add nft or erc721, with threejs or 3d art as a rare card (feature)
- Add mini game with token and nfts as currencies (feature)

