  # LUMMY Ticket 🎫

  **Web3 Value, Web2 Experience**

  Blockchain ticketing platform that prevents fraud and scalping through innovative
  algorithm selection, giving organizers the flexibility to choose between pure Web3
  experience or hybrid Web2/Web3 approach based on their event needs.

  ## 🌟 Our Mission

  Revolutionizing the ticketing industry by eliminating fraud, reducing scalping, and
  providing transparent, secure, and user-friendly ticket management through blockchain
  technology.

  ## 🎯 Problems We Solve

  - **Ticket Fraud & Scalping**: 200% price markup, 4000+ duplicate ticket IDs
  - **Lack of Transparency**: Hidden fees and opaque resale markets
  - **Poor User Experience**: Complex Web3 interfaces limiting mass adoption
  - **Limited Flexibility**: One-size-fits-all solutions that don't match event
  requirements

  ## 🚀 Platform Features

  ### 🔗 Algorithm Flexibility

  **Algorithm 1 - Pure Web3**
  - NFT metadata updates for anti-fraud protection
  - Gasless transactions via ERC-2771
  - Perfect for tech-savvy audiences (<500 attendees)

  **Algorithm 2 - Hybrid Web2/Web3**
  - Dynamic QR codes with 30-minute refresh cycles
  - Database validation for instant entry
  - Optimized for mass adoption (500+ attendees)

  **Algorithm 3 - Zero Knowledge (Planned)**
  - Anonymous ticket verification using ZK proofs
  - Privacy-preserving entry for premium events

  ### 🛡️ Security & UX

  - **NFT-Based Tickets**: Blockchain-verified ownership prevents counterfeiting
  - **Dynamic QR Codes**: Time-based security that changes every 30 minutes
  - **Gasless Experience**: Users don't pay blockchain fees
  - **Email-Based Wallets**: Xellar Kit integration for Web2-friendly onboarding
    - Login with email only (no seed phrases required)
    - Local payment methods (BNI, e-wallets, bank transfer)
    - Automatic wallet creation for new users

  ### 🌐 Technology Stack

  - **Blockchain**: Lisk (scalable, low-cost transactions)
  - **Smart Contracts**: ERC-721 with algorithm-specific implementations
  - **Frontend**: React + TypeScript + Chakra UI
  - **Wallet**: Xellar Kit (email-based) + MetaMask fallback
  - **Payment**: IDRX stablecoin + local Indonesian payment methods

  ## 📂 Repository Structure

  ### Core Platforms
  - [`lummy-smart-contracts`](https://github.com/Lummy-Ticket/.github) - Smart contracts for all
  algorithms
  - [`lummy-frontend`](https://github.com/Lummy-Ticket/.github) - React web application
  - [`lummy-backend`](https://github.com/Lummy-Ticket/.github) - API backend for Algorithm 2
  - [`lummy-scanner`](https://github.com/Lummy-Ticket/.github) - Web-based ticket scanner

  ### Infrastructure
  - [`lummy-docs`](https://github.com/Lummy-Ticket/.github) - Documentation and guides
  - [`lummy-indexer`](https://github.com/Lummy-Ticket/.github) - The Graph subgraph for Algorithm 2
  - [`lummy-infrastructure`](https://github.com/Lummy-Ticket/.github) - DevOps and deployment configs

  ### Future Development
  - [`lummy-mobile`](https://github.com/Lummy-Ticket/.github) - Mobile application (planned)
  - [`lummy-analytics`](https://github.com/Lummy-Ticket/.github) - Analytics dashboard (planned)
  - [`lummy-sdk`](https://github.com/Lummy-Ticket/.github) - Developer SDK (planned)

  ## 🏗️ Architecture Overview
  
  ### System Components
  - **Frontend**: React web application with algorithm selection
  - **Smart Contracts**: Solidity contracts on Lisk blockchain
  - **Scanner Interface**: Web-based QR code verification
  - **Backend API**: Node.js service for Algorithm 2 database operations
  - **Database**: PostgreSQL for hybrid validation (Algorithm 2)
  - **Indexer**: The Graph subgraph for blockchain data synchronization
  - **Wallet Integration**: Xellar Kit for email-based authentication + MetaMask fallback

  ### Data Flow
  1. **User Registration**: Email login → Xellar creates wallet → Local payment top-up
  2. **Ticket Purchase**: Algorithm selection → Smart contract minting → NFT ownership
  3. **Venue Entry**: QR scan → Blockchain/database verification → Entry approval
  4. **Post-Event**: Transaction history → Analytics → Collectible NFT proof

  ## 🚦 Getting Started

  ### For Users
  1. Visit [Lummy Website] and login with email
  2. Xellar automatically creates your secure wallet
  3. Top up using local payment methods (Bank, e-wallets)
  4. Browse events and purchase tickets
  5. Show QR code at venue for entry

  ### For Organizers
  1. Connect wallet and apply for organizer status
  2. Choose algorithm based on event size and audience
  3. Create event with ticket tiers and pricing
  4. Add staff wallets for venue scanning
  5. Monitor sales and attendance in real-time

  ## 🎯 Roadmap

  ### Year 0 (2025) - Foundation
  - ✅ Algorithm 1 (Pure Web3) implementation
  - ✅ Smart contract development & testing
  - ✅ Frontend with algorithm selection
  - 🚧 Beta testing with selected events

  ### Year 1-3 (2026-2028) - Scaling
  - 🔄 Algorithm 2 (Hybrid) completion
  - 🔄 Mass adoption features
  - 🔄 Partnership with major organizers
  - 🔄 Mobile optimization

  ### Year 4+ (2029+) - Growth
  - 📋 Algorithm 3 (Zero-Knowledge Proofs)
  - 📋 International expansion
  - 📋 Advanced analytics dashboard
  - 📋 Enterprise solutions

  ## 👥 Team

  - **Zahra Sasongko** - CEO
  - **Luthfi Hadi** - CTO
  - **Joanita Timbin Panggalo** - COO
  - **Raffa Arya Nugraha** - CPO
  - **Daffa Rifki Arditya** - CMO
  - **Oktavianus Bima Jadiva** - Web3 Developer
