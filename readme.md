# MCW3 - Make Change With Web3

## Introduction
MCW3's aim is to bridge the gap between on-chain initiatives and non-crypto users. The project's objective is to create a platform that aggregates public goods projects and allows verified initiatives to receive support without the need for crypto-specific solutions. By providing an intuitive user interface, MCW3 preserves the benefits of on-chain technology while making it accessible to a broader audience.

## Features
- Aggregates public goods projects for easy access and support.
- Allows users to create an account via Twitter and donate to projects.
- Supports bank transfer as a payment method.
- Provides an intuitive user interface for project selection and transaction confirmation.

## Technology Stack
The MCW3 project was built using the following technologies:

- **Frontend**: Next.js, Typescript
- **Backend**: Kotlin
- **Authentication Provider**: SISMO
- **Custodian Wallet Layer**: DFNS
- **Bank Transfer Integration**: Monerium
- **Smart Contract**: Mantle chain, Solidity

## Installation
To run the MCW3 project locally, follow these steps:

1. Clone the GitHub repository: [GitHub Repo] (https://github.com/mkww3/mcw3-ui)
2. Install the necessary dependencies for the frontend and backend.
3. Set up and configure the required services, including SISMO, DFNS, and Monerium.
4. Deploy the smart contract on the Mantle chain and update the contract address in the code.
5. Run the frontend and backend servers.
6. Access the MAKE CHANG3 website on your local machine.

## Challenges Faced
During the development of the project, we encountered several challenges, including:

- Incomplete or non-user-friendly project documentation, which required reverse engineering.
- Interacting with smart contracts at a low level due to the use of a custodian, making it difficult to utilize popular libraries.
- Errors in the tools and dependencies used, causing additional debugging and troubleshooting.

## Achievements
We are proud to have integrated solutions that eliminate the need for users to connect to our portal with their own crypto wallet, enhancing user experience and accessibility.

## Learnings
Throughout the project, our team member took the initiative to learn Kotlin from scratch and developed several endpoints, leading to a higher level of security for users' assets through the custodian wallet system. This experience allowed us to expand our skills and knowledge in developing secure solutions.

## Future Plans
Moving forward, our main objective is to integrate our solution with existing public goods projects and assess the market response. To enhance the platform, we plan to seek grants to expand the dashboard and crowdfunding modules, integrate with more chains and identity providers, and improve overall functionality.

Additionally, we are committed to building a strong community and raising awareness about public goods and regenerative finance to promote sustainable development initiatives.

## Try it Out
- GitHub Repository: https://github.com/mkww3/
- Figma Design: https://www.figma.com/file/WL6qia6QFLaudZaX0SbeMq/MakeChang3?type=design&node-id=0-1
- Crowdfunding Factory: 0xDE1b88a55E8A062c6DecA5D1f910C04315962328
- Example Crowdfunding Addresses:
  - 0x25bE87FCC7aD0DaE1CBB38558e5b20C88447cB10
  - 0x60dc73d633DE97df77DB128Ebe4Df06C947C4f0e
  - 0x56078208730b5cf36c083d888Cd2c58181504d8d
