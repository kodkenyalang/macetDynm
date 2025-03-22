# MacetDym

<div align="center">
  <img src="generated-icon.png" alt="MacetDym Logo" width="100" />
  <h3>Decentralized Traffic Management in Jakarta</h3>
  <p>Built on Dymension blockchain with AI processing and Filecoin storage</p>
</div>

## 📋 Overview

MacetDym ("Macet" means traffic jam in Indonesian) is a decentralized application (dApp) that connects people's waiting times in traffic to central traffic management systems in Jakarta, Indonesia. The application utilizes AI agents to collect and process traffic data, which is then stored on Filecoin. This creates a decentralized infrastructure for real-time traffic monitoring and management with blockchain-based data integrity.

## 🌟 Features

- **Real-time Traffic Reporting**: Users can report traffic conditions and waiting times at different locations in Jakarta.
- **AI-Powered Insights**: TensorFlow.js models analyze traffic patterns to predict congestion and identify bottlenecks.
- **Blockchain Integration**: All traffic reports are stored on the Dymension blockchain for transparency and immutability.
- **Decentralized Storage**: Critical traffic data is stored on Filecoin for long-term persistence.
- **User Rewards**: Contributors receive tokens for submitting verified traffic reports.
- **Admin Controls**: Traffic management authorities can adjust traffic light timings based on blockchain data.

## 💻 Tech Stack

- **Frontend**: React, TanStack Query, Tailwind CSS, shadcn/ui
- **Backend**: Express.js, TypeScript
- **Blockchain**: Dymension (Ethereum compatible), ethers.js
- **Storage**: Filecoin/IPFS
- **AI/ML**: TensorFlow.js for traffic prediction models
- **Authentication**: Wallet-based authentication (MetaMask)

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- MetaMask or compatible wallet extension

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/macetdym.git
   cd macetdym
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5000`

## 📱 Application Structure

- `/client` - React frontend
  - `/src/components` - UI components
  - `/src/context` - React context providers
  - `/src/lib` - Utility functions
  - `/src/pages` - Application pages
- `/server` - Express backend
  - `routes.ts` - API endpoints
  - `storage.ts` - Data storage implementation
- `/shared` - Shared code between frontend and backend

## 🔄 Core Workflows

### Reporting Traffic

1. Connect your wallet
2. Navigate to the "Report Traffic" page
3. Select a location or use your current GPS coordinates
4. Enter traffic conditions, waiting time, and direction
5. Submit the report, which will be processed via a blockchain transaction

### Managing Traffic Areas

Administrators can:
1. Add new traffic monitoring areas
2. Update congestion status for existing areas
3. Configure traffic light controls
4. View AI-generated insights for traffic optimization

## 🧠 AI Features

MacetDym uses TensorFlow.js to:
- Predict traffic congestion based on historical patterns
- Identify bottlenecks in traffic flow
- Generate optimized traffic light timing recommendations
- Provide route alternatives based on real-time conditions

## 🔐 Security and Privacy

- User location data is anonymized when stored
- Personal information is never stored on-chain
- Optional sharing settings allow users to control data visibility
- All sensitive data is encrypted before storage

## 🌍 Supported Areas

Currently, MacetDym focuses on three major areas in Jakarta:
- Jalan Sudirman (Central Business District)
- Tangerang Toll Road
- Kemang Area

## 🤝 Contributing

We welcome contributions to MacetDym! Please check our [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 📞 Contact

For questions or support, please open an issue on this repository or contact the team at `team@macetdym.io`.