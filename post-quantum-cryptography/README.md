# Post-Quantum Cryptography Migration

A survey of one large, slow-moving event: the replacement of the public-key cryptography that secures nearly all digital communication. Quantum computers, once large enough, will break the algorithms in use today. Standards bodies have chosen replacements, and deploying them now touches every layer of computing, from silicon to government policy.

The collection has nineteen parts plus a reading guide, ordered by dependency: hardware before the software built on it, software before the systems deployed on it, deployments before the rules that govern them. Every part stands on its own, and every statement carries a numbered citation to a public source.

**Start with the [Reading Guide](latest/00-reading-guide.pdf).** It explains the structure and summarizes every part.

Last updated: 2026-08-31

## Latest Edition

| Part | Report |
|---|---|
| — | [Reading Guide](latest/00-reading-guide.pdf) |
| 1 | [Hardware Acceleration & Silicon](latest/01-hardware-acceleration.pdf) |
| 2 | [Firmware & Root of Trust](latest/02-firmware-root-of-trust.pdf) |
| 3 | [Operating Systems & Endpoints](latest/03-operating-systems.pdf) |
| 4 | [Crypto Libraries & Providers](latest/04-crypto-libraries.pdf) |
| 5 | [HSMs, KMS & Key Management](latest/05-hsm-kms.pdf) |
| 6 | [Network & Transport Protocols](latest/06-network-transport.pdf) |
| 7 | [PKI, Certificates, Identity & Authentication](latest/07-pki-identity.pdf) |
| 8 | [Application Dev Stacks & Languages](latest/08-app-dev-stacks.pdf) |
| 9 | [Software Supply Chain](latest/09-software-supply-chain.pdf) |
| 10 | [Containers, Orchestration, Service Mesh](latest/10-containers-orchestration.pdf) |
| 11 | [Cloud Infrastructure](latest/11-cloud-infrastructure.pdf) |
| 12 | [Security & Network Appliances](latest/12-security-appliances.pdf) |
| 13 | [Enterprise Infrastructure & Storage](latest/13-enterprise-infra-storage.pdf) |
| 14 | [Enterprise Applications & Delivery](latest/14-enterprise-applications.pdf) |
| 15 | [Email & Messaging](latest/15-email-messaging.pdf) |
| 16 | [Enterprise IoT & OT](latest/16-iot-ot.pdf) |
| 17 | [Financial Messaging & Sector Rails](latest/17-financial-sector-rails.pdf) |
| 18 | [Developer & Migration Tooling](latest/18-migration-tooling.pdf) |
| 19 | [Governance, Mandates & Timelines](latest/19-governance-mandates.pdf) |

## Change Reports

The `diffs/` folder carries reports on what changed since the previous edition. It is currently empty: all findings through 2026-08-29 are folded into the edition above. Past change reports are in the archive.

## Archive

- [`archive/2026-08-29/`](archive/2026-08-29/) — change report for the 2026-08-29 research sweep, now folded into the latest edition.
