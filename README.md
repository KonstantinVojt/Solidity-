# Blockchain Solidity Basics

A learning repository covering Solidity fundamentals and token standard implementations. Built while studying smart contract development from the ground up.

## Contents

### Demo Contracts (`contracts/demo/`)
Basic Solidity concepts and patterns:
- Payment contracts
- Ownership patterns
- Libraries
- Event loggers
- Tree data structures

### ERC20 from Scratch (`contracts/erc20/`)
Full ERC20 token standard implemented manually without OpenZeppelin. Written as a learning exercise to understand the standard internals – transfer logic, allowances, approvals, and events.

### ERC721 from Scratch (`contracts/erc721/`)
Full ERC721 (NFT) standard implemented manually without OpenZeppelin. Covers token minting, ownership tracking, approvals, and safe transfer logic.

### Dutch Auction (`contracts/auction/`)
`AuctionDanishEngine` – the final project of this course. A full Dutch auction implementation with fees, pause/unpause, and custom errors.

See the standalone repo for full details: [AuctionDanish](https://github.com/KonstantinVojt/AuctionDanish)

## Tests

Tests cover demo contracts, the auction engine, and MShop scenarios.

```bash
npm install
npx hardhat test
```

## Tech Stack

- Solidity
- Hardhat
- JavaScript
- Ethers.js
- Chai
