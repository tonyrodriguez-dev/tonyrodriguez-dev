# 👋 Hey, I'm Tony

<p align="center">
  <img src="assets/profile-banner.svg" width="100%" alt="Tony Rodríguez Moreno · Smart contracts, Python and AI automation">
</p>

<p align="center"><strong>Solidity &amp; EVM · Python Backend · AI Automation</strong><br>📍 Castellón, Spain</p>

<p align="center">
  <a href="https://github.com/tonyrodriguez-dev/solidity-starter-projects"><img alt="Solidity projects" src="https://img.shields.io/badge/Solidity_Projects-5C46BE?style=for-the-badge&amp;logo=solidity&amp;logoColor=white"></a>
  <a href="https://www.linkedin.com/in/tonyrodriguezmoreno/"><img alt="Connect on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
</p>

## 👨‍💻 About Me

I build smart contracts, Python backends and AI workflows. My background in ceramic logistics shapes how I approach automation. I pay attention to the handoff between people and software, especially when a workflow needs someone to review an exception.

```python
tony = {
    "based_in": "Castellón, Spain",
    "building_now": "CryptoBank in Solidity",
    "working_with": ["Solidity", "Python", "FastAPI"],
    "interests": ["DeFi", "tokenization", "AI agents"],
}
```

## 🚀 Currently Building

### 🏦 CryptoBank

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white) ![In progress](https://img.shields.io/badge/In%20progress-7751BA?style=for-the-badge)

I'm building an ETH vault that tracks how much each address can withdraw. Three cases guide the design:

| Design decision | What I'm checking |
| --- | --- |
| 👛 **Track balances per address** | One account cannot withdraw another account's deposit. |
| 🎚️ **Check the balance after a deposit** | Reaching the limit is allowed. One extra wei is rejected. |
| 🔄 **Update the balance before sending ETH** | If the recipient rejects the transfer, the withdrawal reverts and restores the balance. |

## 🛠️ Tech Stack

### ⛓️ Web3 & smart contracts

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white) ![Ethereum / EVM](https://img.shields.io/badge/Ethereum%20%2F%20EVM-5264D9?style=for-the-badge&logo=ethereum&logoColor=white) ![Remix](https://img.shields.io/badge/Remix-126A79?style=for-the-badge) ![OpenZeppelin](https://img.shields.io/badge/OpenZeppelin-4E5EE4?style=for-the-badge&logo=openzeppelin&logoColor=white)

### ⚙️ Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-087D72?style=for-the-badge&logo=fastapi&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST%20APIs-31527F?style=for-the-badge)

### 🤖 AI & automation

![LangChain](https://img.shields.io/badge/LangChain-176951?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-6B4BA1?style=for-the-badge&logo=langgraph&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-9551A1?style=for-the-badge) ![LLM integrations](https://img.shields.io/badge/LLM%20integrations-3C627D?style=for-the-badge)

### 🗄️ Data & tooling

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169A1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-AD292B?style=for-the-badge&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-1264B1?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-BB412B?style=for-the-badge&logo=git&logoColor=white)

### 🌐 Web tools I'm exploring

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## 📂 Featured Projects

| Project | What you can explore |
| --- | --- |
| 🪙 [**CryptoReal**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/blob/main/CryptoReal.sol) | An ERC-20 token built with OpenZeppelin. Its constructor mints 1,000 CRT to the deployer. |
| 🔗 [**Caller Identity Lab**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/connected-contracts) | Connected contracts, interfaces and a security study comparing `msg.sender` with `tx.origin`, with local reproduction steps. |
| 💸 [**ETH Transfers Lab**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/eth-transfers) | Deposits with `payable`, withdrawals via `call` and a documented test showing why withdrawal permissions matter. |
| 🛡️ [**Access Checks Lab**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/access-checks) | Three ways to check an administrator address, with examples of the revert data each approach produces. |
| 👤 [**Sender**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/msg-sender) | Constructor initialization and the difference between a stored owner and the caller of a later request. |
| 🧮 [**Calculadora**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/blob/main/Calculadora.sol) | A Solidity calculator with a persistent accumulator, arithmetic events and an input check implemented as a modifier. |

[**Browse my Solidity projects and try them locally ↗**](https://github.com/tonyrodriguez-dev/solidity-starter-projects)

## 🤝 Connect With Me

I'm interested in smart contract development, Python backends and AI automation. I'm open to opportunities in Spain and with remote teams.

[**Tony Rodríguez Moreno on LinkedIn ↗**](https://www.linkedin.com/in/tonyrodriguezmoreno/)
