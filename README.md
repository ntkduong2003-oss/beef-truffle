# 🥩 Beef Supply Chain DApp

Beef traceability prototype on blockchain (Solidity + Truffle + Ganache + Ethers.js).

## 📦 Features
- Create batches with hash ID.
- Transfer custody between parties.
- Flag non-compliance with reasons.
- Close batches when completed.
- Simple web UI, MetaMask connection.

## 🛠️ Technology
- Solidity 0.8.20, Truffle
- Ganache (local), MetaMask
- Frontend: HTML + Ethers v6

## ⚙️ How to run
```bash
# 1) Run chain local
npx ganache --port 7545 --chain.chainId 1337 --chain.networkId 1337

# 2) Deploy contract (in project folder)
npx truffle migrate --reset --network development

# 3) Open index.html file with browser (or serve via VS Code Live Server)
 npx serve
# 4) Connect MetaMask (Ganache Local) → paste contract address → Create/Transfer/Flag/Close operation
