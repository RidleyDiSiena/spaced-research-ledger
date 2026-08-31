# Post-Quantum Mathematics

A survey of the layer underneath the migration. A companion collection, [Post-Quantum Cryptography Migration](../post-quantum-cryptography/), covers the deployment of the new algorithms across real systems. This one covers where those algorithms come from, who is choosing them, what the alternatives are, and what is being broken.

The distinction is practical. Anyone deploying the new cryptography needs to know that ML-KEM is the standard. Anyone deciding what to deploy for the next twenty years needs more: two European governments recommend an algorithm NIST rejected, a fifth NIST algorithm was selected but never written up, and one candidate signature scheme was withdrawn in July 2026 after an AI-assisted attack halved its security margin.

The collection has five parts plus a reading guide. Every part stands on its own, and every statement carries a numbered citation to a public source.

**Start with the [Reading Guide](latest/00-reading-guide.pdf).** It explains the structure and summarizes every part.

Last updated: 2026-08-31

## Latest Edition

| Part | Report |
|---|---|
| — | [Reading Guide](latest/00-reading-guide.pdf) |
| 1 | [NIST Standards Track](latest/01-nist-standards-track.pdf) |
| 2 | [Non-NIST National & Regional Standards Tracks](latest/02-non-nist-national-regional-standards-tracks.pdf) |
| 3 | [Candidate Asymmetric Algorithms](latest/03-candidate-asymmetric-algorithms.pdf) |
| 4 | [Symmetric & Hash-Based Research](latest/04-symmetric-hash-based-research.pdf) |
| 5 | [Cryptanalysis of Candidate & Non-Ratified Schemes](latest/05-cryptanalysis-of-candidate-non-ratified-schemes.pdf) |

Parts 1 through 3 cover who is standardizing what, including the national tracks that diverge from NIST. Parts 4 and 5 cover the primitives underneath and the attacks against candidates still under evaluation.

## Change Reports

The `diffs/` folder carries reports on what changed since the previous edition. It is empty for this edition, which is the first for this topic.

## Archive

The `archive/` folder holds superseded editions and past change reports, in folders named by date. It is empty for this edition, which is the first for this topic.
