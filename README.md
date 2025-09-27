# All Weather Finance

**The first auto-rebalancing RWA that tokenizes S&P 500 stocks, gold and bonds into a single diversified portfolio.**

All Weather Finance ensures your portfolio performs in all market conditions by providing automated rebalancing across multiple asset classes. Customize your investment strategy according to your needs with our Web3-native DeFi platform.

## 🌟 Overview

All Weather Finance is a decentralized ETF protocol built on Hedera that provides diversified investment exposure through real-time price oracle integration. Our platform allows users to create and manage portfolios that automatically rebalance across:

- **S&P 500 (VOO)** - Equity exposure
- **Bonds (LQD)** - Fixed income stability  
- **Gold (XAU)** - Inflation hedge

## 🏗 Project Structure

This monorepo contains three main components:

```
allweatherfi-frontend/     # React + TypeScript frontend
allweatherfi-backend/      # NestJS backend API
allweatherfi-contracts/    # Solidity smart contracts
```

### Frontend (`allweatherfi-frontend`)
Modern Web3 DeFi application built with:
- **React 18** with TypeScript and Vite
- **Tailwind CSS** with shadcn/ui components
- **Wallet Integration** for crypto wallets
- **Real-time Price Data** via Pyth Network
- **Interactive Portfolio Management** with allocation sliders

### Backend (`allweatherfi-backend`)  
NestJS API server providing:
- RESTful API endpoints
- TypeScript-first development
- Scalable server architecture
- Integration with blockchain services

### Smart Contracts (`allweatherfi-contracts`)
Solidity contracts deployed on Hedera:
- **AllWeatherEscrow** - Main ETF trading contract
- **AllWeatherPriceOracle** - Pyth Network price feeds
- **Automated Rebalancing** logic
- **Secure Escrow** for fund management

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm/yarn/bun
- [Foundry](https://book.getfoundry.sh/getting-started/installation) (for contracts)

### Installation

```bash
# Clone the repository
git clone https://github.com/LovishB/allweather-finance.git
cd allweather-finance

# Install frontend dependencies
cd allweatherfi-frontend
npm install

# Install backend dependencies  
cd ../allweatherfi-backend
npm install

# Install contracts dependencies
cd ../allweatherfi-contracts
npm install
forge install
```

### Development

```bash
# Start frontend (port 5173)
cd allweatherfi-frontend
npm run dev

# Start backend (port 3000)
cd allweatherfi-backend
npm run start:dev

# Build contracts
cd allweatherfi-contracts
forge build
```

## 🔗 Deployed Contracts (Hedera Testnet)

- **AllWeatherEscrow**: [0.0.6915065](https://hashscan.io/testnet/contract/0.0.6915065)
- **AllWeatherPriceOracle**: [0.0.6915028](https://hashscan.io/testnet/contract/0.0.6915028)

## 🌐 Key Features

- **Diversified ETF Creation** - Buy ETF tokens with customizable allocation weights
- **Auto-Rebalancing** - Smart portfolio rebalancing based on market conditions  
- **Real-time Pricing** - Integration with Pyth Network oracles
- **Web3 Native** - Built for decentralized finance
- **Responsive Design** - Works across desktop and mobile devices

## 🛠 Technology Stack

- **Frontend**: React, TypeScript, Vite, Tailwind CSS, Ethers.js
- **Backend**: NestJS, TypeScript, Node.js
- **Blockchain**: Solidity, Foundry, Hedera Hashgraph
- **Oracles**: Pyth Network for real-time price feeds

## 📈 How It Works

1. **Connect Wallet** - Link your crypto wallet to the platform
2. **Set Allocation** - Choose your desired asset allocation percentages
3. **Buy ETF Tokens** - Purchase diversified portfolio tokens with HBAR
4. **Auto-Rebalance** - Let the protocol maintain optimal allocation
5. **Sell Anytime** - Redeem your tokens back to HBAR when needed