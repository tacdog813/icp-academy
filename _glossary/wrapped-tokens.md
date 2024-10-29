---
slug: "wrapped-tokens"
title: "Wrapped Tokens"
description: "Wrapped tokens are tokens that represent assets from another blockchain, enabling them to be used on different blockchains without directly transferring the original asset"
content: "Wrapped tokens are tokens that represent assets from another blockchain, enabling them to be used on different blockchains without directly transferring the original asset."
difficulty: Beginner
tags: ["Web3", "DeFi", "Blockchain", "ICP"]
---

**Wrapped tokens** are tokens that represent assets from another blockchain, enabling them to be used on different blockchains without directly transferring the original asset.

A wrapped token is essentially a representation or **"wrapped"** version of an asset (like Bitcoin or Ether) on a different blockchain.

For example, **Wrapped Bitcoin (WBTC)** is a version of Bitcoin that exists on the Ethereum blockchain, allowing users to interact with DeFi protocols on Ethereum using Bitcoin. Wrapped tokens maintain a 1:1 peg with the underlying asset, ensuring that the value of the wrapped token mirrors the original asset.

The concept of wrapped tokens emerged as a way to solve the **interoperability** problem between different blockchains. Before the advent of wrapped tokens, users couldn’t easily move assets between blockchain ecosystems.

For example, if someone wanted to use their Bitcoin in Ethereum's DeFi ecosystem, they’d have to sell it for Ether or some other ERC-20 token. Wrapped tokens changed that by allowing Bitcoin and other non-Ethereum assets to be tokenized and brought onto the Ethereum network. **Wrapped Bitcoin (WBTC)** was introduced in 2019, and since then, wrapped tokens have been used across various DeFi platforms for lending, staking, and trading.

ICP utilizes Chain Key technology and Chain Fusion technology to wrap multi chain assets like Bitcoin and Ethereum without any middlemen. ICP’s Canister Smart Contracts will custody Bitcoin tokens directly and issue a digital twin, aka ckBTC on ICP network. The ckBTC gets the superpowers of ICP network and can be used within smart contracts for seamless composability and user experience.

**How Wrapped Tokens Work:**

1. **Pegged to the Underlying Asset:** Wrapped tokens maintain a 1:1 peg to the original asset. For example, for every Wrapped Bitcoin (WBTC) on Ethereum, there’s a corresponding real Bitcoin locked in a reserve, ensuring that WBTC maintains the same value as Bitcoin.
2. **Custodian Services:** To issue a wrapped token, a **custodian** (a centralized entity or smart contract) holds the original asset in reserve. This ensures that each wrapped token is fully backed by the underlying asset, preventing inflation or dilution of value.
3. **Interoperability Across Chains:** Wrapped tokens allow assets from one blockchain to be used on another blockchain. This enables cross-chain interoperability, allowing users to access decentralized applications (dApps) and DeFi protocols on Ethereum, Solana, Binance Smart Chain, and others using assets from different blockchains.

**Advantages of Wrapped Tokens:**

- **Cross-Chain Interoperability:** Wrapped tokens provide seamless **interoperability** between blockchains. Bitcoin holders can now participate in Ethereum’s DeFi protocols or Solana's dApps without selling their BTC, preserving the asset while gaining access to new ecosystems.
- **Increased Liquidity for DeFi:** By wrapping assets like Bitcoin or Ether, users can unlock liquidity in DeFi protocols, providing collateral for loans, staking in liquidity pools, or earning interest in lending platforms.
- **Expanding Use Cases for Non-Native Tokens:** Wrapped tokens give assets like Bitcoin, Litecoin, or even traditional financial assets like gold a new range of use cases on smart contract platforms like Ethereum. This boosts the utility of assets that were previously restricted to their native chains.

**Challenges and Risks:**

1. **Centralization Risks (Custodian Control):** Wrapped tokens often rely on a **centralized custodian** to hold the original asset in reserve. If the custodian is hacked or goes rogue, the wrapped tokens could lose their value, as the reserve backing them is compromised.
2. **Smart Contract Vulnerabilities:** If a wrapped token operates via a smart contract, vulnerabilities in the contract could result in the loss of funds or unintended behavior, such as minting too many wrapped tokens or failing to maintain the 1:1 peg.
3. **Trust and Transparency Issues:** Users must trust that custodians or decentralized protocols will accurately manage the reserves backing the wrapped tokens. A lack of transparency or auditing could lead to doubts about the legitimacy of the wrapped asset.

**Practical Applications:**

1. **DeFi Lending and Borrowing:** Wrapped tokens like **Wrapped Bitcoin (WBTC)** allow Bitcoin holders to participate in DeFi lending platforms like **Aave** or **Compound**, using their BTC as collateral without needing to convert it into another asset.
2. **Liquidity Provision in AMMs:** Wrapped tokens can be deposited into **automated market makers (AMMs)** like **Uniswap**, where they help provide liquidity for trading pairs involving wrapped assets, earning LPs trading fees in return.
3. **Cross-Chain Bridges:** Wrapped tokens play a key role in cross-chain bridges, allowing assets to move between different blockchains. For instance, a user can transfer Bitcoin from the Bitcoin network to Ethereum by wrapping it into WBTC and using it in Ethereum-based DeFi applications.

**Wrapped Tokens in ICP:**

**Secure Token Wrapping with Chain Key Cryptography:** The **Internet Computer Protocol (ICP)** can enable token wrapping using **Chain Key Cryptography**, allowing users to wrap assets in a highly secure and decentralized manner, reducing reliance on centralized custodians. This enhances the security and transparency of the wrapped tokens.

**Native Bitcoin Integration on ICP:** ICP’s direct Bitcoin integration (without the need for wrapping) makes it easier to use Bitcoin in DeFi applications on the Internet Computer. Even Ethereum tokens can be custodied and wrapped on ICP network by ICP Smart Contracts.

**Example:**

**Wrapped Bitcoin (WBTC)** is one of the most popular wrapped tokens, enabling Bitcoin holders to use their BTC on Ethereum. WBTC is fully backed by Bitcoin, with custodians holding the real BTC in reserves, while WBTC is traded and used in Ethereum’s DeFi ecosystem. WBTC allows users to lend, stake, and trade their Bitcoin without leaving the Ethereum network.

Wrapped tokens are crucial for unlocking cross-chain functionality and expanding the use cases of assets locked within their native blockchains. As blockchain interoperability improves, expect to see more seamless and decentralized mechanisms for wrapping assets, enhancing both the security and utility of cross-chain tokens.

**Further Exploration:**

- How do decentralized and trustless wrapping mechanisms improve the security of wrapped tokens compared to centralized custodians?
- Explore the potential of fully decentralized cross-chain bridges for the future of blockchain interoperability.
