# BTC Portfolio and Investment Manager

A comprehensive portfolio management solution for Bitcoin assets across multiple chains, including Stacks, Rootstock, and BOB. This project enables users to track, manage, and optimize their BTC investments through various DeFi protocols (Velar on Stacks , Runes on Rootstock , 5+ Strategies integrated on BOB).

## 🌟 Features

- Multi-Asset Portfolio Tracking on Stacks
  - Track BTC assets across Stacks (including sBTC)
  - Real-time portfolio valuation and performance metrics
  - Transaction history and analytics

- AI-Powered Eliza Trading Assistant for Stacks
  - Natural language interaction for trading and portfolio management
  - Automated strategy suggestions and execution on stacks
  - Risk assessment and portfolio optimization on Stacks

- DeFi Protocol Integration
  - Velar Protocol integration for Stacks trading



- Implemented a portfolio management system that interacts with the Stacks blockchain
- Created a user interface for managing sBTC transactions and portfolio tracking
- Built functionality for deposits and withdrawals of sBTC using the Stacks network
- Integrated real-time price tracking and transaction history for sBTC assets
- Created a Velar-Eliza plugin for doing swaps on Stacks
- Implemented portfolio statistics tracking including total balance, deposits, and withdrawals in sBTC



Key Features Across All Integrations:
- Real-time transaction status tracking
- Comprehensive error handling
- User-friendly interface for all operations
- Cross-chain compatibility
- Transaction confirmation notifications
- Secure wallet integrations
- Price tracking and portfolio management
- Strategy-based investment options
- Bridge selection interface for cross-chain operations
- Support for multiple transaction types (swap, transfer, invest)
- Modular plugin architecture for extensibility
- Responsive and intuitive user interface
- Real-time price and portfolio updates
- Transaction history tracking
- Secure transaction signing and validation

This implementation demonstrates a comprehensive approach to blockchain interoperability, focusing on user experience while maintaining security and reliability across different blockchain networks.

## Architecture

## 🔧 Technical Stack

- Frontend
  - Next.js 14
  - TailwindCSS
  - shadcn/ui components
  - TypeScript

- Agent
  - Node.js
  - ElizaOS Core
  - Custom plugins for protocol integration
  - Natural language processing

- Smart Contracts
  - Solidity
  - ERC-7621 standard
  - OpenZeppelin contracts
  - Hardhat development environment

## Demo Video

## 🚀 Getting Started

### Prerequisites
- Node.js >= 22
- pnpm or npm
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kamalbuilds/stacks-portfolio-manager.git
cd stacks-portfolio-manager
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install agent dependencies:
```bash
cd ../agent
pnpm install
```

4. Set up environment variables:
```bash
cp frontend/.env.example frontend/.env
cp agent/.env.example agent/.env
```

5. Start the development servers:

Frontend:
```bash
cd frontend
npm run dev
```

Agent:
```bash
cd agent
pnpm start
```


### Key Components

1. Frontend
   - Portfolio dashboard
   - Transaction management
   - Strategy visualization
   - Wallet integration

2. Smart Contracts
   - Basket token implementation
   - Factory contracts
   - Proxy contracts
   - Domain vault

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


