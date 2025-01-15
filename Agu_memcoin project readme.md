
# AGU Memecoin Project

This repository contains the implementation of AGU Memecoin and its Proxy contract.

## Features
- ERC-20 token with mint and burn functionality.
- Proxy contract to point to the implementation.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/agu-memcoin.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Configure environment variables in `.env` file.

## Deployment
Deploy the Proxy contract pointing to your implementation:
```bash
npx hardhat run scripts/deploy.js --network goerli
```
