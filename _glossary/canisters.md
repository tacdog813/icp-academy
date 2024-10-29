---
slug: "canisters"
title: "Canisters"
description: "Smart contracts on the internet computer are called Canisters"
content: "Canisters on the Internet Computer Protocol (ICP) are specialized smart contracts capable of handling both the frontend and backend components of a decentralized application (dApp) entirely on-chain."
difficulty: Beginner
tags: ["Web3", "Blockchain", "ICP"]
---

Canisters on the Internet Computer Protocol (ICP) are specialized **smart contracts** capable of handling both the **frontend and backend** components of a decentralized application (dApp) entirely on-chain.

This is a significant step toward full-scale decentralization, as it removes dependency on off-chain servers and external cloud services. Canisters combine **code and state** within a unified structure and leverage **WebAssembly (Wasm)** to execute efficiently, secured by ICP’s **chain-key cryptography**.

Developers can use canisters to deliver HTML, CSS, JavaScript, and data seamlessly, creating a user experience similar to Web2 apps.

Canisters were developed by the **DFINITY Foundation** to overcome the limitations of traditional smart contracts, such as those on **Ethereum**. These older platforms face issues like high gas fees, limited scalability, and backend dependencies. Canisters on ICP enable a low-cost, high-performance solution where full-scale dApp functionality—frontend and backend—is fully decentralized and operates without relying on any off-chain infrastructure.

**How Canisters Work:**

1. **Smart Contracts with Persistent State:** Canisters maintain their **state on-chain**, securely processing transactions and updates. ICP’s **chain-key cryptography** protects every interaction, making canisters resistant to tampering and providing secure state changes.
2. **Concurrency with the Actor Model:** Utilizing the **actor model**, canisters manage multiple requests simultaneously, which increases scalability and efficiency as they operate asynchronously.
3. **Wasm-Based Execution Environment:** Compiled to Wasm, canisters are portable, secure, and efficient, enabling developers to deploy applications written in **Motoko** or **Rust** directly on ICP.
4. **Cycle-Based Model for Computation:** Canisters run on **cycles**, akin to gas fees, covering execution costs predictably. Developers convert ICP tokens into cycles, which fuel computation as the canister operates.
5. **Flexible Mutability:** Canisters are not immutable by default. This feature allows them to be upgraded by developers or by a DAO. Canisters can be controlled by a DAO or a developer. They can also be made immutable by setting their controller to a Blackhole address (ICP's burn address).

**Advantages of Canisters:**

- **Full-Scale Decentralization (Frontend and Backend):** Canisters host both the **frontend and backend** components entirely on-chain, allowing developers to build dApps without needing any centralized or cloud-based servers.
- **High Security and HTTPS Support:** With **chain-key cryptography**, canisters are secure, with each transaction verified. The **HTTPS support** enables seamless, secure user access, mirroring the security standards of traditional web applications.
- **Cost Efficiency and Scalability:** Canisters enable high performance at a low cost, with data storage priced at approximately $5 per GB annually, and provide fast, Web2-level page load times (around 200ms), making them ideal for large-scale dApps.

**Practical Applications:**

1. **DeFi Platforms:** Canisters support DeFi protocols like **ICPSwap** by managing trading, liquidity, and transaction functions directly on-chain with low transaction fees.
2. **Web-Based Social and Media Apps:** Canisters make it possible to host social networks, messaging platforms, and other interactive apps directly on ICP without needing off-chain components.
3. **Enterprise Solutions:** Large-scale applications, from secure messaging to data storage and analytics platforms, can leverage canisters' persistent, decentralized state management and secure execution.

**Types of Canister Calls:**

- **Update Calls:** These modify canister states, handling tasks like transaction processing and are cryptographically verified on-chain for security. Update calls require consensus to finalize.
- **Query Calls:** Designed for data retrieval, query calls are fast and ideal for reading canister data without altering state, ensuring efficiency for user requests. Query calls do not require consensus as they do not alter sate.

A decentralized finance (DeFi) application such as **ICPSwap** uses canisters to manage transactions, execute smart contracts, and store data for trade execution and liquidity management. By hosting all components directly on-chain, these dApps benefit from fast, efficient, and fully decentralized operations.

Canisters are transformative for the blockchain landscape, allowing both frontend and backend dApps to operate without reliance on external infrastructure, secured by HTTPS and chain-key cryptography. This infrastructure is foundational to the Internet Computer, positioning it as a leader in full-scale decentralization.

**Further Exploration:**

- Discover more on **chain-key cryptography** and its role in canister security.
- Learn how **cycles** streamline predictable costs compared to traditional gas fees.
- See how **on-chain hosting of frontend and backend** differentiates ICP from other blockchain networks.
