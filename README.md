<div align="center">

# Solana App Kit

### Open-Source React Native Scaffold for Building iOS and Android Crypto Mobile Apps with Solana Protocols.

<p> From AI to Social, Launchpads to Wallets, and Trading — build mobile apps in under 15 minutes. </p>

![Solana App Kit - Cover](https://github.com/user-attachments/assets/202830af-1638-4fa1-b40f-7faac03a1cef)


[![Downloads](https://img.shields.io/github/downloads/SendArcade/solana-app-kit/total?label=Downloads&color=brightgreen&style=for-the-badge)](https://github.com/SendArcade/solana-app-kit/releases)
[![Forks](https://img.shields.io/github/forks/SendArcade/solana-app-kit?label=Forks&color=blue&style=for-the-badge)](https://github.com/SendArcade/solana-app-kit/network/members)
[![License](https://img.shields.io/github/license/SendArcade/solana-app-kit?label=License&color=brightgreen&style=for-the-badge)](https://github.com/SendArcade/solana-app-kit/blob/main/LICENSE)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/sendarcadefun)

<p> Anyone — whether a seasoned React Native developer or a Solana developer — can build mobile apps faster with 10+ protocol integrations. </div>

## Key Protocol Integrations

1. **Swaps:**  
   In-App trading via [Jupiter](https://jup.ag/) for the best prices across all DEXs, and native [Pump AMM](https://swap.pump.fun/)

2. **Launchpads:**  
   The three biggest Solana launchpads with configurable bonding curves – [Pump.fun](https://pump.fun/), [Raydium](https://raydium.io/launchpad/), and [Meteora](https://app.meteora.ag/) – along with [Token Mill](https://tokenmill.xyz/)

3. **Embedded Wallets:**  
   Top wallets like [Privy](https://www.privy.io/), [Turnkey](https://turnkey.com/), and [Dynamic](https://www.dynamic.xyz/), along with Mobile Wallet Adapter support by [Solana Mobile](https://solanamobile.com/) for external wallet connections.

4. **Token Data & Prices:**  
   Live prices and token info from [Coingecko](https://www.coingecko.com/), [Birdeye](https://birdeye.so/), and [Rugcheck](https://rugcheck.xyz/)

5. **NFTs:**  
   NFT minting via [Metaplex](https://www.metaplex.com/) and trading via [Tensor](https://www.tensor.trade/)

6. **AI Integration:**  
   [SendAI](https://sendai.fun/) for AI chat integration to take Solana actions

7. **On/Off-Ramps:**  
   Buy/sell crypto using cards or Apple Pay with [MoonPay](https://www.moonpay.com/) and [Mercuryo](https://mercuryo.io/)

8. **Miscellaneous Tools:**  
   [Jito Bundles](https://www.jito.network/) and [Helius](https://www.helius.dev/) for transaction landing

---

## 📋 Detailed Table of Contents

- [📱 App Features](#-app-features)
- [📚 Documentation](#-documentation)
- [📦 Core Installation](#-core-installation)
- [🛠️ Tech Stack](#️-tech-stack)
- [✅ Prerequisites](#-prerequisites)
- [🚀 Quick Start](#-quick-start)
- [⌨️ Hotkeys](#️-hotkeys)
- [🧪 Development Mode Guide](#-development-mode-guide)
- [🏁 Getting Started](#-getting-started)
- [📂 Project Structure](#-project-structure)
- [🧩 Modules](#-modules)
- [📊 Examples](#-examples)
- [🚢 Production Deployment](#-production-deployment)
- [📚 Dependencies](#-dependencies)
- [🤝 Contributing](#-contributing)
- [👥 Contributors](#-contributors)
- [📄 License](#-license)
- [❓ Troubleshooting](#-troubleshooting)
- [🔒 Security](#-security)
- [🌐 Community](#-community)

---

## 📱 App Features

| Feature | Description |
|---------|-------------|
| 👛 **Wallet Integration** | • Multiple wallet connection methods<br>• Embedded wallet support via Privy, Dynamic, and Turnkey<br>• External wallet connections via Solana Mobile MWA<br>• Transaction signing and management<br>
| 👥 **Social Features** | • User profiles and following system<br>• Social feed with posts and interactions<br>• Community engagement features<br>• NFT display and management<br>• IPFS storage for metadata |
| 🎨 **UI/UX** | • Modern, responsive design<br>• Tab-based navigation<br>• Interactive charts and visualizations<br>• Elegant loading states and error handling<br>• Platform-specific optimizations |
| 🖥️ **Backend Features** | • RESTful API for token operations<br>• Social data storage and retrieval<br>• Token market creation and management<br>• Token swapping via Jupiter and PumpSwap<br>• Token launching via different launchpads like Pump, Raydium, and Meteora <br>• Image upload and storage |

---

## 📚 Documentation

You can view the full documentation of the kit at: [https://docs.1doma.in/docs/introduction](https://docs.1doma.in/docs/introduction)

---

## 📦 Core Installation

```sh
npx start-solana-app
```

---

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="https://d33wubrfki0l68.cloudfront.net/554c3b0e09cf167f0281fda839a5433f2040b349/ecfc9/img/header_logo.svg" width="60" height="60" alt="React Native" /><br /><b>React Native</b></td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/expoio/expoio-icon.svg" width="60" height="60" alt="Expo" /><br /><b>Expo</b></td>
      <td align="center"><img src="https://raw.githubusercontent.com/solana-labs/token-list/main/assets/mainnet/So11111111111111111111111111111111111111112/logo.png" width="60" height="60" alt="Solana" /><br /><b>Solana</b></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/81824329?s=200&v=4" width="60" height="60" alt="Privy" /><br /><b>Privy</b></td>
      <td align="center"><img src="https://cdn.worldvectorlogo.com/logos/redux.svg" width="60" height="60" alt="Redux" /><br /><b>Redux</b></td>
    </tr>
    <tr>
      <td align="center"><img src="https://reactnavigation.org/img/spiro.svg" width="60" height="60" alt="React Navigation" /><br /><b>React Nav</b></td>
      <td align="center"><img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" width="60" height="60" alt="TypeScript" /><br /><b>TypeScript</b></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/104513330?s=200&v=4" width="60" height="60" alt="Turnkey" /><br /><b>Turnkey</b></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/96269716?s=200&v=4" width="60" height="60" alt="Dynamic" /><br /><b>Dynamic</b></td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/expoio/expoio-icon.svg" width="60" height="60" alt="Image Picker" /><br /><b>Image Picker</b></td>
    </tr>
    <tr>
      <td align="center"><img src="https://expressjs.com/images/favicon.png" width="60" height="60" alt="Express" style="background-color: white; border-radius: 10px; padding: 5px;" /><br /><b>Express</b></td>
      <td align="center"><img src="https://cdn.worldvectorlogo.com/logos/postgresql.svg" width="60" height="60" alt="PostgreSQL" /><br /><b>PostgreSQL</b></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/82165905?s=48&v=4" width="60" height="60" alt="TokenMill" /><br /><b>TokenMill</b></td>
      <td align="center"><img src="https://avatars.githubusercontent.com/u/43088506?s=200&v=4" width="60" height="60" alt="Pinata" /><br /><b>Pinata</b></td>
      <td align="center"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" width="60" height="60" alt="Google Cloud" /><br /><b>GCP Storage</b></td>
    </tr>
  </table>
</div>

---

## ✅ Prerequisites

- Node.js >= 18
- pnpm or yarn or npm
- iOS: XCode and CocoaPods
- Android: Android Studio and Android SDK
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- PostgreSQL database (for the server)

---

## 🚀 Quick Start

1. Clone the repository:

   ```sh
   git clone https://github.com/SendArcade/solana-app-kit.git
   cd solana-app-kit
   ```

2. Install dependencies:

   ```sh
   pnpm install
   ```

3. Run on a specific platform:

   ```sh
   # For iOS
   npx expo run:ios

   # For Android
   npx expo run:android
   ```

To run in development mode with cache clearing:

```sh
pnpm start --dev --clear
```

---

## ⌨️ Hotkeys

When running the Expo development server:

| Key | Action |
|-----|--------|
| `i` | Open on iOS simulator |
| `a` | Open on Android emulator |
| `w` | Open in web browser |
| `r` | Reload the app |
| `m` | Toggle the menu |
| `d` | Open developer tools |

---

## 🧪 Development Mode Guide

For details on running the app in development mode, including environment variable handling and troubleshooting, please refer to the [Development Mode Guide](docs/DEV_MODE.md).

---

## 🏁 Getting Started

This project consists of two main parts:

1. React Native mobile application (in the root directory)
2. Backend server (in the `server` directory)

### Mobile App Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/SendArcade/solana-app-kit.git
   cd solana-app-kit
   ```

2. Install dependencies:

   ```sh
   pnpm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory with the necessary variables as shown in the example below:

   ```
   # Blockchain
   CLUSTER=mainnet-beta

   # Authentication
   PRIVY_APP_ID=your_privy_app_id
   PRIVY_CLIENT_ID=your_privy_client_id
   DYNAMIC_ENVIRONMENT_ID=your_dynamic_env_id

   # Turnkey wallet
   TURNKEY_BASE_URL=https://api.turnkey.com
   TURNKEY_RP_ID=host.exp.exponent
   TURNKEY_RP_NAME=send-fi
   TURNKEY_ORGANIZATION_ID=your_turnkey_organization_id
   TURNKEY_API_PUBLIC_KEY=your_turnkey_public_key
   TURNKEY_API_PRIVATE_KEY=your_turnkey_private_key

   # APIs
   HELIUS_API_KEY=your_helius_api_key
   HELIUS_RPC_CLUSTER=mainnet
   HELIUS_STAKED_URL=your_helius_staked_url
   HELIUS_STAKED_API_KEY=your_helius_staked_api_key
   SERVER_URL=your_server_url
   TENSOR_API_KEY=your_tensor_api_key
   PARA_API_KEY=your_para_api_key
   COINGECKO_API_KEY=your_coingecko_api_key
   BIRDEYE_API_KEY=your_birdeye_api_key
   COIN_MARKE_CAPAPI_KEY=your_coinmarketcap_api_key
   ```

### Server Installation

1. Navigate to the server directory:

   ```sh
   cd server
   ```

2. Install server dependencies:

   ```sh
   pnpm install
   ```

3. Set up server environment variables:

   ```sh
   cp .env.example .env
   ```

   Required server environment variables:

   ```
   WALLET_PRIVATE_KEY=your_wallet_private_key
   RPC_URL=your_helius_rpc_url
   TOKEN_MILL_PROGRAMID=your_token_mill_program_id
   TOKEN_MILL_CONFIG_PDA=your_token_mill_config_pda
   SWAP_AUTHORITY_KEY=your_swap_authority_key

   # Pinata for IPFS
   PINATA_JWT=your_pinata_jwt
   PINATA_GATEWAY=your_pinata_gateway
   PINATA_SECRET=your_pinata_secret
   PINATA_API_KEY=your_pinata_api_key

   # Database and Storage
   DATABASE_URL=your_postgresql_url
   GCS_BUCKET_NAME=your_gcs_bucket_name
   SERVICE_ACCOUNT_EMAIL=your_service_account_email

   # Turnkey
   TURNKEY_API_URL=https://api.turnkey.com
   TURNKEY_ORGANIZATION_ID=your_turnkey_organization_id
   TURNKEY_API_PUBLIC_KEY=your_turnkey_api_public_key
   TURNKEY_API_PRIVATE_KEY=your_turnkey_api_private_key
   ```

4. Start the development server:
   ```sh
   pnpm dev
   # or
   yarn dev
   ```

For more details about the server, see the [Server README](server/README.md).

### Environment Variables for EAS Builds

The project is configured to use the `.env.local` file for both local development and EAS builds. When building with EAS, the environment file is automatically loaded:

```sh
# Example for a development build on Android
npx eas build --profile development --platform android
```

The configuration in `eas.json` specifies the `.env.local` file for each build profile. The babel configuration dynamically loads this file during the build process.

### Running the Mobile App

#### Start Metro Bundler

```sh
pnpm start
# or
yarn start
# or
npm start
```

#### iOS

For iOS, you need to install CocoaPods dependencies first:

```sh
# Install Ruby bundler (first time only)
bundle install

# Install CocoaPods dependencies
bundle exec pod install
```

Then run the app:

```sh
pnpm ios
# or
yarn ios
# or
npm run ios
```

#### Android

```sh
pnpm android
# or
yarn android
# or
npm run android
```

---

## 📂 Project Structure

```
solana-app-kit/
├── src/                # Mobile app source code
│   ├── assets/         # Images, icons, and other static assets
│   ├── config/         # Configuration files and settings
│   ├── context/        # React context providers
│   ├── core/           # Core application components
│   │   ├── devMode/    # Development mode utilities
│   │   ├── profile/    # User profile related components
│   │   ├── shared-ui/   # Common UI components
│   │   └── thread/     # Thread-related components
│   ├── modules/        # Feature modules (core functionality)
│   │   ├── dataModule/ # Data management module
│   │   ├── mercuro/    # Advanced financial utilities
│   │   ├── nft/        # NFT display and management
│   │   ├── pumpFun/    # Pump.fun integration
│   │   ├── tokenMill/  # Token creation and management
│   │   └── walletProviders/ # Wallet connection adapters
│   ├── screens/        # App screens and UI flows
│   ├── services/       # API integrations and business logic
│   ├── shared/         # Shared utilities and components
│   │   ├── hooks/      # Custom React hooks
│   │   ├── mocks/      # Mock data for testing
│   │   ├── navigation/ # Navigation configuration
│   │   ├── state/      # Redux store and slices
│   │   ├── types/      # TypeScript type definitions
│   │   └── utils/      # Utility functions and helpers
├── server/             # Backend server code
│   ├── src/            # Server source code
│   │   ├── controllers/ # Controller functions
│   │   ├── db/         # Database configuration
│   │   ├── routes/     # API endpoints
│   │   ├── service/    # Service implementations
│   │   ├── types/      # TypeScript types
│   │   └── utils/      # Utility functions
│   ├── .env.example    # Example environment variables
│   └── README.md       # Server documentation
├── App.tsx             # Main application component
├── index.js            # Entry point
├── app.config.js       # Expo configuration
├── app.json            # App configuration
├── babel.config.js     # Babel configuration
├── metro.config.js     # Metro bundler configuration
├── tsconfig.json       # TypeScript configuration
├── docs/               # Documentation files
├── CONTRIBUTING.md     # Contribution guidelines
├── LICENSE             # License information
└── package.json        # Dependencies and scripts
```

---

## 🧩 Modules

The Solana App Kit provides several modular features that can be used independently:

| Module | Capabilities |
|--------|-------------|
| 🔐 **walletProviders** | • Multiple wallet connection methods (Privy, Dynamic, Mobile Wallet Adapter)<br>• Standardized wallet interface<br>• Transaction handling across providers<br>• Support for embedded wallets, social login, and external wallets |
| 🪙 **tokenMill** | • Token creation with configurable parameters<br>• Bonding curve configuration for token pricing<br>• Token swapping (buy/sell) functionality<br>• Staking tokens for rewards<br>• Creating and releasing vesting plans<br>• Fund management for users and markets |
| 📊 **onChainData** | • Fetching on-chain data with optimized RPC calls<br>• Token balance tracking<br>• Transaction history display<br>• Real-time data synchronization |
| 🖼️ **nft** | • NFT display, management, and trading<br>• Collection viewing with floor prices<br>• Compressed NFT support<br>• Integration with threads and posts |
| 💱 **pumpSwap** | • Token swapping using PumpSwap SDK<br>• Liquidity pool creation with custom token pairs<br>• Liquidity management (add and remove liquidity)<br>• Pool creation with custom parameters<br>• Real-time quotes and price impact estimates<br>• Transaction status monitoring |
| 🚀 **pumpFun** | • Integration with the Pump.fun ecosystem<br>• Meme token creation and management<br>• Community engagement tools |
| 💸 **Moonpay** | • Advanced financial transaction utilities<br>• Custom financial operations |

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

For detailed guidelines on how to contribute to this project, see our [Contributing Guide](CONTRIBUTING.md).

## 👥 Contributors

<div align="center">
  <a href="https://github.com/SendArcade/solana-app-kit/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=SendArcade/solana-app-kit" alt="Contributors" />
  </a>
</div>

---

## 🔒 Security

This toolkit handles transaction generation, signing and sending, using provided wallets. Always ensure you're using it in a secure environment and never share your private keys.

---

## ❓ Troubleshooting

Common issues and their solutions:

| Issue | Solution |
|-------|----------|
| **Expo build errors** | Clear your cache with `expo start --clear` |
| **Wallet connection issues** | Ensure you're using the correct provider and have properly configured environment variables |
| **iOS simulator issues** | Try resetting the simulator or running `pod install` in the iOS directory |

---

## 🌐 Community

Join our community to get help, share your projects, and contribute:

[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/sendarcade)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/sendarcadefun)

---

## 📄 License

This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details.

---

## Birdeye API Integration

The application now uses Birdeye APIs for token listing and searching, providing users with accurate market data:

### Features

- Token listing sorted by market cap (high to low)
- Debounced token search functionality
- Real-time price and 24h price change data
- Pagination support for token lists
- Zero fallbacks or hardcoded token data

### Setup

To use the Birdeye API, you need to add your API key to the environment variables:

```
BIRDEYE_API_KEY=your_api_key_here
```

### API Endpoints Used

- Token List: `https://public-api.birdeye.so/defi/v3/token/list`
- Token Search: `https://public-api.birdeye.so/defi/v3/search`
- Token Metadata: `https://public-api.birdeye.so/defi/v3/token/meta-data/single`
- Token Market Data: `https://public-api.birdeye.so/defi/v3/token/market-data`

### Hooks

Custom hooks for using the Birdeye API:

- `useTokenSearch`: Provides debounced search functionality for tokens

---

<div align="center">

Built with ❤️ for the Solana ecosystem by SendAI and Send Arcade.

</div>
