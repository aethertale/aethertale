# aethertale

**Security Researcher — Smart Contracts & Cross-Chain Bridges**

Independent security researcher focused on EVM smart contracts and cross-chain
bridge protocols. Evidence-first methodology: every finding ships with a runnable
proof-of-concept and an honest severity assessment — including honest negative
results.

---

### Focus
Solidity / EVM · cross-chain bridges · DeFi protocol logic · signature & replay flaws ·
upgradeable (UUPS/proxy) safety

### Tooling
Foundry (`forge` / `cast` / `anvil`) · Slither · Hardhat · fork & invariant testing

### Method
Map every external call and trust boundary → form a hypothesis → build a runnable
`forge test` PoC → validate → report with a concrete fix.

### Profiles
HackenProof — [@aethertale](https://hackenproof.com/hackers/aethertale)  
Immunefi — [@aethertale](https://immunefi.com/profile/aethertale)

---

### Recent work
*Private / pending coordinated disclosure — details on request.*

- **Cross-chain bridge audit** — permissionless out-of-order relay causing permanent
  deposit fund-lock (griefing); missing EIP-712 domain separation enabling
  cross-deployment signature replay; uninitialized UUPS implementation. All
  reproduced with Foundry PoCs.
- **Protocol reviews** — multiple engagements closed as no-finding after a full
  review, reported honestly rather than padded.

---

*Open to bridge lifecycle, economic-security, and smart-contract review engagements.*
