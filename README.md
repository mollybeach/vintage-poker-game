# Vintage Poker Game 🎲♠️🃏

## Description
🎲 Vintage Poker Game ♠️🃏 is an immersive online poker experience that combines classic gameplay with modern technology. Built on a blockchain framework, it offers secure wallet integration, real-time gameplay, and a user-friendly interface. Players can enjoy various poker games while managing their digital assets seamlessly. 💻💰

## Features
- **Wallet Integration**: Users can create wallets, deposit and withdraw funds, and view transaction history.
- **In-Game Currency Management**: Players can use their wallet balance to place bets and enter tournaments.
- **Real-Time Gameplay**: All transactions are processed instantly during gameplay.
- **User-Friendly Interface**: Intuitive design for easy navigation between poker tables and wallet management.
- **Security Measures**: Enhanced security protocols to protect user data and transactions.
- **Compliance**: Adheres to online gambling regulations, including KYC/AML policies.
- **Testing Framework**: Comprehensive testing for all functionalities, including unit and integration tests.

## Project Context


## Important Notes
- This snapshot shows only the cmrpoker directory and its contents.
- Files over 2000 lines are truncated.
- Binary files and dependencies are excluded.

## Project Technologies
### Main Dependencies
- **bcryptjs**: ^2.4.3
- **cookie-parser**: ^1.4.5
- **cors**: ^2.8.5
- **dotenv**: ^8.2.0
- **express**: ^4.17.1
- **mongoose**: ^5.10.2
- **socket.io**: ^2.3.0
- **pokersolver**: ^2.1.4
- **nodemailer**: ^6.4.11

### Dev Dependencies
- **concurrently**: ^5.3.0
- **nodemon**: ^2.0.4

## Installation Instructions

### Install Server Dependencies

```bash
npm install
```

### Install Client Dependencies

```bash
cd client
npm install
```

### Run Both Express & React from Root Project Directory

```bash
npm run dev
```

### Build for Production

```bash
cd client
npm run build
```

### Test Production Before Deploy

```bash
NODE_ENV=production node server.js
```

## Coding Project Requirements
### Vintage
Prepared for: David Santiago Florez Diaz, Texas, US

### Requirements for Vintage Poker Game
1. **Wallet Integration**
   - Wallet Creation
   - Deposit Funds
   - Withdraw Funds
   - Transaction History

2. **Security Requirements**
   - Use encryption protocols for data transmission.
   - Implement anti-fraud measures.

3. **User Interface Requirements**
   - Design an intuitive user interface.
   - Include wallet balance indicators.

4. **Compliance Requirements**
   - Ensure compliance with online gambling regulations.

5. **Testing Requirements**
   - Conduct thorough testing of all functionalities.

## File Structure
```bash
cmrpoker/
├── client/
│   ├── public/
│   ├── routes/
│   ├── socket/
│   ├── config.js
│   └── server.js
├── package.json
└── README.md
```

## Additional Notes
- Generated using repository-content-printer.
- Node modules and build outputs excluded.
- See config.mjs for the complete ignore list.