# 🚀 Getting Started with Boa-favorites-cu

![Smart Contract Deployment](https://user-images.githubusercontent.com/123456789/boa-contract-deployment.png)
*Deploy contracts with a single command using Titanoboa!*

## What is Boa-favorites-cu?

**Boa-favorites-cu** is a fast, Pythonic way to deploy and interact with your "favorites" smart contract, using [titanoboa](https://github.com/vyperlang/boa) for development and local testing.

---

## 🛠️ Quick Start: Deploying to the “pyevm” Network

Fire up your terminal and run:

```bash
# Set up the pyevm environment
boa env use pyevm

# Deploy your favorites contract (replace Favorite.json with your file)
boa deploy contracts/Favorite.json
```

You’ll see output like:
```bash
✨ Contract deployed at 0xABCDEF1234... on network: pyevm
```

---

## 👨‍🚀 Pro Tip: Switching Environments

Switch between networks or testing setups easily:

```bash
boa env use anvil  # Switch to Anvil for more realistic EVM testing
```

---

## 🎨 Why Use Boa-favorites-cu?

- **Python-first workflow**
- Rapid local development
- Easy environment switching
- Simple account management

> ![Python & Boa Logo](https://raw.githubusercontent.com/vyperlang/boa/main/.github/logo-boa.png)
> _Built for developers who love Python and Ethereum!_

---

For more on contract interaction, account management, and automation, check out the detailed docs or run:
```bash
boa --help
```
