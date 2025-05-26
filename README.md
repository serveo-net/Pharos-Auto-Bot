# Pharos-Auto-Bot

![icon logo](https://github.com/serveo-net/Pharos-Auto-Bot/blob/main/pharos-icon)

Join [Pharos Testnet](https://testnet.pharosnetwork.xyz/experience?inviteCode=reEZLdnbFy2qCwb0)

Pharos Auto Bot is an educational chatbot designed to help users learn various concepts and topics through interactive conversations.

---

## 1. Features

- Daily claims & faucet claims (make sure you have linked your X/twitter account)
- Error handling, and frezz
- Return Tx-Hash to api to complete text
- multi account
- support proxy or not if you don't want to use it

## 2. How to run

1. Clone Repositor
   ```
   git clone https://github.com/serveo-net/Pharos-Auto-Bot.git
   cd Pharos-Auto-Bot
   ```
2. Installation dependencies
   ```
   npm install
   ```
3. Replace **.env** with your private key
   ```
   nano .env
   ```
   **example :**
   
   *PRIVATE_KEYS=0x...pvkey1,0x...pvkey2,0x...pvkey3*
4. replace **proxies.txt** with your proxy ( Optional )
   ```
   nano proxies.txt
   ```
   **one proxy per line**

6. Replace **recipients.json** with the destination wallet ( Optional )
   ```
   nano recipients.json
   ```
   **note:**
   **- must have 65 wallet addresses**
   **- replace with the wallet address you have**

7. use screen to run continuously
   ```
   screen -S Pharos-Auto-Bot
   ```
    
9. run bot
   ```
   node main.js
   ```
10. Press **CTRL + A + D** to exit the screen without stopping the process
    
## Usage

Use this bot wisely and responsibly. All content provided by this bot is intended for educational purposes only.

## Disclaimer

This bot is created solely for educational purposes. Users are fully responsible for how they use the information obtained from this bot. The developer is not liable for any misuse or damages that may result from using this bot.

## Contributing

Contributions to improve this bot are always welcome. Please open an issue or pull request if you'd like to contribute.

## License

![Version](https://img.shields.io/badge/version-1.0.0-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()

---

Use wisely and always prioritize responsible learning.

---

**Donate to buy coffee**

EVM = [0x0e6e521F6A51D45A49A62C0e5c18c57890804091](0x0e6e521F6A51D45A49A62C0e5c18c57890804091)

Solana = [C8PEvAeQoUwBVmt1Ji2dDDG3KBudu9wA9ReLpjME9X4d](C8PEvAeQoUwBVmt1Ji2dDDG3KBudu9wA9ReLpjME9X4d)

---
