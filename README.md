# About
A sample smart contract deployed using **QuickNode's RPC's** and can be interacted with.
You can write your custom message to blockchain and display it! 

---
## Table of Contents
 - **contracts/GreetUser.sol** - Main solidity contract source code.
 - **scripts/deploy.js** - The deployment script.
 - **package-json.lock** - Contains all project dependency & skeleton
 - **hardhat.config.js** - The hardhat configuration file for deployment, requires `.env` file with `QUICKNODE_HTTP_URL` & `PRIVATE_KEY ` added 

Requires `dotenv` package to work



## How to interact
 
  1. Visit this [Goreli Ether Scan Address](https://goerli.etherscan.io/address/0xdA9595a862b0166BD74c49C1aE0C1ca3bbBdBbCA#writeContract)(Open in new tab!)
  2. Click on **Connect To Web 3** and then authenticate using *Metamask*
  3. Expand **setGreeting**, add your <u>text</u> and click *Write*
  4. Pay the transaction fees and let transaction *confirm*
  5. Navigate to **Read Contract**
  6. Expand **greet** and your message will be shown!
  
  ---
  Proof Of Interaction
  
  ![Proof](https://user-images.githubusercontent.com/74095712/200911700-b44b3d10-2e77-4c2f-8e10-71e7280e58ed.png)
  
  ---
