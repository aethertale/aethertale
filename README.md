### Security Researcher — Smart Contracts & Cross-Chain Bridges

Independent security researcher focused on EVM smart contracts and cross-chain bridge protocols. Evidence-first methodology: every finding ships with a runnable proof-of-concept and an honest severity assessment — including honest negative results.

- 🔭 **Focus:** Solidity / EVM · cross-chain bridges · DeFi protocol logic · signature & replay flaws · upgradeable (UUPS/proxy) safety
- 🛠️ **Tooling:** Foundry (forge/cast/anvil) · Slither · Hardhat · fork & invariant testing
- 🧪 **Method:** map every external call & trust boundary → hypothesize → build a runnable `forge test` PoC → validate → report with a concrete fix
- 🏷️ **Profiles:** HackenProof [`@aethertale`](https://hackenproof.com/hackers/aethertale) · Immunefi `@aethertale`
- 📫 **Engagements:** private bug-bounty & audit work available for review under NDA

---

**Recent work** (private / pending coordinated disclosure — details on request):
- Cross-chain bridge audit: permissionless out-of-order relay causing permanent deposit fund-lock (griefing), missing EIP-712 domain separation enabling cross-deployment signature replay, and an uninitialized UUPS implementation — all reproduced with Foundry PoCs.
- Multiple protocol reviews closed as no-finding after full audit — reported honestly rather than padded.

*Interested in bridge lifecycle, economic-security, and smart-contract review engagements.*
