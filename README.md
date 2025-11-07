# Bridge Swap | Cross-Chain Token Bridge DApp

![alt text](https://www.daulathussain.com/wp-content/uploads/2025/11/Build-Deploy-Bridge-Swap-Cross-Chain-Token-Bridge-DApp-Using-Next.js-Thirdweb-Blockchain-DeFi-Project.jpg)

- [Final Source Code](https://www.theblockchaincoders.com/sourceCode/build-and-deploy-bridge-swap-or-cross-chain-token-bridge-dapp-using-next.js-thirdweb-and-blockchain-or-defi-project)

#### Setup Video

- [Final Code Setup video](https://youtu.be/-IlnisTAX-8?si=4tvSxvyRpcrmuJZS)

Build & Deploy Bridge Swap | Cross-Chain Token Bridge DApp Using Next.js, Thirdweb & Blockchain | DeFi Project

In this video, you’ll learn how to build and deploy a fully functional Cross-Chain Token Bridge (Bridge Swap) DeFi DApp using Next.js, Thirdweb, and Blockchain integration. 🌉💻

We’ll go step-by-step through:

- Setting up the project with Next.js
- Integrating Thirdweb SDK for multi-chain support
- Building a Cross-Chain Token Swap UI
- Connecting different blockchain networks
- Deploying your Bridge DApp on the web

Perfect for developers looking to explore DeFi, Web3 interoperability, and cross-chain token transfers.

🔗 Tech Stack: Next.js, Thirdweb, EVM Networks, Solidity, DeFi
💡 Level: Intermediate to Advanced

👉 Watch till the end to learn how to create your own decentralized bridge for seamless token swaps across multiple blockchains!

#DeFi #Web3 #Nextjs #Thirdweb #Blockchain #Crypto #CrossChain #BridgeSwap #DApp #SmartContracts

## Instruction

Kindly follow the following Instructions to run the project in your system and install the necessary requirements

#### Deploying Dapp

```
  WATCH: Hostinger
  Get : Discount 50%
  URL: https://www.hostg.xyz/aff_c?offer_id=6&aff_id=139422
```

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### NodeJs & NPM Version

```
  NodeJs: 20 / LATEST
  NPM: 20
  URL: https://nodejs.org/en/download
  Video: https://youtu.be/PIR0oBVowXU?si=9eNdR29u37F2ujJJ
```

All you need to follow the complete project and follow the instructions which are explained in the tutorial by Daulat

## Final Code Instruction

If you download the final source code then you can follow the following instructions to run the Dapp successfully

#### Install Vs Code Editor

```
  GET: VsCode Editor
  URL: https://code.visualstudio.com/download
```

#### THIRDWEB

```
  OPEN: THIRDWEB
  URL: https://thirdweb.com/login
```

## Important Links

- [Get Pro Blockchain Developer Course](https://www.theblockchaincoders.com/pro-nft-marketplace)
- [Support Creator](https://bit.ly/Support-Creator)
- [All Projects Source Code](https://www.theblockchaincoders.com/SourceCode)

## Authors

- [@theblockchaincoders.com](https://www.theblockchaincoders.com/)
- [@consultancy](https://www.theblockchaincoders.com/consultancy)
- [@youtube](https://www.youtube.com/@daulathussain)

# Bridge Swap - Cross-Chain Token Bridge

A beautiful, production-ready cross-chain bridge swap application built with Next.js 15 and Thirdweb. This application allows users to seamlessly swap and bridge tokens across multiple blockchain networks with a stunning, custom UI design.

## Features

- **Cross-Chain Swapping**: Seamlessly swap tokens across 15+ blockchain networks
- **Beautiful Custom UI**: Completely custom design that doesn't look like default Thirdweb
- **Glass Morphism Design**: Modern, sleek UI with glass morphism effects
- **Responsive**: Fully responsive design that works on all devices
- **Multi-Wallet Support**: Support for MetaMask, Coinbase Wallet, Rainbow, Rabby, and more
- **Real-time Stats**: Display live stats and network information
- **Secure**: Built on audited Thirdweb infrastructure
- **TypeScript**: Fully typed for better developer experience
- **Tailwind CSS**: Utility-first CSS for rapid UI development

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Web3**: Thirdweb SDK v5
- **Blockchain Integration**: Thirdweb Bridge & Swap Widget

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js 18.x or higher
- npm or yarn package manager
- A Thirdweb account and Client ID

## Getting Started

### 1. Clone the repository

\`\`\`bash
git clone <your-repo-url>
cd bridge-swap
\`\`\`

### 2. Install dependencies

\`\`\`bash
npm install --legacy-peer-deps

# or

yarn install
\`\`\`

### 3. Get your Thirdweb Client ID

1. Go to [Thirdweb Dashboard](https://thirdweb.com/dashboard)
2. Create a new project or select an existing one
3. Navigate to Settings > API Keys
4. Copy your Client ID

### 4. Configure environment variables

Create a \`.env.local\` file in the root directory:

\`\`\`env
NEXT_PUBLIC_THIRDWEB_CLIENT_ID=your_thirdweb_client_id_here
\`\`\`

Replace \`your_thirdweb_client_id_here\` with your actual Thirdweb Client ID.

### 5. Run the development server

\`\`\`bash
npm run dev

# or

yarn dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Building for Production

To create a production build:

\`\`\`bash
npm run build
npm run start

# or

yarn build
yarn start
\`\`\`

## Project Structure

\`\`\`
bridge-swap/
├── app/
│ ├── globals.css # Global styles
│ ├── layout.tsx # Root layout with ThirdwebProvider
│ └── page.tsx # Main page component
├── components/
│ ├── Header.tsx # Header with wallet connect
│ ├── SwapWidget.tsx # Custom swap widget wrapper
│ ├── Stats.tsx # Statistics display
│ ├── SupportedNetworks.tsx # Network icons and info
│ ├── Features.tsx # Features section
│ └── Footer.tsx # Footer component
├── lib/
│ └── thirdweb.ts # Thirdweb client configuration
├── public/ # Static assets
├── .env.local # Environment variables (create this)
├── .env.example # Example environment variables
├── next.config.ts # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
├── tsconfig.json # TypeScript configuration
└── package.json # Dependencies and scripts
\`\`\`

## Customization

### Changing Colors

Edit the color palette in [tailwind.config.ts](tailwind.config.ts):

\`\`\`typescript
colors: {
primary: { ... },
accent: { ... },
}
\`\`\`

### Modifying the Swap Widget

The swap widget can be customized in [components/SwapWidget.tsx](components/SwapWidget.tsx). You can change:

- Default tokens
- Theme colors
- Supported chains
- Widget configuration

### Adding More Networks

Edit the networks array in [components/SupportedNetworks.tsx](components/SupportedNetworks.tsx) to add or remove networks.

## Supported Networks

The bridge currently supports:

- Ethereum
- Polygon
- Binance Smart Chain (BSC)
- Avalanche
- Arbitrum
- Optimism
- Base
- Fantom
- And 7+ more networks

## Security

This application uses Thirdweb's audited smart contracts for all bridge and swap operations. The UI is completely custom but leverages Thirdweb's secure infrastructure.

## Performance Optimization

The application includes:

- Server-side rendering (SSR) with Next.js App Router
- Optimized images and assets
- Code splitting and lazy loading
- Minimal bundle size

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Brave

## Troubleshooting

### Build Errors

If you encounter build errors, try:
\`\`\`bash
rm -rf node_modules package-lock.json
npm install --legacy-peer-deps
\`\`\`

### Wallet Connection Issues

Ensure you have:

1. A Web3 wallet extension installed
2. The correct network selected
3. Your Thirdweb Client ID configured correctly
