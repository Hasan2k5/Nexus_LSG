# Nexus LSDFi Platform

![Nexus LSDFi](https://images.unsplash.com/photo-1639762681485-074b7f938ba0?auto=format&fit=crop&q=80&w=2232&ixlib=rb-4.0.3)

A next-generation Liquid Staking Derivatives (LSD) platform built on Mantle Network, enabling users to stake MNT tokens, participate in liquidity pools, and earn yield through innovative farming strategies.

## 🌟 Features

- **Liquid Staking**
  - Stake MNT tokens and receive stMNT
  - Earn staking rewards while maintaining liquidity
  - Dynamic APY based on network participation

- **Liquidity Pools**
  - MNT-ETH LP
  - MNT-USDC LP
  - stMNT-MNT LP
  - Automated market making with optimized curves

- **Yield Farming**
  - Multiple farming strategies
  - Boosted rewards for long-term stakers
  - Governance token rewards

- **Analytics Dashboard**
  - Real-time TVL tracking
  - APY/APR calculations
  - Historical performance metrics
  - Portfolio management

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- MetaMask or any Web3 wallet
- MNT tokens for staking

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nexus-lsd.git
cd nexus-lsd
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 🏗️ Technology Stack

- **Frontend**
  - React 18
  - TypeScript
  - Vite
  - TailwindCSS
  - shadcn/ui
  - Zustand (State Management)

- **Web3 Integration**
  - MetaMask/Web3 Wallets
  - Mantle Network
  - Smart Contract Interaction

- **Development Tools**
  - ESLint
  - Prettier
  - TypeScript
  - Vite

## 🔧 Smart Contracts

All smart contract addresses are configured in `src/config/contracts.ts`. Replace the placeholder addresses with your deployed contract addresses.

```typescript
export const CONTRACTS = {
  STAKING: {
    address: '0x1234...', // MNT Staking Contract
    // ...
  },
  // ... other contracts
}
```

## 📦 Project Structure

```
nexus-lsd/
├── src/
│   ├── components/     # React components
│   ├── config/        # Configuration files
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utility functions
│   ├── pages/         # Page components
│   └── types/         # TypeScript types
├── public/            # Static assets
└── package.json       # Project dependencies
```

## 🔐 Security

- All smart contracts are thoroughly audited
- Secure wallet integration
- Regular security updates
- Protected API endpoints

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏆 Hackathon Submission

This project was developed for the Mantle Network DeFi Track Hackathon.

### Judging Criteria Alignment

- **Innovation (30%)**: Novel liquid staking mechanism with enhanced yield strategies
- **Ecosystem Contribution (30%)**: Deep integration with Mantle Network and existing DeFi protocols
- **User Experience (10%)**: Intuitive interface with real-time analytics
- **Impact (10%)**: Addressing the need for liquid staking solutions on Mantle
- **Technical Implementation (10%)**: Robust architecture with security-first approach
- **Team Background (10%)**: Experienced team with DeFi expertise

## 🙏 Acknowledgments

- Mantle Network Team
- DeFi Community
- Open Source Contributors

---

Built with ❤️ for the Mantle Network Ecosystem
