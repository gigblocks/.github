# GigBlocks: Revolutionize Freelancing with Scroll-Powered Decentralization

GigBlocks is a decentralized platform that manages freelance jobs and payments through blockchain technology. Our mission is to create a secure, transparent, and reliable ecosystem where freelancers can find jobs, get paid fairly, and build their reputation, while clients can ensure the work they pay for is completed to their satisfaction.

## Project Overview

GigBlocks leverages blockchain technology and smart contracts to automate job creation, assignment, completion, and payment processes. By using decentralized storage and a robust reputation system, we ensure all transactions are secure, transparent, and immutable.

## Key Features

- **Job Management**: Clients can create jobs, assign freelancers, and approve completed work, with payments securely handled by smart contracts.
- **Reputation System**: Freelancers build their reputation through a non-fungible token (NFT) system, earning project points and maintaining a verified profile.
- **Payment Security**: All payments are held in escrow and only released upon job completion, ensuring fairness and security for both clients and freelancers.
- **Decentralized Storage**: User profiles and job details are stored on IPFS, ensuring data integrity and availability.

## Repositories

This project consists of three main repositories:

1. `services-gigblocks`: Handles API off-chain requests using Pinata IPFS.
2. `contracts-gigblocks`: Contains smart contracts responsible for job management, user management, ENS (Ethereum Name Service), and reputation handling.
3. `ui-gigblocks`: The frontend built with Next.js, providing an intuitive interface for clients and freelancers.

## ENS Integration & L1SLoad Precompile

- **ENS Integration**: Implements ENS as a subdomain for freelancers, acting as a reputation system. This allows freelancers to showcase their verified profile on a decentralized web, building trust and credibility in the community.
- **L1SLoad Precompile**: Utilizes Scroll's L1SLoad Precompile to bridge data from Layer 1 (L1) into Layer 2 (L2), ensuring that important reputation data and job information are accurately reflected across the blockchain.

## Smart Contracts

Our smart contracts automate the entire process from job creation to payment. The main contracts include:

- `GigBlocks.sol`: Manages job creation, assignment, completion, payment, and disputes.
- `GigBlocksUserManager.sol`: Handles user registration, profiles, ratings, and preferences.
- `GigBlocksReputation.sol`: Manages reputation tokens (NFTs) and related functionality.
- `GigBlocksJobManagement.sol`: Implements core job management functions, including creating, updating, canceling jobs, and managing payments.
- `GigBlocksView.sol`: Provides view functions for querying jobs and user profiles.
- `GigBlocksResolverScrollENS.sol`: Resolves L1 ENS Address Record into L2 Scroll Sepolia Network.

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
