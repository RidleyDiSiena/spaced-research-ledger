# Digital Asset Cryptography

A survey of the quantum exposure of blockchain systems and the industry built on them. A companion collection, [Post-Quantum Cryptography Migration](../post-quantum-cryptography/), covers the migration of the cryptography that secures general digital infrastructure. This collection is deliberately kept on its own track, so that asset-specific claims, disputes, and vendor incentives never mix into the coverage of migration strategy elsewhere.

**This collection does not endorse any cryptocurrency, token, or digital asset, and nothing in it is investment advice.** It tracks the cryptography and the migration, not the merits of the assets. Several sources in this field sell quantum urgency alongside their research, and the reports identify them as vendors wherever they appear.

The reason to read it anyway is that this is one of the most instructive migrations in the whole post-quantum transition. The hash functions that give a blockchain its structure, the proof-of-work and the linking of blocks, are not the weak point: a quantum computer only modestly weakens hashing, and the ledger's integrity rests on it safely. The exposure sits in the digital signatures that control ownership, because every public key revealed on-chain is a key a future quantum computer could attack, and a public ledger preserves those keys forever. Fixing that means coordinating protocol changes, key rotation, and custody practice across systems that were designed never to change, with no administrator who can order the upgrade. Watching this industry work that problem, from contested Bitcoin proposals to Ethereum's staffed roadmap to custodians shipping tools ahead of any protocol fix, is a preview of the hard parts every long-lived infrastructure will face.

It is part of the same post-quantum migration as everything else in this ledger, and it should not be ignored.

The collection has five parts plus a reading guide. Every part stands on its own, and every statement carries a numbered citation to a public source. Disagreements between sources are reported, not resolved, and no exposure figure is given without its definition.

**Start with the [Reading Guide](latest/00-reading-guide.pdf).** It explains the structure and summarizes every part.

Last updated: 2026-08-31

## Latest Edition

| Part | Report |
|---|---|
| — | [Reading Guide](latest/00-reading-guide.pdf) |
| 1 | [ECC Attack Demonstrations & Resource Estimates](latest/01-ecc-attack-demonstrations-resource-estimates.pdf) |
| 2 | [Exposure & Migration Analytics](latest/02-exposure-migration-analytics.pdf) |
| 3 | [Protocol Proposals & Activation Politics](latest/03-protocol-proposals-activation-politics.pdf) |
| 4 | [Protocol Quantum Roadmap](latest/04-protocol-quantum-roadmap.pdf) |
| 5 | [Institutional Custody & Exchanges](latest/05-institutional-custody-exchanges.pdf) |

Part 1 covers what it would take to break the cryptography. Part 2 covers how much bitcoin is exposed and by whose definition. Parts 3 and 4 cover the protocol responses on Bitcoin and Ethereum. Part 5 covers the custodians who cannot wait for either.

## Change Reports

The `diffs/` folder carries reports on what changed since the previous edition. It is empty for this edition, which is the first for this topic; the change report from the collection's founding sweep lives in the archive.

## Archive

The `archive/` folder holds superseded editions and past change reports, in folders named by date.
