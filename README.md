# Telegram Bot for Jur Currency Distribution on the TON Network

## Overview
This Telegram bot will facilitate the distribution of 200 million Jur currency (JOR) through the TON network. The bot allows users to link their wallets, receive JOR, participate in mining, and transfer tokens. Additional features such as mining speed-ups and support options are also included.

---

## Features and Flow

### 1. User Interaction and Wallet Linking
- **Welcome Screen**: Users interact with the bot for the first time by clicking the **Start** button.
- **Wallet Linking**: Users will be prompted to link their TON wallet by sending 0.5 TON to the project's wallet address. Once the wallet is linked, they will automatically receive 1000 JOR as a reward.

### 2. Mining Mechanism
- **Automatic Mining**: Once the wallet is linked, JOR will be mined every 24 hours, and the balance will be updated automatically.
- **Balance Display**: Users can check their current JOR balance at any time by clicking a button or typing a command. The mined JOR will be displayed along with their total balance.
- **Mining Speed-Up**: Users will have the option to purchase "Mining Cards" or other virtual items to speed up the mining process.

### 3. Transfer JOR
- Users can transfer JOR tokens once they reach a defined minimum balance, which will be set during the development process. This transfer will be facilitated by the bot, directly linked to the smart contract on the TON network.

### 4. Support and Inquiry
- A dedicated menu where users can ask questions or get support. The bot will provide answers to common inquiries or connect users to a support team.

### 5. News and Updates
- The bot will provide regular updates about JOR, including announcements about new features, exchange listings, or important project developments. Users will be able to subscribe to this news feed through the bot.

### 6. Smart Contract Execution
- The bot will interact with the smart contract deployed on the TON network, executing predefined actions like token transfers, mining, and wallet linking.

---

## Bot Flow

### 1. Main Menu
- **Options**:
  - Link Wallet
  - Check Balance
  - Mining Cards
  - Transfer JOR
  - Support
  - News/Updates

### 2. Wallet Link Process
- Step 1: Prompt the user to link their wallet.
- Step 2: User sends 0.5 TON to the project’s wallet.
- Step 3: The bot verifies the transaction and rewards the user with 1000 JOR.

### 3. Balance and Mining
- User types `/balance` or selects "Check Balance" to view their total JOR and their mined tokens.
- Every 24 hours, mining occurs automatically, and the bot updates the user’s balance.

### 4. Mining Cards Purchase
- The bot will allow users to purchase mining speed-up cards via a simple interaction:
  - Users click "Mining Cards" and select the type of card they want to buy.
  - The bot processes the payment and activates the card, speeding up the user's mining process.

### 5. Support and Help
- Users can select the "Support" option or type `/support` to access support. The bot will provide a list of frequently asked questions and common issues or redirect the user to contact support directly via a provided link.

### 6. News and Updates
- A section where users can receive updates on the JOR currency and the project's development. Users can subscribe or unsubscribe from this feature.

---

## Technical Specifications

### 1. Telegram Bot Framework
- The bot will be built using the Telegram Bot API, allowing smooth interaction with users and the ability to send/receive messages.

### 2. TON Blockchain Integration
- The bot will be integrated with the TON network, enabling users to link wallets, send tokens, and interact with the smart contract.

### 3. Database
- A database will store user wallet information, mining progress, and JOR balances.

### 4. Smart Contract
- The bot will interact with the smart contract deployed on the TON network, ensuring secure transactions and proper management of token distribution.

---

## Development Timeline
- The estimated time to develop the Telegram bot is **20–30 days**. This includes design, coding, integration with the TON network, and testing.

---

## Cost Estimate
- The total cost for the development of the Telegram bot is estimated to be between 850$ and 1000$, depending on additional feature requirements and testing phases.

---

## Next Steps
- Once this document is approved, we can proceed with drafting the smart contract and setting up the necessary infrastructure for the bot development.
