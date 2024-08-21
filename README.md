<h1 align="center">
  <img width='450px'src="https://www.kassandra.finance/_next/static/media/kassandra-header.613d13f9.svg" align="center"/>
</h1>

Kassandra is an decentralized autonomous organization of decentralized finance that governs a protocol that allows the creation and management of tokenized crypto portfolios, bringing a new class of products to managers and investors.

<br />

## 🚀 Technology

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
  This project requires certain environment variables to be set up in order to run properly. You can create a .env file in the root of the project and add the following variables:
  
  ```.env
  
# Example .env file

# Database connection string
DATABASE_URL=postgres://user:password@localhost:5432/mydatabase

NEXT_PUBLIC_MASTER=1
NEXT_PUBLIC_BACKEND_KASSANDRA=https://backend.kassandra.finance/

NEXT_PUBLIC_NODE_ENV=public
IRON_SESSION_PASSWORD=

NEXT_PUBLIC_WALLETCONNECT=
NEXT_PUBLIC_COINGECKO=
  ```

## Installation  

Follow the steps below to set up the Next.js application with Docker:  

1. **Clone the repository:**  

   ```bash  
   git clone https://github.com/KassandraFinance/kassandra-application.git
   
   cd kassandra-application

   # Installing the dependencies
   $ yarn
    
   # Running application
   $ yarn dev

