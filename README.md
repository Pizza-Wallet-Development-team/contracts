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
| Chain    | Address |
| -------- | ------- |
| Ethereum | [0xeefba1e63905ef1d7acba5a8513c70307c1ce441](https://etherscan.io/address/0xeefba1e63905ef1d7acba5a8513c70307c1ce441#contracts) |
| Polygon | [0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507](https://explorer-mainnet.maticvigil.com/address/0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507/contracts) |

### multicall3 Testnet Addresses
| Chain    | Address |
| -------- | ------- |
| Goerli | [0xeefba1e63905ef1d7acba5a8513c70307c1ce441](https://etherscan.io/address/0xeefba1e63905ef1d7acba5a8513c70307c1ce441#contracts) |
| Mumbai | [0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507](https://explorer-mainnet.maticvigil.com/address/0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507/contracts) |


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

#### Compile a contract

```sh
npx hardhat compile
```