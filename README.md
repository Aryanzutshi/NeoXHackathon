
# NeoXPay: "Step into the future of Payments with our DEX"

The DEX (Decentralized Exchange) smart contract is designed to facilitate seamless trading of both Ether (Ethereum's native currency) and ERC-20 tokens on the blockchain. It differentiates Ether from tokens using a unique constant (ETHER), represented as address(0), allowing the contract to manage Ether deposits, withdrawals, and balances alongside various tokens. By integrating this structure, users can easily deposit and withdraw Ether through specific functions, ensuring secure and accurate transaction tracking.

The contract also implements a fallback function to prevent accidental Ether transfers, reinforcing security by ensuring that all Ether deposits are correctly logged. Furthermore, users can make and fill trading orders for token swaps, with a built-in fee mechanism that directs a small percentage of each trade to a designated fee account.

In addition to these core functions, the contract emphasizes leveraging blockchain technology to streamline decentralized trading, promoting the ease of use and security that blockchain offers. This smart contract embodies a scalable solution for decentralized finance (DeFi) applications, making blockchain transactions more accessible and efficient for users.


## Features

1) Account Connection:

- Users can easily connect their MetaMask wallet to the dApp, allowing seamless interaction with the Ethereum blockchain. This feature uses the window.ethereum object to request account access and establish a connection.

2) Transaction Signing:

- Once connected, users can sign transactions directly from their MetaMask wallet. This ensures that all operations, such as token transfers or contract interactions, are securely approved by the user, preventing unauthorized actions.

3) Ether and Token Balance Retrieval:

- Users can view their Ether balance or the balance of any ERC-20 token directly within the dApp. This is done using the getBalance function from ethers.js, which queries the blockchain to provide up-to-date information on the user's holdings.

4) Smart Contract Interaction:

- Users can interact with deployed smart contracts through their MetaMask account. This feature allows users to perform contract functions such as depositing or withdrawing tokens, executing trades, or checking the status of a transaction, all without leaving the dApp.


## Demo

Insert gif or link to demo


![Logo]()


## Run Locally

Clone the project

```bash
  git clone https://github.com/Aryanzutshi/NeoXHackathon
```

Go to the project directory

```bash
  cd app
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```


## Authors

#### Aryan
- [X](https://x.com/aryanzutshi12)
- [Linkedin](https://www.linkedin.com/in/aryanzutshi/)
- [Github](https://github.com/Aryanzutshi)

#### Ayush Raj
- [Linkedin](https://www.linkedin.com/in/ayush-raj-411529289/)
- [Github](https://github.com/ayush78490) 
