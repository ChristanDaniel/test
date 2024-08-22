<h1 align="center">
  <img width='450px'src="https://www.kassandra.finance/_next/static/media/kassandra-header.613d13f9.svg" align="center"/>
</h1>

Kassandra is an decentralized autonomous organization of decentralized finance that governs a protocol that allows the creation and management of tokenized crypto portfolios, bringing a new class of products to managers and investors.

<br />

## Technology

This project was developed with the following technologies:
- [React](https://reactjs.org) / [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled-Components](https://styled-components.com/)
- [Ethers](https://docs.ethers.org/v6/)
- [TanStack Query / React Query](https://tanstack.com/query/latest/docs/framework/react/overview)
- [Big.js](https://mikemcl.github.io/big.js/)

<br />

## Prerequisites  
Before you begin, ensure you have the following software installed:  

- [Node.js](https://nodejs.org/en/docs/) >=18.x.x <=20.x.x 
- [Docker](https://docs.docker.com/)

<br />

## Environment Variables
This project requires certain environment variables to be set up in order to function properly. You can create a `.env` file in the root of the project and add the following variables:

```env
# Example .env file

NEXT_PUBLIC_MASTER=1
NEXT_PUBLIC_BACKEND_KASSANDRA=https://backend.kassandra.finance/
NEXT_PUBLIC_NODE_ENV=public

# You must provide one of the following CoinGecko API keys:
COINGECKO_API_KEY= # Free CoinGecko API key with limited access. You can obtain it by creating a free account. Learn more at https://docs.coingecko.com/v3.0.1/reference/introduction
COINGECKO_PRO_API_KEY= # CoinGecko PRO API key. Learn more at https://docs.coingecko.com/reference/introduction

# The variables below are optional.
DATABASE_URL= # Optional: Used to connect to the database (only used for user profiles).
IRON_SESSION_PASSWORD= # Optional: Used to encrypt sessions (only used for user profiles).
NEXT_PUBLIC_WALLETCONNECT= # Optional: Project ID for WalletConnect integration. Learn more at https://cloud.walletconnect.com
NEXT_PUBLIC_MORALIS_KEY= # Optional: Used to fetch the user's NFT list in their profile. Learn more at https://docs.moralis.io/web3-data-api/aptos/reference/authentication
```

## Installation  

Follow the steps below to set up the Next.js application with Docker:  

1. **Clone the repository:**  

   ```bash  
   $ git clone https://github.com/KassandraFinance/kassandra-application.git
   
   cd kassandra-application

   # Installing the dependencies
   $ yarn
    
   # Running application
   $ yarn dev

