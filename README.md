# 🧠 Discord Bot Assistant – Web3 Made Easy on Discord

Welcome to **Discord Bot Assistant**, a project that bridges **Discord** and **Web3** through **MetaMask**, allowing users to interact with blockchain-based tools without ever leaving their favorite chat platform.

This repository serves as the **main hub** for our full-stack hackathon project, connecting two core parts:

- 🔗 [Frontend – Next.js Website (with MetaMask)](https://github.com/senderro/discordbotassistant)
- 🤖 [Backend – Discord Bot + API (Express + Prisma)](https://github.com/senderro/botAndApi)

---

## 🎯 What is the project about?

**Discord Bot Assistant** simplifies Web3 for everyone — especially non-technical users — by integrating MetaMask features directly inside Discord.

From wallet registration to donations and token transfers, our system makes interacting with crypto:

- intuitive 👶  
- social 🫂  
- and frictionless 🚀

Perfect for communities who want to onboard users into crypto, run token-based campaigns, or manage member incentives — all within Discord threads.

---

## 🧰 Features

- 🦊 **MetaMask integration** via website (Next.js + Wagmi)
- 🤖 **Discord bot** commands like `/register`, `/send`, and `/donation`
- 🔐 Secure actions using **JWT tokens**
- 📦 Backend powered by **Express** and **Prisma (PostgreSQL)**
- 📊 Tracks all user actions: transactions, raffles, donations, and more
- 🔗 All user interactions are tied to their Discord ID

---

## 🔧 Architecture Overview

| Layer      | Stack                                 |
|------------|----------------------------------------|
| Frontend   | Next.js, Wagmi, MetaMask SDK, Tailwind |
| Backend    | Express (API), Prisma, PostgreSQL      |
| Bot Engine | discord.js                             |
| Auth       | JWT (via bot-issued tokens)            |
| Deploy     | Vercel (frontend) + Railway (bot/api)  |

---

## 📁 Repository Structure

| Component | Description | Link |
|----------|-------------|------|
| 🌐 Website (Frontend) | Next.js frontend where users register/connect their wallet, donate, and interact with blockchain. | [discordbotassistant](https://github.com/senderro/discordbotassistant) |
| 🤖 Bot & API (Backend) | Discord bot that handles commands and interacts with the API and database. | [botAndApi](https://github.com/senderro/botAndApi) |

---

## 🛠️ Hackathon Progress

We’ve built a complete MVP with a clean architecture that supports adding new features quickly.  
Everything is structured to scale and integrate with other Web3 tools or DAOs.

---

## 💸 Funding Status

Currently **unfunded**. The project has been built 100% independently.

---

## 🤝 Contributions

Feel free to fork the repositories, test the bot, or suggest improvements via issues or PRs!

---

## 📬 Contact

For collaborations or demo access, feel free to contact:

- 🧑‍💻 [@senderro on GitHub](https://github.com/senderro)

---

> “Bringing the Web3 experience to where communities already live: Discord.” 🎯
