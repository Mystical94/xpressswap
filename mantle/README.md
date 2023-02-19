# XpressSwap

A one point destination to swap your cryptos on Filecoin blockchain

## XpressSwap Interface for Aurora(EVM Blockchain Layer for NEAR) Network

An open source interface for XpressSwap -- a protocol for decentralized exchange on Filecoin.

Enabling users to:

- Add and remove their liquidity positions on XpressSwap protocol
- Swap tokens on XpressSwap protocol


## Deploying the XpressSwap on local machine

Clone the repository

move into the filecoin Directory

```sh
cd filecoin
```

move into the UserInterface Directory

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

### ☄️ What's next?
- More features will be introduced, such as farming, staking, and limit orders to make XpressSwap more accessible to everyone and a common destination for everyone's needs.
- Creating a fully community-driven protocol in which the community votes on all protocol-related decisions.
- Making it live on the Mantle Blockchain (coming very soon 😉)

### Deployed Addresses
- Factory: [0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f](https://hyperspace.filfox.info/en/address/0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f)
- Router: [0x90d4e9eb792602aa7a7506b477b878307c35e24a](hhttps://hyperspace.filfox.info/en/address/0x90d4e9eb792602aa7a7506b477b878307c35e24a)
- WTFIL Address : [0x3221ce4ade9a9564b34992a6d9dd35e38d3884c9](https://hyperspace.filfox.info/en/address/0x3221ce4ade9a9564b34992a6d9dd35e38d3884c9)
- Multicall contract Address : [0x0c0d088a6fe7c65754d821eb94bce29c2cfb0d1d](https://hyperspace.filfox.info/en/address/0x0c0d088A6Fe7C65754D821eB94Bce29c2Cfb0D1d)

### 🚫 License
This repository includes an [unlicensed](http://unlicense.org/) statement.