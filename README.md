# Awesome Audits Checklists

> NOTE: All the resources in this repo are for educational purposes only and have been curated especially for developers and auditors. Developers should use them to build more secure applications. Auditors should benefit from these resources as well, using them to learn and secure systems but they should not [rely](https://x.com/TheTradMod/status/1941314119090446734) solely on checklists. Auditors should always adapt checklists to their specific context and prioritize a deep understanding of systems and security principles over rigid reliance on lists. This repository is a community effort, a collection of humble contributions from security researchers around the world. Thanks and respect to everyone who shares their knowledge to help make blockchain applications safer for all.


### Table of Contents
- [General Smart Contract Security & Audit Checklists](#1-general-smart-contracts-security--audit-checklists)
- [ERC Standards & Edge Cases](#2-erc-standards--edge-cases)
- [Bridges, Interoperability & Multichain](#3-bridges-interoperability--multichain)
- [DeFi Protocols](#4-defi-protocols)
- [Protocols Integration Security](#5-protocols-integration-security)
- [Proxies & Upgradability](#6-proxies--upgradability)
- [Signature Attacks](#7-signature-attacks)
- [Governance](#8-governance)
- [Chains Specific Security](#9-chains-specific-security)
- [Wallets Security](#10-wallets-security)
- [Other/Uncategorized](#11-otheruncategorized)
- [Support](#support)
- [Contribution](#contribution)

## 1. **General Smart Contracts Security & Audit Checklists**
- [Solodit Checklist](https://solodit.cyfrin.io/checklist) — by Cyfrin  
  An actionable checklist for auditing and reviewing Solidity smart contracts.
- [Ultimate Security Checklist](https://www.beirao.xyz/blog/Security-checklist) — by Beirao  
  A comprehensive checklist covering all essential aspects of smart contract security.
- [General Audit Checklist](https://github.com/tamjid0x01/SmartContracts-audit-checklist) — by Tamjid  
  A general-purpose checklist for smart contract audits, covering common vulnerabilities.
- [SCSVS - Smart Contract Security Verification Standard](https://github.com/ComposableSecurity/SCSVS) — by Composable Security  
  A standardized framework for verifying the security of smart contracts.
- [Smart Contract Security](https://www.rareskills.io/post/smart-contract-security) — by Rareskills  
  An in-depth article on smart contract security concepts and best practices.
- [Auditors Checklist](https://github.com/Cyfrin/audit-checklist?tab=readme-ov-file#acknowledgements) — by Cyfrin  
  Curated list of audit checklists of different auditors.
- [Pre-Audit Preparation](https://composable-security.com/blog/smart-contract-audit-the-best-tips-on-how-to-be-prepared-better/) — by Composable Security  
  Tips and steps to prepare your project for a successful smart contract audit.
- [Development Security Toolkit](https://github.com/nascentxyz/simple-security-toolkit?tab=readme-ov-file) — by Nascent  
  A toolkit of scripts, resources and checklists for enhancing security during smart contract development.
  - [Multisig Security Best Practices](https://www.youtube.com/watch?v=lHk_RDzvKCc) — by Mudit Gupta  
  Video guide covering security best practices for implementing and managing multi-signature wallets and governance systems.
- [Bug Report Submission Checklist](https://immunefisupport.zendesk.com/hc/en-us/articles/15427337783057-Bug-Report-Submission-Checklist) — by Immunefi  
  Guidelines for submitting effective and complete bug reports.
- [Anti-Hack Checklist](https://github.com/Quillhash/DeFi-anti-hack-checklist) — by QuillAudits  
  A checklist focused on preventing hacks in DeFi protocols.
- [Crisis Handbook - Smart Contract Hack](https://docs.google.com/document/d/1DaAiuGFkMEMMiIuvqhePL5aDFGHJ9Ya6D04rdaldqC0/edit?tab=t.0) - SEAL  
  A Checklist to follow when protocols get hacked and handle smart contracts hack crisis.
- [Practical Security Measures for Web3 Founders](https://www.youtube.com/watch?v=Wa--zO509bA) - Mehdi  SigmaPrime    
  This is a must watch and practical measures to take for every Web3 founders, developers & researchers.

## 2. **ERC Standards & Edge Cases**
### ERC20
- [Weird ERC20 Implementations](https://github.com/d-xo/weird-erc20) — by d-xo  
  A list of unusual or non-standard ERC20 token implementations.
### ERC721
- [Weird ERC721 Implementations](https://github.com/abarbatei/weird-erc721) — by ABA  
  Examples of non-standard and quirky ERC721 contracts.
- [ERC721 Security Thread](https://x.com/Olympix_ai/status/1757018050291761295) — by Olympix  
  A Twitter thread discussing ERC721-specific security issues.
### ERC4626
- [ERC4626 Security Checklist](https://github.com/Solthodox/erc4626-checklist) — by Solthodox  
  A checklist for auditing ERC4626 (tokenized vault) contracts.
- [ERC4626 Rounding Issues](https://x.com/sammyaudits/status/1831615410573136327) — by Sammy  
  A Twitter thread highlighting rounding errors in ERC4626 implementations.
- [ERC4626 Vault Security Primer](https://github.com/devdacian/ai-auditor-primers/blob/main/primers/amy.vault.erc4626.primer.md) — by DevDacian    
  Biggest ERC4626 checklist. More than 350 direct vulnerabilities, many pitfalls, integration errors and more.
### ERC4337 & Account Abstraction
- [ERC4337 Security Checklist](https://github.com/aviggiano/security/blob/main/audit-checklists/ERC-4337.md) — by Aviggiano  
  Security checklist for ERC4337 (account abstraction) contracts.

## 3. **Core Blockchain, Node & Infra**
- [Core Node Security Guide](https://blog.sigmaprime.io/core-node-security.html) — by Sigma Prime  
  A comprehensive security engineer's guide to reviewing core blockchain nodes, covering systematic approaches to conducting thorough security reviews of blockchain node implementations like Reth.
- [Blockchain Security Thread](https://x.com/Designer_Misbah/status/1953906761871626751) — by Misbah  
  Twitter thread covering general blockchain security considerations and best practices.  

## 3. **Bridges, Interoperability & Multichain**
- [Interoperability Protocol Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist) — by Windhustler  
  A checklist for securing interoperability protocols LyerZero, CCIP, Wormhole etc and cross-chain solutions.
- [Multichain Auditor](https://github.com/0xJuancito/multichain-auditor) — by 0xJuancito  
  A repository with resources and tools for auditing multichain protocols.
- [Cross-chain Bridge Security Checklist](https://github.com/spearbit/portfolio/blob/master/content/bridges/BridgeSecurityChecklist.md) — by Spearbit  
  Checklist for auditing the security of cross-chain bridges.
- [Blockchain Bridge Vulnerabilities](https://github.com/the-caliber/Blockchain-bridge-vulnerabilities) — by the-caliber  
  Repository documenting various blockchain bridge vulnerabilities and security considerations for cross-chain bridge implementations.
- [LayerZero Security Research](https://lab.guardianaudits.com/encyclopedia-of-security-research/layerzero) — by Guardian Audits  
  Encyclopedia entry covering LayerZero protocol security research, vulnerabilities, and integration considerations.

## 4. **DeFi Protocols**
- [AMM Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/amm.md) — by Decurity  
  A checklist for auditing AMM smart contracts.
- [AMM Security & Audit Insights](https://mirror.xyz/millietez.eth/ixD3xe-Q7JQowYcIFmGKxkPae_C5tCN9kWn9jXUhnKk) — by Millie Tez
  An in-depth article on security considerations and audit tips for Automated Market Maker protocols.
- [CDP Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/cdp.md) — by Decurity  
  Checklist for auditing Collateralized Debt Positions.
- [LSD Audit Checklist](https://github.com/Decurity/audit-checklists/blob/master/lsd.md) — by Decurity  
  Checklist for auditing LSD protocols.
- [Guidelines for Auditing Staking Protocols](https://defihacklabs.substack.com/p/solidity-security-lesson-3-guidelines) - QuillAudits  
- Useful reference for auditing staking protocols and can help you identify potential bugs.
- [LSDs Best Practices](https://mixbytes.io/blog/liquid#rec621210033) — by MixBytes  
  Security analysis and best practices for liquid staking derivatives.
- [Liquid Restaking Tokens](https://blog.sigmaprime.io/liquid-restaking.html) — by Sigma Prime  
  An article on security considerations for liquid restaking tokens (LRTs).
- [Liquidation Vulnerabilities](https://dacian.me/defi-liquidation-vulnerabilities) — by Dacian  
  Analysis of vulnerabilities in DeFi liquidation mechanisms.
- [CLM Vulnerabilities](https://dacian.me/concentrated-liquidity-manager-vulnerabilities) — by Dacian  
  Security issues and risks in concentrated liquidity managers.
- [Slippage Attacks](https://dacian.me/defi-slippage-attacks) — by Dacian  
  Explanation of slippage attacks in DeFi and how to prevent them.
- [Precision Loss Errors](https://dacian.me/precision-loss-errors) — by Dacian  
  Discussion of errors caused by precision loss in smart contracts.

## 5. **Protocols Integration Security**
- [External Integrations: The Hidden Risk in Smart Contracts](https://x.com/0xCharlesWang/status/1931486275707830730) - by CharlesWang
- General External Integration Best practices and security risks.
- [Across V3 Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist/blob/main/audit-checklists/Across.md) — by TradMod (ABDul Rehman)  
  A detailed checklist for auditing the security of Across V3 cross-chain messaging protocol integrations.
- [LayerZero V2 Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist/blob/main/audit-checklists/LayerZeroV2.md) — by windhustler  
  A detailed checklist for auditing the security of LayerZero V2 cross-chain messaging protocol integrations.
- [Wormhole Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist/blob/main/audit-checklists/Wormhole.md) — by windhustler  
  A comprehensive audit checklist for Wormhole bridge integrations, highlighting key risks and best practices.
- [Chainlink CCIP Security Checklist](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist/blob/main/audit-checklists/Chainlink-CCIP.md) — by windhustler  
  A thorough checklist for reviewing and securing Chainlink CCIP (Cross-Chain Interoperability Protocol) implementations.
- [Berachain Oracle Bugs](https://x.com/blckhv/status/1928502350999687388?t=sNBNAMdhhSp9TkSGLlvpzg&s=19) — by blckhv  
  Twitter thread detailing bugs found in Berachain's oracle implementation.
- [Stargate v2 Integration Checklist](https://mirror.xyz/0xaeDAA951e7fbe1031E3553a7a8b1d8A89b132d7b/WfZ1ewSlkbErd-swiBV0AGbQ0xEWdnq6nCzDNStDUKI) — by EngimaDark/Windhustler  
  Secruity Checklist for for Stargate V2 contracts integrations.
### UniswapV4 Hooks Integration Guides
- [Questions To Ask Before Writing a Uniswap v4 Hook](https://blog.openzeppelin.com/6-questions-to-ask-before-writing-a-uniswap-v4-hook) - by OpenZeppelin  
  This guide outlines some key considerations when designing a UniswapV4 hook to suit your specific needs.
- [Uniswap V4 Hooks Security Talk](https://www.youtube.com/watch?v=Fbxsv8rxHZw) — by Damian (Composable Security)  
  A detailed presentation on Uniswap V4's architecture and the main security threats and best practices when building custom hooks.
- [Uniswap V4 Hooks Security Deep Dive](https://www.youtube.com/watch?v=4o8yGcq6tfM) — by Jota Carpanelli (OpenZeppelin)  
  A technical walkthrough of Uniswap V4 hooks, including how to build, test, and secure custom hooks.
- [Auditing Uniswap V4 Hooks](https://hacken.io/discover/auditing-uniswap-v4-hooks/) — by Hacken  
  An article outlining the main audit considerations, attack vectors, and recommendations for Uniswap V4 hook integrations.
- [Uniswap V4 Hooks Security Considerations](https://www.quillaudits.com/blog/web3-security/uniswap-v4-security-considerations) — by QuillAudits  
  A breakdown of the new security challenges and mitigation strategies for Uniswap V4 and its hooks.
- [Uniswap V4 Hooks Integration Security Considerations](https://www.certik.com/resources/blog/uniswap-v4-hooks-security-considerations) — by CertiK  
  A blog post analyzing the unique security risks introduced by hooks in Uniswap V4 and how to address them.
- [Uniswap V3/V4 Security](https://lab.guardianaudits.com/encyclopedia-of-security-research/uniswap) — by Guardian Audits  
  Comprehensive security research and analysis of Uniswap V3 and V4 protocols, covering integration risks and security considerations.

## 6. **Proxies & Upgradability**
- [Upgradable Patterns](https://www.youtube.com/watch?v=Zjj5lDmHlq8) — by Daniel Von Fange  
  Video explaining common patterns for upgradable smart contracts.
- [Upgradable Contracts Twitter Thread](https://x.com/pashovkrum/status/1699407698750578765) — by Pashov Krum  
  Twitter thread discussing upgradability and proxy contract security.
- [UUPS Proxy Security](https://www.rareskills.io/post/uups-proxy) — by Rareskills  
  Article analyzing the security of UUPS proxy pattern in Solidity.

## 7. **Signature Attacks**
- [Signature Replay Attacks](https://dacian.me/signature-replay-attacks#cmb200fic000009jrbs2y2cnw) — by Dacian  
  In-depth explanation of signature replay attacks in smart contracts.
- [Signatures](https://medium.com/coinmonks/ethereum-signatures-for-hackers-and-auditors-101-4da766cd6344) — by Coinmonks (Medium)  
  A beginner-friendly guide to Ethereum signatures and their security implications.
- [Signature Replays](https://dacian.me/signature-replay-attacks) — by Dacian  
  General overview of replay attack vectors and prevention.

## 8. **Governance**
- [DAO Governance Attacks](https://dacian.me/dao-governance-defi-attacks) — by Dacian  
  Analysis of attacks and vulnerabilities in DAO governance mechanisms.
- [DAO Governance Security](https://blog.sigmaprime.io/governance-dao.html) — by Sigma Prime  
  Common vulnerabilities in protocol governance and DAOs, covering reentrancy, insider threats, flash loan voting, proposal execution issues, and other governance-specific attack vectors.

## 9. **Chains Specific Security**
- [Multichain Auditor](https://github.com/0xJuancito/multichain-auditor) — by 0xJuancito  
  A repository with resources and tools for auditing multichain protocols.
### Solana
- [Solana Program Security Guide](https://www.helius.dev/blog/a-hitchhikers-guide-to-solana-program-security) — by Helius  
  A comprehensive hitchhiker's guide to Solana program security covering common vulnerabilities, attack vectors, and mitigation strategies for intermediate/advanced developers building on Solana.
- [Solana Best Practices](https://github.com/slowmist/solana-smart-contract-security-best-practices) — by Slowmist  
  Best practices for securing Solana smart contracts.
- [SPL Token-2022](https://neodyme.io/en/blog/token-2022/#tldr) - by Neodyme  
  Potential security pitfalls and best practices for secure implementation of the new Solana SPL token extensions. 
- [Solana Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/solana/index.html) — by ToB Secure Contracts  
  Examples of security issues in Solana contracts.
- [Solana Advanced Security](https://substack.com/home/post/p-164534668) — by Nirlin  
  Advanced security topics for Solana developers.
### Arbitrum
- [Arbitrum Integration Bugs](https://github.com/windhustler/Interoperability-Protocol-Security-Checklist/blob/main/audit-checklists/Arbitrum.md) — by Windhustler  
  Arbitrum Security pitfalls and integration guide.
### Algorand
- [Algorand Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/algorand/index.html) — by ToB Secure Contracts  
  Security pitfalls and real-world issues in Algorand contracts.
### Starknet (Cairo)
- [Starknet Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/cairo/index.html) — by ToB Secure Contracts  
  Examples of vulnerabilities in Starknet (Cairo) contracts.
### Cosmos
- [Cosmos Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/cosmos/index.html) — by ToB Secure Contracts  
  Security issues and case studies in Cosmos contracts.
### Substrate
- [Substrate Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/substrate/index.html) — by ToB Secure Contracts  
  Security analysis of Substrate-based smart contracts.
### Ton
- [Ton Not-So-Smart Contracts](https://secure-contracts.com/not-so-smart-contracts/ton/index.html) — by ToB Secure Contracts  
  Security vulnerabilities in TON smart contracts.
- [Ton Security Checklists](https://github.com/PositiveSecurity/ton-audit-guide) — by PositiveSecurity  
  Checklist for Auditing TON Smart Contracts
### Tron
- [Checklist for Auditing Tron Projects](https://github.com/PositiveSecurity/tron-audit-guide) — by PositiveSecurity  
  A guide to common bugs and integration pitfalls in Tron Contracts.
### Blast
- [Blast Integration Guide](https://nirlin-blast-bugs.notion.site/Blast-Integration-Bugs-Guide-131344ccd05642bdbb49d2026c3227cf) — by Nirlin  
  A guide to common bugs and integration pitfalls in Blast.
### Near
- [Near Smart Contracts Checklist](https://docs.near.org/smart-contracts/security/checklist) — Near Docs  
  Near smart contracts security considerations list 
### Binance Chain
- [BNB Chain Security Tips](https://cantina.xyz/blog/bnb-chain-security-tips) — by Cantina  
  Top 15 security recommendations for BNB Chain developers covering vulnerability patterns, exploit defenses, and secure engineering practices specific to BNB Chain development.

## 10. **Wallets Security**
- [Web3 Wallet Security Checklist](https://blockapex.io/web3-wallet-security-checklist/) — by BlockApex  
  A practical checklist covering best practices for securing Web3 wallets.
- [All Wallet Security Checklist](https://www.slowmist.com/service-wallet-security-audit.html) — by SlowMist  
  A comprehensive checklist for auditing and securing various types of crypto wallets.
- [Account Abstraction](https://mixbytes.io/blog/account-abstraction#rec613585484) — by MixBytes  
  An article exploring security considerations for account abstraction.
- [Account Abstraction Audit Checklist](https://slowmist.medium.com/slowmist-security-audit-checklist-for-account-abstraction-wallets-ed48fc10cdbc) — by Slowmist  
  Audit checklist for account abstraction wallets.
- [Crypto Wallet Security Assessment Checklist ](https://www.certik.com/resources/blog/cryptowalletsecurityassessmentchecklist) — by Certik    
  A checklist outlining key steps and best practices for assessing the security of crypto wallets.
- [Web3 Wallet Security Checklist](https://blockapex.io/web3-wallet-security-checklist/) — by BlockApex  
  A practical checklist covering best practices for securing Web3 wallets and wallet security assessment methodologies.

## 11. **Other/Uncategorized**
- [Oracle Security Thread](https://x.com/0xjmaria/status/1939980905453367761) — by @0xjmaria  
  Twitter thread detailing oracle-specific security considerations and vulnerabilities.
- [Oracles and Pricing Security](https://blog.sigmaprime.io/oracles-and-pricing.html) — by Sigma Prime  
  Comprehensive guide to common vulnerabilities in oracles and pricing feeds, covering spot pricing attacks, homegrown oracle issues, time delays, gas congestion, and price manipulation techniques.
- [Solidity Gas Optimizations](https://github.com/TechnoGeek01/solidity-gas-optimizations) — by TechnoGeek01  
  A curated list of gas-saving techniques and best practices for Solidity smart contract development.
- [2020 Smart Contract Security Paper](https://arxiv.org/pdf/2008.04761) — by Nicola arXiv  
  Academic paper reviewing the state of smart contract security as of 2020.
- [Chainlink Oracle Attacks](https://medium.com/cyfrin/chainlink-oracle-defi-attacks-93b6cb6541bf) — by Cyfrin  
  Article on past attacks and vulnerabilities involving Chainlink oracles.
- [Chainlink VRF Security](https://docs.chain.link/vrf/v2/security) — by Chainlink  
  Official documentation on the security model of Chainlink's Verifiable Random Function.
- [SWC Registry](https://swcregistry.io) — by SWC Registry  
  A comprehensive database of known smart contract vulnerabilities, each with a unique identifier and detailed description.
- [Solidity Inline Assembly Vulnerabilities](https://dacian.me/solidity-inline-assembly-vulnerabilities) — by Dacian  
  Security risks and pitfalls when using inline assembly in Solidity.
- [Solidity DevSecOps Standard](https://github.com/0xsomnus/Solidity-DevSecOps-Standard) — by 0xsomnus  
  DevSecOps best practices and standards for Solidity development.
- [How To Multisig](https://howtomultisig.com/) - SEAL/fredrik  
  Best practices on how to implement secure standard operation procedures for multisigs.

- [CREATE/CREATE2 Security Pitfalls](https://mixbytes.io/blog/pitfalls-of-using-cteate-cteate2-and-extcodesize-opcodes) — by MixBytes  
  Analysis of security pitfalls when using CREATE, CREATE2, and EXTCODESIZE opcodes in smart contract development.

- [EIP-7702 Security Considerations](https://www.youtube.com/watch?v=ZFN2bYt9gNE) — by Tincho/Red Guild
  Video discussion on security implications and considerations for EIP-7702 implementation.

## Support
If you want to support this repo and its contributors, you can do it on the [Terminal](https://terminal.merit.systems/TradMod/awesome-audits-checklists). Thanks!

## Contribution
If you'd like to contribute reach out on [X](https://x.com/TheTradMod), or Simply create a PR anon :)