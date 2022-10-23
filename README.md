# Pizza Wallet Smart Contracts

## Table of contents
- [Smart Contracts](#smart-contracts)
    - [Multicall3 Mainnet Addresses](#multicall3-mainnet-addresses)
    - [Multicall3 Testnet Addresses](#multicall3-testnet-addresses)
- [Development Guide](#development-guide)
    - [Requirements](#requirements)
    - [Install all dependencies](#install-all-dependencies)
    - [Hardhat](#hardhat)

## Smart Contracts
| Contract   | Feature    |
| ---------- | ---------- |
| Multicall3 | Token List |

### Multicall3 Mainnet Addresses
| Chain     | Address |
| --------- | ------- |
| Ethereum  | [0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB](https://etherscan.io/address/0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB) |
| BSC       | [0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB](https://bscscan.com/address/0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB) |
| Polygon   | [0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB](https://polygonscan.com/address/0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB) |
| Avalanche | [0x4e6EEd99e4cacab3e266305E2Ad02C1783265AfB](https://snowtrace.io/address/0x4e6eed99e4cacab3e266305e2ad02c1783265afb) |

## Development Guide

### Requirements

It is recommended to be running a Debian or Ubuntu based Linux distribution. <br>
In order to install the requirements for another OS, please refer to the official guides.  

1. NVM
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash && source ~/.nvm/nvm.sh
```
2. Node
```sh
nvm use --lts
```
3. Yarn
```sh
npm install --global yarn
```

### Install all dependencies:

```sh
yarn install
```

### Hardhat

#### Environment Variables

- In order to run any hardhat commands you must setup your envs first.

1. Copy the ``.env.example`` file and rename it to ``.env``
2. Paste your envs

#### Compile contracts

```sh
npx hardhat compile
```

#### Deploy contracts

```sh
npx hardhat run scripts/deploy.js --network [NETWORK]
```

#### Verify contracts

```sh
npx hardhat verify --network [NETWORK] [CONTRACT_ADDRESS]
```