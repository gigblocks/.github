GigBlocks - Revolutionize Freelancing with Scroll-Powered Decentralization
Welcome to GigBlocks, a decentralized platform designed to manage freelance jobs and payments through blockchain technology. Our goal is to create a secure, transparent, and reliable ecosystem where freelancers can find jobs, get paid fairly, and build their reputation, while clients can ensure the work they pay for is completed to their satisfaction.

Project Overview
GigBlocks leverages the power of blockchain technology and smart contracts to automate the processes of job creation, assignment, completion, and payment. By using decentralized storage and a robust reputation system, we ensure that all transactions are secure, transparent, and immutable.

Key Features
Job Management: Clients can create jobs, assign freelancers, and approve completed work, with payments securely handled by smart contracts.
Reputation System: Freelancers build their reputation through a non-fungible token (NFT) system, earning project points and maintaining a verified profile.
Payment Security: All payments are held in escrow and only released upon job completion, ensuring fairness and security for both clients and freelancers.
Decentralized Storage: User profiles and job details are stored on IPFS, ensuring data integrity and availability.
Repositories
This project consists of three main repositories:

services-gigblocks - Handles API off-chain requests using Pinata IPFS.
contracts-gigblocks - Contains smart contracts responsible for job management, user management, ens ( ethereum name serve, and reputation handling.
ui-gigblocks - The frontend built with Next.js, providing an intuitive interface for clients and freelancers.
ENS Integration & L1SLoad Precompile
A key feature of GigBlocks is the implementation of ENS (Ethereum Name Service) as a subdomain for freelancers, which acts as a reputation system. This allows freelancers to showcase their verified profile on a decentralized web, building trust and credibility in the community.

Additionally, we're using L1SLoad Precompile from Scroll to bridge data from Layer 1 (L1) into Layer 2 (L2). This ensures that important reputation data and job information are accurately reflected across the blockchain, providing a seamless and efficient user experience.

Smart Contracts
Our smart contracts are the backbone of GigBlocks, automating the entire process from job creation to payment. The main contracts include:

GigBlocks.sol - Manages job creation, assignment, completion, payment, and disputes.
GigBlocksUserManager.sol - Handles user registration, profiles, ratings, and preferences.
GigBlocksReputation.sol - Manages reputation tokens (NFTs) and related functionality.
GigBlocksJobManagement.sol - Implements the core job management functions, including creating, updating, canceling jobs, and managing payments.
GigBlocksView.sol - Provides view functions for querying jobs and user profiles.
GigBlocksResolverScrollENS.sol - Resolves from L1 ENS Address Record into L2 Scroll Sepolia Network.
Getting Started
To get started with GigBlocks:

Clone the Repositories: Clone the services-gigblocks, contracts-gigblocks, and ui-gigblocks repositories.
Install Dependencies: Navigate to each repository and install the necessary dependencies using npm install.
Deploy Smart Contracts: Deploy the smart contracts on your preferred blockchain network.
Run the Services: Start the API services and frontend UI.
