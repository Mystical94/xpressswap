# XpressSwap

<img src="images/swap page mantle.png" alt="Logo">

<img src="images/swap page filecoin.png" alt="Logo">

### 📝 Project Description

#### 😎 Idea
- People put their money in banks thinking they have control over it, but in actuality, banks control the money.
- 'Your Money, Your Control,' is the core of Blockchain Technology which is how Decentralized Exchange work under the hood and this has long attracted me. As laws tighten, more people are turning to decentralised exchanges, discovering the actual value of blockchain and decentralised exchanges.
- Banks have unlimited control over money and can even refuse to enable customers to withdraw it in an emergency.
- There is no transparency in the operations of the Banks and everingthing is Centralized
- What's a better way to exchange your money while still having the ability to contribute to the Mantle and Filecoin Ecosystem in the form of the fees which you anyhow have to pay to the big Institutions and banks.

#### 💻 Implementation
- We have forked UniswapV2 and deployed it on the Mantle Network as well as on the Filecoin Network, as well as rendered our own UI and link the smart contracts with the UI, allowing users to interact with the protocol.
- We have also made some modifications to the Uniswap's smart contracts to automatically transmit 0.01% of the total fees for the projects, for a total of 0.08% to the global causes, 0.02% to the protocol for continued development and improvement of the protocol, and 0.3% to the liquidity providers for their contribution.
- Tools Used: Solidity, Remix, Mantle Blockchain, Filecoin Blockchain, uniswapV2, React and Metamask.

#### 👥 Intended Users
- People who wnat complete authority and transparency over their assets are the intended users as DEXs are decentralized and provides complete transparency and record which is publicaly avaliable to everyone on the Blockchain

### ✒ Summary
- XpressSwap enables anyone from anywhere in the globe to purchase and sell cryptocurrencies immediately using Mantle Network and Filecoin Network.
- XpressSwap will contribute to the projects being build on the Mantle Network as well as Filecoin Network by providing them with the funds as decided by the community.
- It does not discriminate anyone and will be open to everyone.
- Xpress Token can be earned by providing liquidity and earning a steady passive income.


### 📺 Video Demo
https://youtu.be/TX15ZyDugKc

### ☄️ What's next?
- More features will be introduced, such as farming, staking, and limit orders to make XpressSwap more accessible to everyone and a common destination for everyone's needs.
- Creating a fully community-driven protocol in which the community votes on all protocol-related decisions.


### 💪 Deployed Addresses (Mantle Testnet)
- Factory: [0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f](https://explorer.testnet.mantle.xyz/address/0xe7F7067C9ECAB27c5F7f13E02b13eD50931f6D0f)
- Router: [0x90d4e9eb792602aa7a7506b477b878307c35e24a](https://explorer.testnet.mantle.xyz/address/0x90D4e9eB792602AA7A7506b477B878307C35e24A)
- WBIT Address : [0x3221ce4ade9a9564b34992a6d9dd35e38d3884c9](https://explorer.testnet.mantle.xyz/address/0x3221CE4Ade9a9564b34992a6d9Dd35E38D3884C9)
- Multicall contract Address : [0x0c0d088a6fe7c65754d821eb94bce29c2cfb0d1d](https://explorer.testnet.mantle.xyz/address/0x0c0d088A6Fe7C65754D821eB94Bce29c2Cfb0D1d)


### 💪 Deployed Addresses (Filecoin Hyperspace Testnet)
- Factory: [0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f](https://hyperspace.filfox.info/en/address/0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f)
- Router: [0x90d4e9eb792602aa7a7506b477b878307c35e24a](hhttps://hyperspace.filfox.info/en/address/0x90d4e9eb792602aa7a7506b477b878307c35e24a)
- WTFIL Address : [0x3221ce4ade9a9564b34992a6d9dd35e38d3884c9](https://hyperspace.filfox.info/en/address/0x3221ce4ade9a9564b34992a6d9dd35e38d3884c9)
- Multicall contract Address : [0x0c0d088a6fe7c65754d821eb94bce29c2cfb0d1d](https://hyperspace.filfox.info/en/address/0x0c0d088A6Fe7C65754D821eB94Bce29c2Cfb0D1d)

### 🚫 License
This repository includes an [unlicensed](http://unlicense.org/) statement.

### 💻 Deploying the XpressSwap on local machine

Clone the repository

move into the mantle Directory for accessing XpressSwap on Mantle(Testnet) Blockchain

```sh
cd mantle
```
or

move into the filecoin Directory for accessing XpressSwap on Filecoin(Hyperspace Testnet) Blockchain

```sh
cd filecoin
```


After moving into the desired blockchin directory move into the UserInterface Directory

```sh
cd UserInterface
```

install dependencies using **yarn** or **npm**

**having some dependency version problems in yarn, so advised to use npm commands instead**

```sh
yarn

or

npm install
```
If using Windows then run these two commmands after npm install

```sh
rm -r ./node_modules/@uniswap/sdk
```
And Then this command

```sh
cp -r ./forks/@uniswap/sdk ./node_modules/@uniswap/sdk
```

start the development server
```sh
yarn start

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```

### 📷 Images

<img src="images/pool page mantle.png" alt="Logo">

<img src="images/pool page filecoin.png" alt="Logo">

<img src="images/create pair mantle.png" alt="Logo">

<img src="images/create pair filecoin.png" alt="Logo">

<img src="images/add liquidity mantle.png" alt="Logo">

<img src="images/add liquidity filecoin.png" alt="Logo">

<img src="images/remove liquidity mantle.png" alt="Logo">

<img src="images/remove liquidity filecoin.png" alt="Logo">

<img src="images/import pool mantle.png" alt="Logo">

<img src="images/import pool filecoin.png" alt="Logo">