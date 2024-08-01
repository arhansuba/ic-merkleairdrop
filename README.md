
# IC-MerkleAirdrop
IC-MerkleAirdrop is a decentralized application that enables token distribution using Merkle Trees on the ICP Chain Fusion. This project facilitates efficient and secure airdrops of tokens to multiple recipients.

Table of Contents
Introduction
Features
Project Structure
Installation
Usage
Configuration
Contracts
Testing
Contributing
License
Introduction
IC-MerkleAirdrop is designed to provide a decentralized and efficient method for distributing tokens using Merkle Trees. This approach ensures scalability and security, allowing for large-scale airdrops with minimal gas costs.

Features
Decentralized Airdrops: Distribute tokens efficiently to a large number of recipients.
Merkle Tree Integration: Utilize Merkle Trees for secure and scalable airdrops.
Smart Contract Deployment: Deploy smart contracts on ICP Chain Fusion.
Project Structure

ic-merkleairdrop/
├── .devcontainer/
├── canisters/
├── contracts/
│   ├── Coprocessor.sol
│   ├── MerkleAirdrop.sol
│   └── MyToken.sol
├── lib/
├── packages/
├── script/
│   ├── DeployMerkleAirdrop.s.sol
│   ├── GenerateInput.s.sol
│   ├── Interact.s.sol
│   ├── MakeMerkle.s.sol
│   └── SplitSignature.s.sol
├── .gitignore
├── Caddyfile
├── Cargo.lock
├── Cargo.toml
├── README.md
Installation
To get started with IC-MerkleAirdrop, follow these steps:

Clone the repository:

git clone https://github.com/arhansuba/ic-merkleairdrop.git
cd ic-merkleairdrop
Install dependencies for the project:

npm install
Usage
Deploying the Contracts
To deploy the smart contracts, use the provided scripts in the script directory. For example:


npx hardhat run script/DeployMerkleAirdrop.s.sol
Configuration
Adjust the configuration files as needed to match your deployment setup. Configuration details can be found in the script and lib directories.

Contracts
The smart contracts are located in the contracts directory. The main contracts include:

Coprocessor.sol: Auxiliary contract for additional functionalities.
MerkleAirdrop.sol: Core contract for handling Merkle Tree based airdrops.
MyToken.sol: Custom token contract for the airdrop.
Testing
To run tests for the contracts:


npm test
Contributing
We welcome contributions to IC-MerkleAirdrop! Please open an issue or submit a pull request on GitHub.

License
This project is licensed under the MIT License. See the LICENSE file for details.
