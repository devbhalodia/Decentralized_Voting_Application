# Decentralized_Voting_Application
A secure and transparent voting platform leveraging Ethereum blockchain. Features include smart contracts for tamper-proof voting, a React.js-based frontend, and integration with Web3.js for blockchain interaction.

# Project Features
Voter authentication and registration.
Transparent and tamper-proof voting using blockchain.
Integration with Metamask for wallet and transaction management.
Deployed and tested in a simulated environment using Ganache.

# Technologies Used
Blockchain: Ethereum, Solidity, Ganache
Frontend: React.js, Web3.js
Backend: Node.js
Wallet Integration: Metamask

# Setup Instructions
1. Clone the Repository:
Download or clone this repository to your local machine.
2. Install Dependencies:
Extract the node_modules_part1.zip and node_modules_part2.zip.
Combine the extracted contents into a single node_modules folder and place it in the project directory.
3. Start Ganache:
Install Ganache and start a local blockchain instance.
4. Deploy Smart Contracts:
Navigate to the project directory and run the following commands:
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
5. Run the Application:
Start the development server:
npm start
Open the application in your browser at http://localhost:3000.
6. Connect Metamask:
Add your Ganache network to Metamask.
Import the accounts from Ganache to Metamask for testing.

# Files and Structure
Project Code: Contains the main application files.
Node Modules (Split):
node_modules_part1.zip
node_modules_part2.zip
Extract these files and combine them to form the node_modules directory.

# Important Notes
Ensure that both node_modules_part1.zip and node_modules_part2.zip are downloaded and combined correctly.
