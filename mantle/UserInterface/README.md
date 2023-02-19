## XpressSwap Interface

An open source interface for XpressSwap -- a protocol for decentralized exchange on Mantle Network.

Enabling users to:

- Add and remove their liquidity positions on XpressSwap protocol
- Swap tokens on XpressSwap protocol

Future Plans:

- Add the functinality of Farming, Staking and Limit Orders

## Deploying the XpressSwap on local machine

Clone the repository

move into the mantle Directory

```sh
cd mantle
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