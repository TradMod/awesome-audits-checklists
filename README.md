# Awesome Audits Checklists

## 1. **General Smart Contract Security & Audit Checklists**
- [Solodit Checklist](https://solodit.cyfrin.io/checklist) — by Cyfrin  
  An actionable checklist for auditing and reviewing Solidity smart contracts.
- [Ultimate Security Checklist](https://www.beirao.xyz/blog/Security-checklist) — by Beirao  
  A comprehensive checklist covering all essential aspects of smart contract security.
- [Solcurity](https://github.com/transmissions11/solcurity) — by transmissions11  
  A curated list of security resources and best practices for Solidity developers.
- [General Audit Checklist](https://github.com/tamjid0x01/SmartContracts-audit-checklist) — by Tamjid  
  A general-purpose checklist for smart contract audits, covering common vulnerabilities.
- [SCSVS - Smart Contract Security Verification Standard](https://github.com/ComposableSecurity/SCSVS) — by Composable Security  
  A standardized framework for verifying the security of smart contracts.
- [Solidity Attack Vectors](https://github.com/Quillhash/Solidity-Attack-Vectors) — by Quillhash  
  A collection of known attack vectors specific to Solidity smart contracts.
- [Smart Contract Vulnerabilities](https://github.com/kadenzipfel/smart-contract-vulnerabilities) — by Kaden Zipfel  
  A categorized list of vulnerabilities found in Ethereum smart contracts.
- [Smart Contract Security (Rareskills)](https://www.rareskills.io/post/smart-contract-security) — by Rareskills  
  An in-depth article on smart contract security concepts and best practices.
- [Auditors Checklist](https://github.com/Cyfrin/audit-checklist?tab=readme-ov-file#acknowledgements) — by Cyfrin  
  Curated list of Checklists of different auditors.
- [Anti-Hack Checklist](https://github.com/Quillhash/DeFi-anti-hack-checklist) — by Quillhash  
  A checklist focused on preventing hacks in DeFi protocols.
- [Bug Report Submission Checklist](https://immunefisupport.zendesk.com/hc/en-us/articles/15427337783057-Bug-Report-Submission-Checklist) — by Immunefi  
  Guidelines for submitting effective and complete bug reports.
- [Pre-Audit Preparation](https://composable-security.com/blog/smart-contract-audit-the-best-tips-on-how-to-be-prepared-better/) — by Composable Security  
  Tips and steps to prepare your project for a successful smart contract audit.
- [Development Security Toolkit](https://github.com/nascentxyz/simple-security-toolkit?tab=readme-ov-file) — by Nascent  
  A toolkit of scripts and resources for enhancing security during smart contract development.


## 2. **Token Standards & Edge Cases**
### ERC20
- [Weird ERC20 Implementations](https://github.com/d-xo/weird-erc20) — by d-xo  
  A list of unusual or non-standard ERC20 token implementations.
### ERC721
- [Weird ERC721 Implementations](https://github.com/abarbatei/weird-erc721) — by Alin Barbat  
  Examples of non-standard and quirky ERC721 contracts.
- [ERC721 Security Thread](https://x.com/Olympix_ai/status/1757018050291761295) — by Olympix_ai (Twitter)  
  A Twitter thread discussing ERC721-specific security issues.
### ERC4626
- [ERC4626 Security Checklist](https://github.com/Solthodox/erc4626-checklist) — by Solthodox  
  A checklist for auditing ERC4626 (tokenized vault) contracts.
- [ERC4626 Rounding Issues](https://x.com/sammyaudits/status/1831615410573136327) — by Sammy Audits (Twitter)  
  A Twitter thread highlighting rounding errors in ERC4626 implementations.
### ERC4337 & Account Abstraction
- [ERC4337 Security Checklist](https://github.com/aviggiano/security/blob/main/audit-checklists/ERC-4337.md) — by Aviggiano  
  Security checklist for ERC4337 (account abstraction) contracts.
- [Account Abstraction (Mixbytes)](https://mixbytes.io/blog/account-abstraction#rec613585484) — by MixBytes  
  An article exploring security considerations for account abstraction.
- [Account Abstraction Audit Checklist (Slowmist)](https://slowmist.medium.com/slowmist-security-audit-checklist-for-account-abstraction-wallets-ed48fc10cdbc) — by Slowmist  
  Audit checklist for account abstraction wallets by Slowmist.
### General Token Security
- [Signatures (Coinmonks)](https://medium.com/coinmonks/ethereum-signatures-for-hackers-and-auditors-101-4da766cd6344) — by Coinmonks (Medium)  
  A beginner-friendly guide to Ethereum signatures and their security implications.

## 3. **DeFi Protocol Types**
### AMMs (Automated Market Makers)
- [AMM Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/amm.md) — by Decurity  
  A checklist for auditing AMM smart contracts.
- [AMM Vulnerabilities (Decurity)](https://blog.decurity.io/typical-vulnerabilities-in-amm-protocols-9006f7986ba0) — by Decurity  
  Overview of common vulnerabilities in AMM protocols.
### CDP (Collateralized Debt Positions) & Lending
- [CDP Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/cdp.md) — by Decurity  
  Checklist for auditing CDP and lending protocols.
- [CDP/Lending Vulnerabilities (Decurity)](https://blog.decurity.io/typical-vulnerabilities-in-lending-and-cdp-protocols-e778e540e215) — by Decurity  
  Discussion of vulnerabilities in lending and CDP systems.
### LSD (Liquid Staking Derivatives)
- [LSD Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/lsd.md) — by Decurity  
  Checklist for auditing LSD protocols.
- [LSDs (Mixbytes)](https://mixbytes.io/blog/liquid#rec621210033) — by MixBytes  
  Security analysis and best practices for liquid staking derivatives.
### LRTs (Liquid Restaking Tokens)
- [LRTs (Sigma Prime)](https://blog.sigmaprime.io/liquid-restaking.html) — by Sigma Prime  
  An article on security considerations for liquid restaking tokens.
### GMX (Perpetuals/Derivatives)
- [GMX Security Thread](https://x.com/0xOwenThurm/status/1719766038064087324) — by Owen Thurm (Twitter)  
  A Twitter thread discussing security issues in GMX and similar protocols.
### Liquidations
- [Liquidation Vulnerabilities](https://dacian.me/defi-liquidation-vulnerabilities) — by Dacian  
  Analysis of vulnerabilities in DeFi liquidation mechanisms.
### CLM (Concentrated Liquidity Managers)
- [CLM Vulnerabilities](https://dacian.me/concentrated-liquidity-manager-vulnerabilities) — by Dacian  
  Security issues and risks in concentrated liquidity managers.
### Slippage
- [Slippage Attacks](https://dacian.me/defi-slippage-attacks) — by Dacian  
  Explanation of slippage attacks in DeFi and how to prevent them.
### Precision Loss
- [Precision Loss Errors](https://dacian.me/precision-loss-errors) — by Dacian  
  Discussion of errors caused by precision loss in smart contracts.

## 4. **Oracles**
- [Chainlink Oracle Attacks](https://medium.com/cyfrin/chainlink-oracle-defi-attacks-93b6cb6541bf) — by Cyfrin  
  Article on past attacks and vulnerabilities involving Chainlink oracles.
- [Berachain Oracle Bugs](https://x.com/blckhv/status/1928502350999687388?t=sNBNAMdhhSp9TkSGLlvpzg&s=19) — by blckhv (Twitter)  
  Twitter thread detailing bugs found in Berachain's oracle implementation.

- [Chainlink VRF Security](https://docs.chain.link/vrf/v2/security) — by Chainlink  
  Official documentation on the security model of Chainlink's Verifiable Random Function.

## 5. **Bridges, Interoperability & Multichain**
- [Interoperability Protocol Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist) — by Windhustler  
  A checklist for securing interoperability protocols and cross-chain solutions.
- [Multichain Auditor](https://github.com/0xJuancito/multichain-auditor) — by 0xJuancito  
  A repository with resources and tools for auditing multichain protocols.
- [Cross-chain Bridge Security Checklist](https://github.com/spearbit/portfolio/blob/master/content/bridges/BridgeSecurityChecklist.md) — by Spearbit  
  Checklist for auditing the security of cross-chain bridges.

---

## 6. **Proxies & Upgradability**
- [Upgradable Patterns (YouTube)](https://www.youtube.com/watch?v=Zjj5lDmHlq8) — by Smart Contract Programmer  
  Video explaining common patterns for upgradable smart contracts.
- [Upgradable Contracts Twitter Thread](https://x.com/pashovkrum/status/1699407698750578765) — by Pashov Krum (Twitter)  
  Twitter thread discussing upgradability and proxy contract security.
- [UUPS Proxy Security](https://www.rareskills.io/post/uups-proxy) — by Rareskills  
  Article analyzing the security of UUPS proxy pattern in Solidity.

---

## 7. **Signature & Replay Attacks**
- [Signature Replay Attacks (Dacian)](https://dacian.me/signature-replay-attacks#cmb200fic000009jrbs2y2cnw) — by Dacian  
  In-depth explanation of signature replay attacks in smart contracts.
- [Signature Replay Attacks (General)](https://dacian.me/signature-replay-attacks) — by Dacian  
  General overview of replay attack vectors and prevention.

---

## 8. **Governance**
- [DAO Governance Attacks](https://dacian.me/dao-governance-defi-attacks) — by Dacian  
  Analysis of attacks and vulnerabilities in DAO governance mechanisms.

---

## 9. **Low-level Solidity & DevSecOps**
- [Solidity Inline Assembly Vulnerabilities](https://dacian.me/solidity-inline-assembly-vulnerabilities) — by Dacian  
  Security risks and pitfalls when using inline assembly in Solidity.
- [Solidity DevSecOps Standard](https://github.com/0xsomnus/Solidity-DevSecOps-Standard) — by 0xsomnus  
  DevSecOps best practices and standards for Solidity development.

---

## 10. **Platform-Specific Security**
### Solana
- [Solana Best Practices (Slowmist)](https://github.com/slowmist/solana-smart-contract-security-best-practices) — by Slowmist  
  Best practices for securing Solana smart contracts.
- [Solana Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/solana/index.html) — by Secure Contracts  
  Examples of security issues in Solana contracts.
- [Solana Advanced Security](https://substack.com/home/post/p-164534668) — by Substack Author (Anonymous)  
  Advanced security topics for Solana developers.
### Algorand
- [Algorand Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/algorand/index.html) — by Secure Contracts  
  Security pitfalls and real-world issues in Algorand contracts.
### Starknet (Cairo)
- [Starknet Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/cairo/index.html) — by Secure Contracts  
  Examples of vulnerabilities in Starknet (Cairo) contracts.
### Cosmos
- [Cosmos Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/cosmos/index.html) — by Secure Contracts  
  Security issues and case studies in Cosmos contracts.
### Substrate
- [Substrate Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/substrate/index.html) — by Secure Contracts  
  Security analysis of Substrate-based smart contracts.
### Ton
- [Ton Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/ton/index.html) — by Secure Contracts  
  Security vulnerabilities in TON smart contracts.
  - [Blast Integration Guide](https://nirlin-blast-bugs.notion.site/Blast-Integration-Bugs-Guide-131344ccd05642bdbb49d2026c3227cf) — by Nirlin  
  A guide to common bugs and integration pitfalls in Blast.

## 11. **Other/Uncategorized**
- [2020 Smart Contract Security Paper (arXiv)](https://arxiv.org/pdf/2008.04761) — by Nicola Atzei, Massimo Bartoletti, Tiziana Cimoli  
  Academic paper reviewing the state of smart contract security as of 2020.

## 12. **Miscellaneous/General Security Threads**
- [General Security Thread 1](https://x.com/0xOwenThurm/status/1664390438822789122) — by Owen Thurm (Twitter)  
  Twitter thread with general insights and tips on smart contract security.
