# Platzi Punks

Platzi Punks is a randomly generated NFT based on https://avataaars.com

## Register a new Infura account

- Go to this URL:

[Infura registration](https://infura.io/register)

- Create your first project

NETWORK*
Web3 API (Formerly Ethereum)

NAME*
My Project -> Platzi Punks

- Go to the project's dashboard

- Select the ENDPOINTS tab. Copy the API KEY. It'll be assigned into the INFURA_PROJECT_ID `.env` file variable.

- Select the SECURITY tab. Copy the API KEY SECRET. It'll be assigned into the DEPLOYER_PRIVATE_KEY `.env` file variable.

## Install project

```shell
cp .env.example .env
vi .env
```

And assign the variables:

```shell
INFURA_PROJECT_ID=XXXXX
DEPLOYER_PRIVATE_KEY=XXXX
```

Then...

```shell
npm install
```

## Hardhat commands

This project uses Hardhat. It has the corresponding smart contract, a test for that contract, a script that deploys that contract, and the task implementation.

The Hardhat tasks are:

```shell
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## Original contract

<https://rinkeby.etherscan.io/address/0x0c5f4b37b32993f7923569c1a7605c3a67ca6bc9#code>

