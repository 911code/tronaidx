# **Crowdfunding dApp with Next.js and Tron Blockchain**

## **Introduction**

This is a decentralized crowdfunding application built using Next.js and Tron blockchain. The app allows users to create campaigns and donate to them using TRX.

## **Features**

-   Create campaigns with title, description, and target amount
-   Donate to campaigns using TRX
-   View campaign details and donation history
-   Responsive UI with dark theme

## **Built With**

-   Next.js - React framework for building fast and scalable web applications
-   Tron Blockchain - Blockchain platform for building decentralized applications
-   Solidity - Programming language for writing smart contracts on Tron blockchain
-   Tailwind CSS - CSS framework for styling the app

## **Getting Started**

1.  Clone the repository: `git clone https://github.com/911code/tronaidx.git`
2.  Install dependencies: `npm install`
3.  Start the app: `npm run dev`

## **Smart Contract**

The smart contract is written in Solidity and deployed on the Tron blockchain. The contract allows users to create campaigns and donate to them.

## **Contract Functions**

-   `createCampaign`: Creates a new campaign with title, description, image, target_amount and deadline
-   `donateToCampaign`: Donates to a campaign using TRX
-   `getDonators`: Returns all donators for that campaign
-   `getCampaigns`: Returns all availables campaign(with details)

## **Frontend**

The frontend is built using Next.js and Tailwind CSS. The app uses the Tron blockchain API to interact with the smart contract.

## **Pages**

-   `/`: Home page with campaign list
-   `/campaigns`: Campaign details page
-   `/donate`: Donate page

## **Components**

-   `CampaignCard`: Displays campaign details
-   `DonateForm`: Handles donation form submission

## **API**

-   `getTronWeb`: Obtain the tronweb object injected by tronLink 
-   `setCampaignsContract` : Obtain contract Object
-   `getCampaigns`: Returns list of campaigns
-   `getCampaignDetails`: Returns campaign details and donation history
-   `donate`: Donates to a campaign using TRX

## **Deployment**

The app is deployed on Vercel.

## **License**

This project is licensed under the MIT License.

## **Acknowledgments**

-   Tron Blockchain
-   Next.js
-   Solidity
-   Tailwind CSS
