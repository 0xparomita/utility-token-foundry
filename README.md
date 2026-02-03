# Utility Token Foundry

A high-quality, beginner-friendly starting point for deploying an ERC-20 token on Ethereum or any EVM-compatible chain (Polygon, Arbitrum, Base).

### Features
* **Standard ERC-20:** Fully compliant with Ethereum standards.
* **Mintable:** Allows the owner to create new tokens (useful for rewards).
* **Burnable:** Allows users to destroy tokens to reduce total supply.
* **Security:** Utilizes OpenZeppelin's industry-standard `Ownable` contract.

### Quick Start
1. Install dependencies: `npm install`
2. Compile: `npx hardhat compile`
3. Deploy: Edit `deploy.js` and run `npx hardhat run deploy.js --network localhost`
