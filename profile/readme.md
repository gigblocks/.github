# GigBlocks: Decentralizing Freelance Work

GigBlocks is a decentralized freelancing platform built on Scroll blockchain, leveraging ENS for reputation management. It aims to solve issues of traditional freelance platforms by offering transparency, global access, and fair treatment of freelancers. Key features include smart contract-based job management, ENS-powered reputation system, and future plans for ZK-based privacy features.

Link : https://www.gigblocks.net/
Demo : https://www.youtube.com/watch?v=Dp02qVUwQZw&t=6s

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
- Borderless, permissionless transactions for freelancers worldwide
- Provision of long-term work data within the Ethereum ecosystem


# Future Plans
- Deploying on Scroll Mainnet (ASAP)
- Implement ZK features for privacy-preserving work verification
- Expand ENS integration for comprehensive reputation management
- Develop advanced dispute resolution mechanisms

# Gigblocks SmartContracts

```
Gigblocks Smart Contract (Scroll Sepolia Network): 0xcaa94f71984474bF224E6A42b0d789d219CbFC82
Gigblocks Reputation NFT Contract (Scroll Sepolia Network) : 0x53150932ee5e5454ffbb88ca2b3ae6c3e63eeea9 
GigblocksEnsResolver (L1sload Precompile Devnet): 0x53150932EE5e5454fFbb88cA2B3Ae6C3E63eeea9
```

link Gigblocks SmartContract : https://sepolia.scrollscan.com/address/0xcaa94f71984474bF224E6A42b0d789d219CbFC82

link Gigblocks NFT Contract : https://sepolia.scrollscan.com/address/0x53150932ee5e5454ffbb88ca2b3ae6c3e63eeea9

link GigblocksEnsResolver : https://l1sload-blockscout.scroll.io/address/0x53150932EE5e5454fFbb88cA2B3Ae6C3E63eeea9


