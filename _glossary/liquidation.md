---
slug: "liquidation"
title: "Liquidation"
description: "Liquidation is the process of converting assets into cash or equivalent value, typically to repay debts."
content: "Liquidation is the process of converting assets into cash or equivalent value, typically to repay debts. In traditional finance, liquidation occurs when a company or individual cannot meet their financial obligations, and assets are sold off to cover these liabilities."
difficulty: Beginner
tags: ["Web3", "DeFi", "Trading", "ICP"]
---

Liquidation is the process of converting assets into cash or equivalent value, typically to repay debts. In traditional finance, liquidation occurs when a company or individual cannot meet their financial obligations, and assets are sold off to cover these liabilities.

In the context of **decentralized finance (DeFi)** and **crypto                              currencies**, liquidation usually refers to the forced sale of assets when a borrower’s collateral falls below the required threshold for maintaining a loan.

Liquidation has been a core principle in traditional finance and legal frameworks, especially in the event of **bankruptcies** or insolvencies, where a company’s assets are sold to pay off creditors. In the blockchain and DeFi space, liquidation emerged as a key mechanism to secure lending and borrowing protocols. With the introduction of decentralized lending platforms such as **Aave** and **MakerDAO**, liquidation ensures that borrowers maintain sufficient collateral to back their loans, safeguarding the protocol from under-collateralized positions.

**How Liquidation Works in DeFi:**

1. **Collateralized Loans:** In decentralized lending, users borrow funds by locking up crypto assets as **collateral**. If the value of the collateral falls below a predetermined **liquidation threshold**, the protocol may automatically trigger liquidation to recover the loan.
2. **Liquidation Threshold:** This is the ratio of loan value to collateral value that must be maintained to avoid liquidation. For example, if the liquidation threshold is 150%, the value of the collateral must remain 1.5 times the value of the loan.
3. **Liquidation Process:** When the value of the collateral falls below the threshold, the protocol liquidates a portion (or all) of the borrower’s collateral. The liquidated collateral is sold to cover the outstanding loan, ensuring the protocol remains solvent.
4. **Liquidation Penalty:** Some platforms impose a penalty or fee on borrowers when their collateral is liquidated. This acts as an incentive for users to maintain a safe collateral ratio to avoid liquidation.
5. **Example in MakerDAO:** In **MakerDAO**, users can borrow **DAI** (a stablecoin) by locking up **ETH** as collateral. If the ETH price drops and the loan becomes under-collateralized, MakerDAO will trigger a liquidation auction to sell off the ETH and recover the DAI loan.

**Advantages of Liquidation:**

- **Risk Management:** Liquidation prevents the protocol from becoming under-collateralized, protecting lenders and maintaining stability in the system.
- **Market Stability:** By liquidating assets when collateral drops, DeFi platforms prevent large defaults that could negatively impact the market.
- **Incentives for Liquidators:** In most DeFi platforms, **liquidators** are incentivized with rewards or discounts for liquidating under-collateralized positions. This provides an economic reason for third parties to participate in the liquidation process.

**Challenges and Risks:**

1. **Volatility:** In the highly volatile world of crypto, collateral values can drop sharply, leading to rapid liquidations that exacerbate market sell-offs.
2. **Gas Fees (On Ethereum):** During periods of network congestion, gas fees can spike, making liquidation more expensive and reducing the profit margins for liquidators.
3. **Risk of Over-Collateralization:** To avoid liquidation, borrowers may over-collateralize their loans, which can reduce capital efficiency and limit their borrowing power.

**Practical Applications:**

1. **Decentralized Lending Protocols:** Platforms like **Aave**, **Compound**, and **MakerDAO** heavily rely on liquidation mechanisms to ensure loans remain collateralized.
2. **Automated Market Makers (AMMs):** Some AMMs employ liquidation mechanisms to maintain market stability in scenarios where liquidity providers face significant losses due to market fluctuations.
3. **Cross-Chain Liquidation:** In the future, cross-chain lending platforms may implement liquidation mechanisms that enable liquidations across different blockchains, providing more flexibility for users holding assets on multiple chains.

**Liquidation on ICP:**

**Low Gas Fees:** Unlike Ethereum, where high gas fees can make liquidations costly, the **Internet Computer Protocol (ICP)** offers low-cost transactions, making liquidation more efficient and accessible.

**Fully On-Chain Liquidation:** On ICP, liquidation processes can be fully automated and executed entirely on-chain, ensuring transparency and reducing the reliance on off-chain mechanisms or centralized services.

On **MakerDAO**, if a user borrows DAI by locking up ETH and the price of ETH drops significantly, MakerDAO will trigger a liquidation process to recover the DAI loan by auctioning off the user's ETH collateral. This prevents the protocol from becoming insolvent and ensures that the system remains over-collateralized.

Liquidation is an essential mechanism for maintaining the integrity of decentralized finance protocols. As DeFi continues to evolve, improved risk management tools and more efficient liquidation mechanisms will be crucial for scaling lending and borrowing markets. Platforms like **ICP** will likely play a key role in advancing on-chain liquidation processes, enabling lower fees and faster execution.

**Further Exploration:**

- Explore the role of **automated liquidators** in DeFi and how they profit from liquidating under-collateralized loans.
- Learn how **cross-chain** liquidity and liquidation mechanisms might impact the future of decentralized lending.
- Compare **liquidation penalties** across different DeFi platforms to understand their role in incentivizing borrowers to maintain healthy collateral ratios.
