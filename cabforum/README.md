# CA/Browser Forum Tracker

The CA/Browser Forum decides what a publicly trusted certificate may contain, how its holder must be checked, and how long it may live. Its decisions reach almost every encrypted connection on the internet, and they are made in public by a body most people have never heard of. This collection follows that body and the four browser and operating system root programs that enforce its rules.

**One distinction governs this entire subject, and getting it wrong is the most common error in writing about the Forum.** A ballot that passes its vote is not yet a rule. Decisions move through five states: proposed, voting, adopted, published, and in force. A ballot that passes enters a thirty-day intellectual property review, and only after that does its text publish into a numbered version. A separate effective date, often a year or more later, decides when certificate authorities must actually comply. Three different true statements can therefore be made about the same ballot, and only one of them means anyone has to do anything. Every part of this collection states the stage, every time.

The reports are organized around that idea rather than around narrative. Where a requirement has a future effective date, the date is given. Where a ballot has passed but not published, it is described as adopted and not as a rule.

Every statement carries a numbered citation to a public source, and the sources are the Forum's own ballot pages and revision tables, the root programs' own policies, the mailing lists where this work is argued, and the incident bugs where certificate authorities are held to account. Where two sources disagree, the disagreement is reported rather than resolved. Where something was checked and genuinely not found, the collection says so, rather than leaving the absence silent.

Last updated: 2026-09-01

## Latest Edition

| Part | Report |
|---|---|
| — | [Reading Guide](latest/00-reading-guide.pdf) |
| 1 | [Server Certificate Working Group](latest/01-server-certificate-working-group.pdf) |
| 2 | [Code Signing Working Group](latest/02-code-signing-working-group.pdf) |
| 3 | [S/MIME Working Group](latest/03-smime-working-group.pdf) |
| 4 | [Public Trust Programs](latest/04-public-trust-programs.pdf) |
| 5 | [Revocation & Transparency](latest/05-revocation-and-transparency.pdf) |

Part 1 covers the busiest group, including the schedule now cutting certificate lifetimes toward 47 days by 2029. Part 2 covers software signing, and carries a warning about reading a standards body correctly, because two of the Forum's own pages disagree about which version is current. Part 3 covers email certificates, and is the one place in the Forum where post-quantum algorithms are already permitted. Part 4 covers the root programs that decide who is actually trusted, and which routinely demand more than the Forum does, earlier. Part 5 covers revocation, which is being replaced rather than repaired, and transparency, which is undergoing its first architectural change since it was standardized.

**Start with the [Reading Guide](latest/00-reading-guide.pdf).** It explains the five states, the ballot numbering, and what this collection does not cover.

## Change Reports

The `diffs/` folder carries reports on what changed since the previous edition. It is empty for this edition, which is the first for this topic. The change report from the founding sweep lives in the archive.

## Archive

The `archive/` folder holds superseded editions and past change reports, in folders named by date.
