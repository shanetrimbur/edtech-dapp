# EdTech DApp: Decentralized Educational Platform

Welcome to the **EdTech DApp**, a decentralized platform designed to incentivize learning, teaching, and mentorship using blockchain technology. This platform allows students and mentors to exchange knowledge, earn tokens (EduCoins), and track skill progression using a responsive and interactive interface.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Setup Instructions](#setup-instructions)
- [Available Scripts](#available-scripts)
- [Future Improvements](#future-improvements)
- [License](#license)

## Introduction

The **EdTech DApp** is a decentralized application designed for the education sector. It features interactive course cards, student and mentor rewards, and blockchain-based tokenized incentives for contributing to the learning ecosystem. The platform aims to encourage active participation from both students and mentors by providing EduCoin tokens based on skill development and course completion.

## Features

- **Interactive Course Cards**: Each course is displayed as an interactive card that expands to show details like teacher, course description, available slots, and cost in EduCoins.
- **Student and Mentor Rewards**: Students can earn EduCoins for completing courses, while mentors are rewarded for teaching and improving student performance.
- **Blockchain Integration**: Course enrollments, progress tracking, and rewards are managed via smart contracts on the blockchain.
- **Token Balance Check**: Users can check their EduCoin balance directly from the interface.
- **Progress Tracker**: A visual progress bar that tracks the student's progress in each course.
- **Star Rating System**: Allows students to rate courses after completion.

## Technology Stack

- **Frontend**: React.js
- **Blockchain**: Ethereum (smart contracts) with Ganache for local development
- **Smart Contracts**: Solidity (EduToken and EduReward contracts)
- **Web3**: Web3.js for blockchain interaction
- **UI**: Responsive design with CSS and SVG-based graphics

## Setup Instructions

### Prerequisites
- Node.js and npm
- Ganache for local blockchain testing
- MetaMask browser extension for managing Ethereum wallets

### Installation Steps

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/edtech-dapp.git
    cd edtech-dapp/frontend
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

3. **Run the Application**:

    Start the React app locally:

    ```bash
    npm start
    ```

4. **Run Ganache**:

    Start Ganache on your local machine to simulate the blockchain:

    ```bash
    ganache-cli
    ```

5. **Deploy Smart Contracts**:

    Open the project root directory (assuming you have Truffle installed) and deploy the smart contracts:

    ```bash
    truffle migrate --network development
    ```

6. **Connect MetaMask**:

    - Open MetaMask in your browser.
    - Connect to the local Ethereum network (e.g., Ganache's default network).
    - Import an account using the private key from Ganache.

7. **Interact with the DApp**:

    - Use the DApp interface to explore available courses.
    - Enroll in a course and interact with the blockchain-based rewards system.

## Available Scripts

In the project directory, you can run the following commands:

### `npm start`
Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Launches the test runner in the interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder. It bundles React in production mode and optimizes the build for best performance.

### `truffle migrate`
Deploys the smart contracts to the specified blockchain network.

## Future Improvements

- **Tokenized Marketplace**: Add a marketplace where users can trade EduCoins for learning resources, courses, or mentorship sessions.
- **Advanced Analytics**: Provide students and mentors with advanced analytics and visualizations for tracking progress and token earnings.
- **Decentralized Credentialing**: Issue blockchain-based certificates for course completion and skill mastery.
- **Mobile App Version**: Create a fully optimized mobile app version of the DApp.
- **Cross-Network Deployment**: Deploy on Ethereum testnets (Rinkeby, Goerli) and mainnet.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contributors

- **Shane Trimbur** - Developer

