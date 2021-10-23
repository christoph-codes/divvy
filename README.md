<h1 align="center">  <img src="public/Divvy.png" height="120px"/></h1>

<h3 align="center">Divvy is a Decentralised Dapp made on Web3. It's a Marketplace for artists to sell their digital assets, earn royality and make some sales on the polygon matic network.</h3>

<p align="center">Made with ♥️ using <img src="https://cryptologos.cc/logos/polygon-matic-logo.png" width="40px" /> and <img src="https://pbs.twimg.com/profile_images/1357501845145485316/yo6M6Y9u.jpg" width="40px"/> by <a href="https://piyushmehta.com"><strong>Piyush Mehta</strong></a></p>


### Wallets Compatible
• [MetaMask](https://metamask.io)

### Crypto Currency for exchange of NFTs
• [Polygon Matic](http://polygon.technology)

## How to run this project locally

### 1. Setting up local env

1. Create `secret.js` in the root of the project 

```js
// secret.js get private key and project id from https://infura.io

const PRIVATE_KEY = "your private key"
const PROJECT_ID = "your project id"
module.exports = { PRIVATE_KEY, PROJECT_ID };

```

2. Installing dependencies

```bash
 ➜ yarn install
```

3. Install [Metamask](https://metamask.io) on your choice of browser

### 2. Running the blockchain locally

```bash
  ➜ npx hardhat test # To test the smart contract
  ➜ npx hardhat run scripts/deploy.js --network localhost # To get cred for local network
  ➜ npx hardhat node # create a local node
```

### 3. Running the frontend locally

```bash
  ➜ yarn dev  
```

