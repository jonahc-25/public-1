# 🦊 MetaMask Setup Guide (Ethereum Sepolia Testnet)

This guide walks you through installing and configuring MetaMask to use the **Sepolia test network** for development and testing.

---

## 📌 Prerequisites

- A modern browser (Chrome, Firefox, Edge, or Brave)
- Internet connection

---
![logo](logo.png)
## 1. Install MetaMask

1. Go to the official MetaMask website:  
   https://metamask.io/download/

2. Install the browser extension for your browser.

3. Once installed, click the MetaMask icon in your browser toolbar.

---

## 2. Create or Import a Wallet

### Option A: Create a New Wallet
1. Click **“Create a new wallet”**
2. Set a secure password
3. Save your **Secret Recovery Phrase** somewhere safe  
   ⚠️ *Do NOT share this with anyone*

### Option B: Import Existing Wallet
1. Click **“Import wallet”**
2. Enter your recovery phrase
3. Set a password

---

## 3. Enable Test Networks

By default, MetaMask hides test networks.

1. Open MetaMask
2. Click your profile icon (top right)
3. Go to **Settings → Advanced**
4. Toggle **“Show test networks”** ON

---

## 4. Switch to Sepolia Network


1. At the top of MetaMask, click the network dropdown
2. Select **“Sepolia”**

If you don’t see it:
- Ensure test networks are enabled (Step 3)

---

## 5. Get Sepolia Test ETH

You’ll need test ETH to simulate transactions.

### Use a faucet:

- https://sepoliafaucet.com/
- https://faucets.chain.link/sepolia

### Steps:
1. Copy your wallet address from MetaMask
2. Paste it into the faucet
3. Request test ETH

💡 It may take a minute to appear in your wallet.

---

## 6. (Optional) Add Custom Token

If your project uses a custom ERC-20 token:

1. Scroll down in MetaMask
2. Click **“Import tokens”**
3. Enter:
   - Token Contract Address
   - Token Symbol
   - Decimals
4. Click **Add Token**

---

## 7. Connect MetaMask to the Application

1. Open your application
2. Click **“Connect Wallet”**
3. MetaMask will prompt you to approve connection
4. Click **Confirm**

✅ Once connected:
- Your wallet address should appear in the UI
- You can now send transactions

---

## ⚠️ Common Issues

### MetaMask not detected
- Make sure the extension is installed and enabled
- Refresh the page

### Wrong network
- Ensure MetaMask is set to **Sepolia**

### No test ETH
- Use a faucet (Step 5)

### Transaction stuck or failing
- Check gas fees
- Ensure sufficient test ETH balance

---

## 🔒 Security Notes

- Never share your **Secret Recovery Phrase**
- Do not reuse your real wallet for testing
- Always verify URLs before connecting your wallet

---

## ✅ Summary

You are ready to:
- Connect MetaMask to the app
- Send transactions on Sepolia
- Test blockchain functionality safely
