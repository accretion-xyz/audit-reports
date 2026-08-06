# Accretion — Public Solana Audit Reports

[Accretion](https://accretion.xyz) is a boutique security firm with an exclusive focus on the **Solana runtime**. We audit Solana programs — Anchor, Pinocchio, and native — and nothing else. Since January 2025, our full-time, Solana-only audit practice has reviewed 70+ protocols protecting over $3B in TVL, including Light Protocol, MetaDAO, marginfi, Sanctum, Ellipsis Labs, Realms, Metaplex, and the Solana Foundation.

This repository contains every audit report our clients have chosen to make public. Many engagements are private and not listed here.

**Looking for an audit?** Submit your protocol at [accretion.xyz](https://accretion.xyz) or email [contact@accretion.xyz](mailto:contact@accretion.xyz) — we respond within 24 hours. Typical lead time is 2–4 weeks, and every engagement includes six months of post-audit support with 24/7 emergency response for critical issues.

## Coverage

Our reports cover the full Solana attack surface: account validation, PDA derivation and seeds, CPI safety, arithmetic and rounding, oracle usage, token program interactions (SPL Token and Token-2022), upgrade authority and admin risk, and protocol-specific economic logic. We audit programs written with Anchor, [Pinocchio](https://github.com/anza-xyz/pinocchio), and raw `solana-program`.

## Published Reports

| ID | Protocol | Category | Framework | Date | Website | Report |
| --- | --- | --- | --- | --- | --- | --- |
| A24VAU1 | The Vault Directed Stake | Liquid staking | Anchor | 2024 | [thevault.finance](https://thevault.finance/) | [PDF](/2024-accretion-vault-audit-A24VAU1.pdf) |
| A24LIG1 | Light Protocol | ZK compression | Anchor | 2024 | [lightprotocol.com](https://lightprotocol.com/) | [PDF](/2024-accretion-light-updates-A24LIG1.pdf) |
| A25LIG1 | Light Protocol | ZK compression | Anchor | January 2025 | [lightprotocol.com](https://lightprotocol.com/) | [PDF](/2025-accretion-light-update-audit-A25LIG1.pdf) |
| A25MET1 | MetaDAO Launchpad | Governance / launchpad | Anchor | March 2025 | [metadao.fi](https://metadao.fi/) | [PDF](/2025-accretion-metadao-launchpad-audit-A25MET1.pdf) |
| A25BEA1 | Beans Dot Fun | Consumer | Anchor | March 2025 | [beans.fun](https://beans.fun/) | [PDF](/2025-accretion-beans-audit-A25BEA1.pdf) |
| A25MRG1 | marginfi | Lending | Anchor | April 2025 | [marginfi.com](https://www.marginfi.com/) | [PDF](/2025-accretion-mrgn-audit-A25MRG1.pdf) |
| A25LIG2 | Light Protocol (Batched Merkle Trees) | ZK compression | Anchor | April 2025 | [lightprotocol.com](https://lightprotocol.com/) | [PDF](/2025-accretion-light-batched-mt-audit-A25LIG2.pdf) |
| A25LIG3 | Light Protocol | ZK compression | Anchor / Pinocchio | May 2025 | [lightprotocol.com](https://lightprotocol.com/) | [PDF](/2025-accretion-light-pinocchio-audit-A25LIG3.pdf) |
| A25ELL1 | Ellipsis Plasma / Gavel | AMM (sandwich-resistant) | Native | May 2025 | [gavel.xyz](https://gavel.xyz/) | [PDF](/2025-accretion-ellipsis-plasma-audit-A25ELL1.pdf) |
| A25REA1 | Realms (Versioned Transactions) | Governance | Native | May 2025 | [realms.today](https://realms.today/) | [PDF](/2025-accretion-realms-versioned-transactions-audit-A25REA1.pdf) |
| A25ANA2 | Swig | Smart wallet | Pinocchio | June 2025 | [onswig.com](https://onswig.com/) | [PDF](/2025-accretion-anagram-swig-audit-A25ANA2.pdf) |
| A25MRG2 | Project 0 / mrgn (Kamino integration) | Lending | Anchor | June 2025 | [0.xyz](https://www.0.xyz/) | [PDF](/2025-accretion-mrgn-kamino-audit-A25MRG2.pdf) |
| A25MET2 | MetaDAO Squads Integration | Governance / treasury | Anchor | July 2025 | [metadao.fi](https://metadao.fi/) | [PDF](/2025-accretion-metadao-squads-treasury-audit-A25MET2.pdf) |
| A25PRC1 | Privacy Cash | ZK privacy | Anchor | July 2025 | [privacycash.org](https://www.privacycash.org/) | [PDF](/2025-accretion-privacy-cash-audit-A25PRC1.pdf) |
| A25MET3 | MetaDAO Price-Based Token Unlocks | Governance / launchpad | Anchor | September 2025 | [metadao.fi](https://metadao.fi/) | [PDF](/2025-accretion-metadao-price-based-token-lock-audit-A25MET3.pdf) |
| A25SAN1 | Sanctum Jiminy, Token Ratio, FlatSlab | Liquid staking (LST) | Jiminy | September 2025 | [sanctum.so](https://sanctum.so/) | [PDF](/2025-accretion-sanctum-flat-slab-jiminy-token-ratio-audit-A25SAN1.pdf) |
| A25MRG3 | Project 0 / mrgn (Drift & Solend integration) | Lending | Anchor | September 2025 | [0.xyz](https://www.0.xyz/) | [PDF](/2025-accretion-marginfi-drift-solend-integration-audit-A25MRG3.pdf) |
| A25REA2 | Realms Metaplex Core NFT Plugin | Governance / NFT | Anchor | September 2025 | [realms.today](https://realms.today/) | [PDF](/2025-accretion-realms-metaplex-nft-core-plugin-audit-A25REA2.pdf) |
| A25HYL1 | Hylo | Stablecoin / leverage | Anchor | December 2025 | [hylo.so](https://hylo.so/) | [PDF](/2025-accretion-hylo-hylo-audit-A25HYL1.pdf) |
| A25PRC2 | Privacy Cash SPL Token | ZK privacy | Anchor | December 2025 | [privacycash.org](https://www.privacycash.org/) | [PDF](/2025-accretion-socialfi-privacy-cash-spl-token-audit-A25PRC2.pdf) |
| A26SFR1 | Lazorkit | Passkey wallet | Pinocchio | January 2026 | [github.com/lazor-kit](https://github.com/lazor-kit) | [PDF](/2026-accretion-solana-foundation-lazorkit-audit-A26SFR1.pdf) |
| A25SFR2 | Solana Token ACL | Token infrastructure | Native | January 2026 | [solana-foundation/token-acl](https://github.com/solana-foundation/token-acl) | [PDF](/2025-accretion-solana-token-acl-audit-A25SFR2.pdf) |
| A25TES1 | Tessera Token & Referral | Token / referral | Anchor | January 2026 | [tessera.pe](https://www.tessera.pe/) | [PDF](/2025-accretion-tessera-token-and-referral-audit-A25TES1.pdf) |
| A25MAT1 | Matrixdock XAUm RWA Contracts | RWA (tokenized gold) | Anchor | January 2026 | [matrixdock.com/xaum](https://www.matrixdock.com/xaum) | [PDF](/2025-accretion-matrixdock-RWA-contracts-audit-A25MAT1.pdf) |
| A26MET1 | MetaDAO (Full Audit) | Governance / futarchy | Anchor | February 2026 | [metadao.fi](https://metadao.fi) | [PDF](/2026-accretion-metadao-metadao-full-audit-audit-A26MET1.pdf) |
| A26SFR2 | Solana Keychain | Key management | Rust / TypeScript | February 2026 | [solana-foundation/solana-keychain](https://github.com/solana-foundation/solana-keychain/) | [PDF](/2026-accretion-solana-foundation-solana-keychain-audit-A26SFR2.pdf) |
| A25SFR4 | Solana Token ACL Gate | Token infrastructure | Pinocchio | February 2026 | [solana-foundation/token-acl-gate](https://github.com/solana-foundation/token-acl-gate) | [PDF](/2025-accretion-solana-token-acl-gate-audit-A25SFR4.pdf) |
| A25SAN2 | Sanctum INF V2 | Liquid staking (LST) | Jiminy | February 2026 | [sanctum.so](https://sanctum.so/) | [PDF](/2025-accretion-sanctum-inf-v2-audit-A25SAN2.pdf) |
| A26HTO1 | RevTec V2 | DePIN | Anchor | March 2026 | [revtec.fi](https://revtec.fi/) | [PDF](/2026-accretion-h2o-nodes-gmbh-revtec-audit-A26HTO1.pdf) |
| A25LIG5 | Light Protocol Compressed Token Program V2 | ZK compression | Pinocchio | March 2026 | [lightprotocol.com](https://lightprotocol.com/) | [PDF](/2025-accretion-light-compressed-token-program-v2-audit-A25LIG5.pdf) |
| A26SFR3 | Solana Foundation Escrow | Token infrastructure | Pinocchio | April 2026 | [solana-program/escrow](https://github.com/solana-program/escrow) | [PDF](/2026-accretion-solana-foundation-escrow-audit-A26SFR3.pdf) |
| A26YOL1 | YO Protocol | Yield aggregator | Anchor | April 2026 | [yo.xyz](https://www.yo.xyz/) | [PDF](/2026-accretion-yo-labs-yo-protocol-solana-audit-A26YOL1.pdf) |
| A26MAN1 | Manifest Destiny | Orderbook DEX | Pinocchio | May 2026 | [manifest.trade](https://www.manifest.trade/) | [PDF](/2026-accretion-manifest-destiny-audit-A26MAN1.pdf) |
| A26EXP1 | Exponent Tranching | Fixed yield / tranching | Anchor | May 2026 | [exponent.finance](https://www.exponent.finance/) | [PDF](/2026-accretion-exponent-finance-exponent-tranching-audit-A26EXP1.pdf) |
| A26SFR4 | Solana Foundation Token ACL Gate Updates | Token infrastructure | Pinocchio | June 2026 | [solana-foundation/token-acl-gate](https://github.com/solana-foundation/token-acl-gate) | [PDF](/2026-accretion-solana-foundation-token-acl-gate-updates-audit-A26SFR4.pdf) |
| A26HYL1 | Hylo V2 Exchange, Earn Pool & Router | Stablecoin / leverage | Anchor | July 2026 | [hylo.so](https://hylo.so/) | [PDF](/2026-accretion-hylo-protocol-v2-audit-A26HYL1.pdf) |

## Report IDs

Each report has a stable ID of the form `A<YY><CLIENT><N>` — audit year, client code, and engagement number. Repeat IDs across years (e.g. `A25LIG1` … `A25LIG5`) indicate long-term engagements: several of our clients, including Light Protocol and MetaDAO, have returned for four or more audits.

## About Accretion

- **Website:** [accretion.xyz](https://accretion.xyz)
- **Research blog:** [accretion.xyz/blog](https://accretion.xyz/blog) — Solana security research, new bug classes, and field guides
- **X / Twitter:** [@accretion_xyz](https://x.com/accretion_xyz)
- **Tooling:** [Solana Data Reverser](https://github.com/accretion-xyz/solana-data-reverser) — reverse engineer Solana account data without source code
- **Contact:** [contact@accretion.xyz](mailto:contact@accretion.xyz)

Our researchers have prevented 50+ critical exploits across the Solana ecosystem. We regularly discover vulnerabilities in previously audited protocols and publish new bug classes to raise the ecosystem's security bar.
