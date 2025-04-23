# 📚 BookChain

**A Decentralized Publishing Infrastructure for the Future of Content Ownership.**  
Built on **Starknet**, powered by **Stellar** payments, and distributed via **IPFS**.

## ✨ Overview

BookChain is an open-source protocol for decentralized digital publishing.  
It empowers authors, creators, and readers to **mint, own, trade, and govern** digital books as NFTs on Starknet.

With features like smart contract royalties, DAO governance, decentralized file storage, and crypto-native payments, BookChain transforms books into on-chain assets—preserving intellectual property while ensuring global accessibility.


## 🔧 Tech Stack

| Layer        | Stack                                                                 |
|--------------|-----------------------------------------------------------------------|
| **Frontend** | [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com), [Starknet.js](https://github.com/0xSpaceShard/starknet.js) |
| **Backend**  | [NestJS](https://nestjs.com/), [PostgreSQL](https://www.postgresql.org), [IPFS](https://ipfs.tech) |
| **Smart Contracts** | [Cairo](https://www.cairo-lang.org/) on [Starknet](https://www.starknet.io/) |
| **Payments** | [Stellar Network](https://stellar.org) (royalties, wallet management) |
| **Infra/Tooling** | Docker, Turborepo, GitHub Actions, Husky, ESLint, Prettier |


## 🚀 Features

- 📖 **Book NFTs**  
  Mint books as non-fungible tokens on Starknet, complete with metadata and content hash.

- 💸 **Creator Royalties via Stellar**  
  Built-in revenue splits and payments for authors using Stellar smart wallets.

- 🌍 **Decentralized Storage**  
  IPFS-powered document delivery to ensure permanence and censorship resistance.

- 🧠 **DAO Governance**  
  Token holders can vote on protocol upgrades, content curation, and royalties.

- 🛠 **Modular Monorepo**  
  Managed with Turborepo — scalable for teams and contributions.


## 📁 Monorepo Structure
bookchain-project/
├── apps/
│   ├── frontend/       # Next.js client
│   └── backend/        # NestJS server
├── contracts/          # Starknet (Cairo) smart contracts
├── packages/           # Shared components, config, utils
├── docker/             # Docker & Docker Compose
├── docs/               # Developer and protocol documentation
└── .github/            # GitHub Actions workflows

## 🧑‍💻 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-org/bookchain-project.git
cd bookchain-project
```

### 2. Install dependencies
```bash
pnpm install
```

### 3. Start all services (local dev)
```bash
pnpm dev
```

---

## 🧪 Tests

- Run all backend and frontend unit tests:
```bash
pnpm test
```

- Lint and format code:
```bash
pnpm lint
pnpm format
```

## 🙌 Contributing

We welcome contributions from all open-source and web3 builders!  
See [`CONTRIBUTING.md`](./CONTRIBUTING.md) to get started.

- 🔎 Check [Issues](https://github.com/sta/bookchain-project/issues) for open tasks
- 🛠 PRs must pass tests and linting
- 🧠 Ask questions via Discussions or Telegram

## 🛡️ License

This project is licensed under the MIT License.  
See [`LICENSE`](./LICENSE) for details.



> “The future of publishing is permissionless, peer-owned, and permanent.”

```
