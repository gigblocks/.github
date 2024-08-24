# GigBlocks: Decentralizing Freelance Work

GigBlocks is a decentralized freelancing platform built on Scroll blockchain, leveraging ENS for reputation management. It aims to solve issues of traditional freelance platforms by offering transparency, global access, and fair treatment of freelancers. Key features include smart contract-based job management, ENS-powered reputation system, and future plans for ZK-based privacy features.

# Project Overview

## Problem

Traditional freelance platforms lack:

- Freedom
- Global access
- Transparency
- Genuine care for freelancers

## Solution

Decentralize the core protocol for freelancing gigs, including:

- Payouts
- Escrow
- Profile management
- Communication
- Reputation

## Target Audience

- Global freelancers
- Web3 jobs market

## Competitive Landscape
- Dework (abandoned platform)
- Bounty Caster (focuses on small-scale work)
- Custom bounty platforms (resource-intensive to manage)

## Differentiators 
- Gigblocks can be Active development and maintenance
- Gigblocks Focus on medium to large-scale freelance work
- Gigblocks Easy-to-use, decentralized platform

# Technical Architecture

![image](https://github.com/user-attachments/assets/f37a0e91-9105-4e80-a90f-660740b01d95)


# Key Features

- **Job Management**: Clients can create jobs, assign freelancers, and approve completed work, with payments securely handled by smart contracts.
- **Reputation System**: Freelancers build their reputation through a non-fungible token (NFT) system, earning project points and maintaining a verified profile.
- **Payment Security**: All payments are held in escrow and only released upon job completion, ensuring fairness and security for both clients and freelancers.
- **Decentralized Storage**: User profiles and job details are stored on IPFS, ensuring data integrity and availability.

## ENS Integration & L1SLoad Precompile Scroll Devnet

- **ENS Integration**: Implements ENS as a subdomain for freelancers, acting as a reputation system. This allows freelancers to showcase their verified profile on a decentralized web, building trust and credibility in the community.
- **L1SLoad Precompile**: Utilizes Scroll's L1SLoad Precompile to bridge data from Layer 1 (L1) into Layer 2 (L2), resolving ENS Domain using scroll network.

# Repositories

This project consists of three main repositories:

1. `services-gigblocks`: Handles API off-chain requests using Pinata IPFS.
2. `contracts-gigblocks`: Contains smart contracts responsible for job management, user management, ENS (Ethereum Name Service), and reputation handling.
3. `ui-gigblocks`: The frontend built with Next.js, providing an intuitive interface for clients and freelancers.

# Sponsor-Specific Benefits

## Scroll Blockchain
- Connection of L1 data to L2
- Research and experimentation for chain growth
- Increased traffic to Scroll chain
- Future expansion of ZK features for freelancers
## ENS
- Expansion of ENS profiles
- Integration of work history into ENS
- Support for R&D in ENS applications

## Ethereum Ecosystem
- Alignment with Ethereum's mission of global financial freedom access
- Democratization of freelance protocols
- Protection and advocacy for freelancers
- Provision of long-term work data within the Ethereum ecosystem


# Future Plans
- Deploying on Scroll Mainnet (ASAP)
- Implement ZK features for privacy-preserving work verification
- Expand ENS integration for comprehensive reputation management
- Develop advanced dispute resolution mechanisms



## Getting Started

To get started with GigBlocks:

1. **Clone the Repositories**:
   ```
   git clone https://github.com/hackathon-eth-tokyo-id/services-gigblocks.git
   git clone https://github.com/hackathon-eth-tokyo-id/contracts-gigblocks.git
   git clone https://github.com/hackathon-eth-tokyo-id/ui-gigblocks.git
   ```

2. **Install Dependencies**:
   Navigate to each repository and install the necessary dependencies:
   ```
   cd services-gigblocks && npm install
   cd ../contracts-gigblocks && npm install
   cd ../ui-gigblocks && npm install
   ```

3. **Deploy Smart Contracts**:
   Deploy the smart contracts on your preferred blockchain network. Refer to the `contracts-gigblocks` repository for specific deployment instructions.

4. **Run the Services**:
   Start the API services and frontend UI. Refer to each repository's README for specific run commands.

## Contributing

We welcome contributions to GigBlocks! Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or concerns, please open an issue in the relevant repository or contact our team at support@gigblocks.net.
