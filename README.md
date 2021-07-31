# Lokian.eth: A dapp collectible card game featuring mythical creatures nft, farm tokens for defi, will be deployed soon on evm-based networks.

<!-- <img src="./screenshots/fighting_tab.png" alt="" width="1000em" height="500em">
 -->
 <img src="./screenshots/project.eth.ss2.png" alt="" width="1000em" height="500em">

***

This project was developed as a module coursework.

Thanks to Stamatis Kourkotas from

**Imperial College London:** MSc in Computing (Software Engineering)<br />
**Module:** Principless of Distributed Ledgers<br />
**Project Description:** Found in included [report](./report.pdf)<br />

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps for deployment and use of our DApp

- Firstly, deploy our smart contract found in src/contract.sol (project.eth.sol). We tested this localy on a private blockchain using [Ganache](https://www.trufflesuite.com/ganache)
- In the main file of our user interface src/App.js specify the address where you deployed the contract in the constant CONTRACT_ADDRESS.
- Install the [metamask](https://metamask.io/) extension on your browser to handle your provate blockchain account. the project has been tested with the Chrome and Mozilla browsers.
- In the project directory run:

    **`npm install`** This installs all the necessary dependencies to build our application
    
    **`npm start`** This runs the app in development mode.<br />

- Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You can see all the Creatures owned by the current metamask account and play the game.

## Remaining Tasks

Finished
- Change naming e.g. cryptoMons to creatures..ok..6/28
- Change to 8bit theme for ui..ok..07/02
- Fix ui responsiveness and css, etc..ok..07/14

Ongoing
- Change creature names and artwork from cryptomons to mythical creatures.. (mvp)
- Review breeding function, take fee (0.05%) (mvp)
- Review fighting function, make a pvp (e.g. a duel room), add bet, take fee (0.1%) from winner (mvp)
- Add token or erc20, for buying, selling of cards, 149million capped (8% dev fund, 5% marketing, 5% infrastructure costs, 12% game rewards) (mvp)

- Deploy to matic, bsc, moonbeam or ethereum compatible test networks
- Deploy to matic, bsc, moonbeam or ethereum compatible main networks

Future Plan
- Add 12hr timelock contract, other security practices.
- Add staking, e.g. deposit usdc earn erc20s, dai->erc20, etc., erc20->erc20s
- Add mini game (e.g. mini pet sim, mini pet adventure, etc), take entrance fee($2 worth of erc20),  untill 10% rewards are exhausted (feature)

