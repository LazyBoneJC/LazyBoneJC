# Hi there, I'm Yu-Wei Chang 👋

<div align="left">
  <a href="https://www.linkedin.com/in/yu-wei-chang-6714a91a4/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:wc065426@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>

<br />

I'm a **Web3 Full-stack Engineer** with a security-first mindset.

Transitioning from building data-driven backend systems to the decentralized web, I focus on bridging the gap between robust smart contracts and seamless front-end experiences. I thrive on building resilient DApps, hunting for protocol vulnerabilities, and solving complex engineering challenges.

---

### 🚀 Featured Projects

<details open>
<summary><b>🏪 Neon Marketplace (Full-stack NFT Platform)</b></summary>
<br/>
A non-custodial, cyberpunk-themed NFT marketplace supporting on-chain SVG NFTs and ERC-20 payments, deployed on Sepolia Testnet.
<ul>
    <li><b>Custom Indexing Architecture:</b> Engineered a high-performance event indexer using <b>Rindexer (Rust)</b> and PostgreSQL, bypassing traditional subgraphs for real-time data synchronization.</li>
    <li><b>Smart Contract Engineering:</b> Developed the core marketplace protocol (Listing/Buying/Canceling) and implemented fully <b>On-chain SVG generation</b> (NinjaNFT) using Solidity & Foundry.</li>
    <li><b>DevOps & Security:</b> Solved complex Monorepo deployment challenges on <b>Zeabur (Dockerized Rust backend)</b> and Vercel. Integrated <b>Circle's Compliance API</b> to automatically screen and block high-risk wallets.</li>
</ul>
</details>

<details>
<summary><b>💎 PrismDrop (Full-stack DApp)</b></summary>
<br/>
An efficient ERC-20 token distribution protocol built with Next.js 16, designed to batch-send tokens in a single transaction.
<ul>
    <li><b>Modern Stack:</b> Built with <b>Next.js 16 (App Router)</b>, <b>RainbowKit</b>, and <b>Wagmi v2</b> for a reactive and performant user experience.</li>
    <li><b>Smart Contract Integration:</b> Implemented seamless interaction with custom <code>TSender</code> contracts and standard ERC-20 functions (approve/allowance).</li>
    <li><b>Robust QA Strategy:</b> Solved complex dependency conflicts (Dependency Hell) to implement automated <b>E2E testing using Synpress v4 (Alpha) & Playwright</b>, ensuring reliability across wallet interactions.</li>
</ul>
</details>

<details>
<summary><b>💰 DeFi Stablecoin (Smart Contract Engineering)</b></summary>
<br/>
A decentralized, crypto-collateralized stablecoin protocol inspired by MakerDAO's architecture.
<ul>
    <li><b>Core Logic:</b> Developed core mechanics including collateral management (WETH/WBTC), minting/burning, and liquidation engines.</li>
    <li><b>Security & Testing:</b> Utilized <b>Foundry</b> for comprehensive unit tests and property-based fuzzing to maintain protocol invariants (e.g., overcollateralization).</li>
    <li><b>Oracle Integration:</b> Integrated Chainlink Price Feeds with a custom OracleLib to prevent stale price data and protect against bad debt.</li>
</ul>
</details>

<details>
<summary><b>🛡️ Bug Bounty Hunting (Security)</b></summary>
<br/>
Passionate about improving Web3 security through active participation in bug bounty programs.
<ul>
    <li><b>Track Record:</b> Identified and reported 5 vulnerabilities (3 critical) in the <b>Lido protocol</b> via Immunefi.</li>
    <li><b>Analysis:</b> specialized in root cause analysis, creating PoCs, and proposing mitigation strategies for complex DeFi protocols.</li>
</ul>
</details>

---

### 💻 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Web3 Frontend** | Next.js 16, React 19, TypeScript, Wagmi, Viem, RainbowKit, Tailwind CSS |
| **Smart Contract** | Solidity, Foundry, OpenZeppelin, Chainlink, Security Audits |
| **Backend & Indexing** | **Rindexer (Rust)**, Node.js, PostgreSQL, GraphQL |
| **DevOps & QA** | Docker, **Zeabur**, Vercel, Synpress, Playwright, CI/CD (GitHub Actions) |
