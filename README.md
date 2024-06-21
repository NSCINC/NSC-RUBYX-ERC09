Sure, I'll add a section for the website in the README. Here’s the updated version:

---

# Patent Registry Contract for NSC Inc and Banco Bosco Jones FX

[![Solidity](https://img.shields.io/badge/Solidity-^0.8.0-blue.svg?style=flat&logo=solidity)](https://soliditylang.org/) [![Ethereum](https://img.shields.io/badge/Ethereum-Smart%20Contracts-blue.svg?style=flat&logo=ethereum)](https://ethereum.org/en/developers/docs/smart-contracts/) [![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat&logo=mit)](https://opensource.org/licenses/MIT)

This project includes a smart contract written in Solidity to register a patent for NSC Inc and Banco Bosco Jones FX, along with the creation of ERC-98 and ERC-2099 tokens.

## Table of Contents

- [Introduction](#introduction)
- [Contracts](#contracts)
  - [ERC98Token](#erc98token)
  - [ERC2099Token](#erc2099token)
  - [PatentRegistry](#patentregistry)
- [Getting Started](#getting-started)
- [License](#license)
- [Website](#website)

## Introduction

This project provides smart contracts to:
- Register a patent for NSC Inc and Banco Bosco Jones FX.
- Create and manage ERC-98 and ERC-2099 tokens.
  
The owner of the patent is Lucas Januario do Nascimento.

## Contracts

### ERC98Token

This contract represents the ERC-98 token, which follows the ERC-20 standard for tokens on the Ethereum blockchain.

### ERC2099Token

This contract represents the ERC-2099 token, also following the ERC-20 standard for tokens on the Ethereum blockchain.

### PatentRegistry

The `PatentRegistry` contract stores the details of the patent, including:
- Patent owner: Lucas Januario do Nascimento
- Birth date: 12/07/199
- NSC Inc
- Banco Bosco Jones FX
- NSC Inc owner: Lucas Januario do Nascimento
- NSC Inc National Private Heritage

It also initializes the ERC-98 and ERC-2099 tokens with specified initial supplies.

## Getting Started

To deploy these contracts, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install dependencies:**
    Ensure you have [Node.js](https://nodejs.org/) and [Truffle](https://www.trufflesuite.com/truffle) installed.
    ```sh
    npm install -g truffle
    ```

3. **Compile the contracts:**
    ```sh
    truffle compile
    ```

4. **Deploy the contracts:**
    Make sure you have a local blockchain running, for example using [Ganache](https://www.trufflesuite.com/ganache), and then run:
    ```sh
    truffle migrate
    ```

5. **Interact with the contracts:**
    Use Truffle Console or any Ethereum wallet like [MetaMask](https://metamask.io/) to interact with the deployed contracts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Website

For more information, visit our website: [NSC Inc and Banco Bosco Jones FX](http://www.yourwebsite.com)

---

Replace [`http://www.yourwebsite.com](https://nscio.vercel.app/)` with the actual URL of your website. This README provides a brief overview of the project, the contracts, and how to get started, along with a link to your website for more information.
