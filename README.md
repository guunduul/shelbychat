<div align="center">
  <img src="https://raw.githubusercontent.com/aptos-labs/aptos-core/main/ecosystem/assets/aptos-wordmark.png" width="120" />
  <h1>🌸 ShelbyChat</h1>
  <p><strong>AI Chat on Shelby Testnet</strong><br />Every message confirmed on-chain with gas fee • Powered by Aptos</p>
  <p>
    <a href="https://shelbychat.vercel.app/"><img src="https://img.shields.io/badge/demo-live-ff4daa?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    <a href="https://github.com/guunduul/shelbychat"><img src="https://img.shields.io/github/stars/guunduul/shelbychat?style=for-the-badge&logo=github&color=gold" /></a>
    <a href="https://github.com/guunduul/shelbychat/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-pink?style=for-the-badge" /></a>
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

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/guunduul/shelbychat.git
cd shelbychat

# Install dependencies (if any)
npm install

# Run locally with Vercel CLI
vercel dev

# Or just open index.html in browser
🔧 Environment Variables
Create .env file (for local development) or set in Vercel:

Variable	Description
GROQ_API_KEY	Groq API key for AI responses
HF_API_KEY	Hugging Face API key (fallback)

📁 Project Structure
text
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

🧠 How It Works
User connects Petra Wallet → Address detected

User types message → Gas fee modal appears

User confirms → Transaction sent to Shelby blockchain (register_blob)

Transaction recorded → Hash appears in chat + Explorer link

AI responds → Groq / Hugging Face generates smart reply

🔗 Related Links
Resource	Link
🌐 Shelby Testnet	docs.shelby.xyz
🧾 Shelby Explorer	explorer.shelby.xyz
💎 Petra Wallet	petra.app
🧠 Groq API	console.groq.com
📊 CoinGecko	coingecko.com

📝 License
This project is licensed under the MIT License — feel free to use, modify, and distribute.

🌟 Show Your Support
If you like this project, give it a ⭐ on GitHub!

<div align="center"> <sub>Built with 💗 by <a href="https://github.com/guunduul">guunduul</a> • Powered by Aptos & Shelby</sub> </div> ```
