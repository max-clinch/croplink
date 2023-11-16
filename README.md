# CropLink

**An AgriTech Dapp with weather-savvy smart contracts for bountiful selling**

CropLink is an AgriTech decentralized application (Dapp) that transforms the agricultural selling landscape. It establishes a decentralized platform connecting farmers with registered buyers. The platform utilizes smart contracts and Chainlink oracles to facilitate transparent transactions and manage risks related to unpredictable weather conditions.

## Features

- **Listing Produce:**
  Farmers can easily list and add their produce, specifying details such as name, quantity, and price.

- **Produce Management:**
  Farmers have the capability to view and manage their list of produce.

- **Fair Transactions:**
  Smart contracts, powered by Chainlink oracles, ensure fair and transparent transactions.

- **Weather Monitoring:**
  CropLink monitors weather conditions through Chainlink Automation. In adverse conditions, the smart contracts activate automatically.

- **Onboarding Simplified:**
  Farmers only need a Metamask account to get started. Currently operating on the Sepolia Testnet.

## Smart Contract Integration

CropLink employs smart contracts integrated with Chainlink oracles to monitor and respond to real-time weather conditions. This ensures that farmers can sell their crops at fair prices, even in the face of unpredictable weather events.

## External Adapter

To enhance functionality, CropLink uses AWS Lambda, API Gateway, and the USDA API to host an external adapter. This adapter allows the hybrid smart contract to connect to a Chainlink Oracle and adjust market prices based on real-time global demand for farm commodities/crops.

## Getting Started

1. **Prerequisites:**
   - Install Metamask for onboarding.
   - Connect to the Sepolia Testnet.

2. **Listing Produce:**
   - Use the Dapp to easily list and manage your produce.

3. **Fair Transactions:**
   - Experience transparent transactions with the power of smart contracts and Chainlink oracles.

## Weather Monitoring

Chainlink Automation constantly monitors weather conditions, ensuring smart contracts respond to adverse events automatically.

## External Adapter Integration

CropLink integrates with AWS Lambda, API Gateway, and the USDA API to adjust market prices based on real-time global demand.

## Contributors


## License


---

Feel free to customize the content and structure further based on your project's specific details and requirements.



This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
