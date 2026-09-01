<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="Spaced Research Ledger">
</picture>

Published research from the Spaced Research Ledger, an automated system that gathers claims from live public sources, checks each one against its origin, and records every disagreement instead of merging it. Every stage runs on a different AI model, drawn from four to seven systems across competing labs, so no single model both finds a claim and judges it.

These reports state what their sources say, with every statement cited. They take no editorial position, represent no government, company, or other organization, and endorse no product. The project has no sponsor and no commercial interest in anything it covers. It is published for anyone who finds it useful.

The Spaced Research Ledger is designed and maintained by Ridley DiSiena.

## Research Topics

| Topic | Description | Last updated |
|---|---|---|
| [Post-Quantum Cryptography Migration](post-quantum-cryptography/) | A nineteen-part survey of the replacement of the public-key cryptography that secures nearly all digital communication, from silicon to government policy. | 2026-08-31 |
| [Quantum Computing](quantum-computing/) | A ten-part survey of the machines themselves: the five competing hardware approaches, the error correction every one of them depends on, and the money, theory and contested claims around them. | 2026-08-30 |
| [Post-Quantum Mathematics](post-quantum-mathematics/) | A five-part survey of the layer underneath the migration: who is standardizing which algorithms, the national tracks that diverge from NIST, the alternatives held in reserve, and what is being broken. | 2026-08-31 |

## How This Repository Is Organized

Each topic has its own folder with the same shape:

- **`latest/`** holds the current final reports as PDFs. This is always the newest complete edition.
- **`diffs/`** holds change reports covering what moved since the previous edition. When all recent findings have been folded into the latest edition and no newer sweep has run, this folder is empty and past change reports live in the archive.
- **`archive/`** holds superseded editions and past change reports, in folders named by date.

Only finished PDFs are published here. The research pipeline, its data, and intermediate formats are maintained separately.
