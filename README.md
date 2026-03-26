<div align="center">
  <img src="https://img.shields.io/badge/SHELBYCHAT-FF4DAA?style=for-the-badge&logo=chat&logoColor=white" width="200" />
  <h1>🌸 ShelbyChat</h1>
  <p><strong>AI Chat on Shelby Testnet</strong><br />Every message confirmed on-chain with gas fee • Powered by Aptos</p>
  <p>
    <a href="https://shelbychat.vercel.app/"><img src="https://img.shields.io/badge/demo-live-ff4daa?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    <a href="https://github.com/gunduul/shelbychat"><img src="https://img.shields.io/github/stars/gunduul/shelbychat?style=for-the-badge&logo=github&color=gold" /></a>
    <a href="https://github.com/gunduul/shelbychat/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-pink?style=for-the-badge" /></a>
  </p>
</div>

---

## 🚀 Live Demo

> **👉 [shelbychat.vercel.app](https://shelbychat.vercel.app/)**

Connect your Petra Wallet and start chatting — every message is a transaction on the Shelby blockchain.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🤖 **AI Chat** | Smart responses powered by Groq / Hugging Face (Llama 3, Mistral) |
| ⛽ **On-Chain Gas Fee** | Every chat pays `0.0025 SHELBY_USD` recorded on Shelby Testnet |
| 🔗 **Explorer Integration** | Click transaction hash → View on [Aptos Explorer](https://explorer.aptoslabs.com/) |
| 👤 **Unique Avatar** | Each wallet gets a unique emoji avatar based on wallet address |
| 💾 **Persistent History** | Chat history saved in `localStorage` — survives refresh & disconnect |
| 🔐 **Wallet Connect** | Seamless integration with [Petra Wallet](https://petra.app/) |

---

## 🛠️ Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Aptos-000000?style=for-the-badge&logo=aptos&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-000000?style=for-the-badge&logo=groq&logoColor=white" />
</div>

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Backend** | Vercel Serverless Functions |
| **Blockchain** | Aptos / Shelby Testnet |
| **AI Models** | Groq (Llama 3), Hugging Face (Phi-3, Gemma) |
| **Wallet** | Petra Wallet (Aptos Wallet Standard) |

---

## 📸 Screenshots

<div align="center">
  <img src="ShelbyChat.png" width="80%" />
  <br />
  <em>ShelbyChat — AI Chat on Shelby Testnet</em>
</div>

---

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/gunduul/shelbychat.git
cd shelbychat

# Install dependencies (if any)
npm install

# Run locally with Vercel CLI
vercel dev

# Or just open index.html in browser

```

## 🔧 Environment Variables

```
Create .env file (for local development) or set in Vercel:

Variable	Description
GROQ_API_KEY	Groq API key for AI responses
HF_API_KEY	Hugging Face API key (fallback)

---

## 📁 Project Structure

```
shelbychat/
├── api/
│   ├── balance.js      # ShelbyUSD balance from chain
│   ├── chat.js         # AI + transaction verification
│   ├── prices.js       # Crypto prices from CoinGecko
│   └── view.js         # Aptos view function proxy
├── public/
│   └── favicon.ico
├── index.html          # Main frontend
├── vercel.json         # Vercel config
├── package.json
└── README.md

---

## 🧠 How It Works

---
<div align="center"> <table> <tr> <td width="25%" align="center"><strong>1️⃣ Connect Wallet</strong><br />Petra Wallet → Address detected</td> <td width="25%" align="center"><strong>2️⃣ Type Message</strong><br />Gas fee modal appears</td> <td width="25%" align="center"><strong>3️⃣ Confirm Transaction</strong><br />Send to Shelby blockchain</td> <td width="25%" align="center"><strong>4️⃣ AI Responds</strong><br />Groq/Hugging Face reply</td> </tr> </table> </div>

---

## 🔗 Related Links

---
Resource	Link
🌐 Shelby Testnet	docs.shelby.xyz
🧾 Shelby Explorer	explorer.shelby.xyz
💎 Petra Wallet	petra.app
🧠 Groq API	console.groq.com
📊 CoinGecko	coingecko.com

---

## 📝 License

---
This project is licensed under the MIT License — feel free to use, modify, and distribute.

---

## 🌟 Show Your Support

---
If you like this project, give it a ⭐ on GitHub!

<div align="center"> <sub>Built with 💗 by <a href="https://github.com/gunduul">gunduul</a> • Powered by Aptos & Shelby</sub> </div> ```
