# 🗳️ Election - DAPP Tutorial

Build your first decentralized application (Dapp) on the Ethereum blockchain with this detailed tutorial!

**Video Tutorial:** [Watch Here](https://youtu.be/3681ZYbDSSk)  
**2019 Updated Code:** [GitHub Repository](https://github.com/dappuniversity/election/tree/2019_update)

## 📋 Prerequisites

To follow this tutorial, ensure you have the following tools installed:

- **NPM**: [Node.js & NPM](https://nodejs.org) for managing JavaScript packages.
- **Truffle**: [Truffle Suite](https://github.com/trufflesuite/truffle) for Ethereum smart contract development.
- **Ganache**: [Ganache GUI](http://truffleframework.com/ganache/) for a personal Ethereum blockchain to deploy contracts.
- **Metamask**: [Metamask Extension](https://metamask.io/) for managing Ethereum wallets and interacting with the blockchain.

## 🚀 Setup and Execution

1. **Clone the Project**

    ```bash
    git clone https://github.com/dappuniversity/election
    ```

2. **Install Dependencies**

    ```bash
    cd election
    npm install
    ```

3. **Start Ganache**

    - Launch the Ganache GUI client to create a local Ethereum blockchain.

4. **Compile & Deploy the Election Smart Contract**

    ```bash
    truffle migrate --reset
    ```
    - Migrate the smart contract each time you restart Ganache to deploy it on the local blockchain.

5. **Configure Metamask**

    - **Unlock Metamask** and connect it to your local Ethereum blockchain provided by Ganache.
    - **Import** an account from Ganache into Metamask to interact with your contracts.

6. **Run the Front-End Application**

    ```bash
    npm run dev
    ```
    - Open [http://localhost:3000](http://localhost:3000) in your browser to interact with the Dapp.

## 💡 Troubleshooting

If you face any issues, refer to the video tutorial for step-by-step guidance.


