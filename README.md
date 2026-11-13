<p align="center">
  <img src="assets/profile-banner.svg" width="100%" alt="Tony Rodríguez Moreno · Smart contracts, Python and AI automation">
</p>

<p align="center">
  <strong>Solidity &amp; EVM · Python Backend · AI Automation</strong><br>
  Castellón, Spain
</p>

<p align="center">
  <a href="#currently-building">Current project</a> ·
  <a href="#selected-work">Selected work</a> ·
  <a href="#tech-stack">Tech stack</a> ·
  <a href="https://www.linkedin.com/in/tonyrodriguezmoreno/">LinkedIn</a>
</p>

## About me

I'm Tony Rodríguez Moreno. I build Python backends, AI agent workflows and tools that automate manual work. I bring experience in warehouse operations and ceramic logistics to the way I design software, from validating inputs to deciding when a person should review an exception.

On the blockchain side, I work with Solidity and the EVM. My public repositories show the contracts, the rules they enforce and how to reproduce the behavior locally.

## Currently building

### CryptoBank · Solidity · In progress

I'm building an ETH vault with balances tracked per address. The goal is to let each account deposit and withdraw its own ETH, while enforcing a configurable deposit limit per account.

| Design decision | What I want to verify |
| --- | --- |
| **Separate balances for each address** | A withdrawal checks the caller's balance. Another account's deposit stays untouched. |
| **Limit the resulting balance** | A deposit that reaches the limit succeeds. An extra wei is rejected. |
| **Update the balance before sending ETH** | If the recipient rejects the transfer, the withdrawal reverts and the balance is restored. |

The next milestone is to reproduce these cases locally with two accounts and document the results.

## Selected work

| Project | What you can inspect |
| --- | --- |
| [**CryptoReal**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/blob/main/CryptoReal.sol) | An OpenZeppelin ERC-20 contract that mints 1,000 CRT to the deployer. |
| [**Connected Contracts**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/connected-contracts) | A two-contract system that illustrates how `msg.sender` changes across calls and why `tx.origin` is a poor authorization check. |
| [**ETH Transfers Lab**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/eth-transfers) | ETH deposits, withdrawals via `call` and a reproducible case where an unrestricted withdrawal exposes the shared balance. |
| [**Access Checks Lab**](https://github.com/tonyrodriguez-dev/solidity-starter-projects/tree/main/access-checks) | A comparison of `revert`, `require` and custom errors for the same admin check. |

[Browse all Solidity projects and local reproduction steps](https://github.com/tonyrodriguez-dev/solidity-starter-projects)

## Tech stack

| Area | Tools |
| --- | --- |
| **Blockchain** | Solidity · Ethereum / EVM · Remix · OpenZeppelin |
| **Backend** | Python · FastAPI · REST APIs |
| **AI automation** | LangChain · LangGraph · RAG · LLM integrations |
| **Data and tooling** | PostgreSQL · Redis · Docker · Git |

## Connect

I'm interested in roles involving smart contracts, Python backends or AI automation. I work in Spanish and welcome opportunities in Spain and remote teams.

[**LinkedIn · Tony Rodríguez Moreno**](https://www.linkedin.com/in/tonyrodriguezmoreno/)
