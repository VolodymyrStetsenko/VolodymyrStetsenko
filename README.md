<div align="center">
  <a href="https://github.com/VolodymyrStetsenko">
    <img src="https://raw.githubusercontent.com/VolodymyrStetsenko/VolodymyrStetsenko/main/baner.png" alt="Volodymyr Stetsenko — Web3 Security Research" width="100%">
  </a>

  <h1>Volodymyr Stetsenko</h1>
  <p><strong>Web3 Security Researcher · Exploit-Chain Analysis · On-chain Evidence</strong></p>

  <p>
    I reconstruct how Web3 systems fail across code, privileged control, infrastructure,
    and on-chain fund flows — then turn the evidence into reproducible labs and actionable security controls.
  </p>

  <p>
    <a href="https://github.com/VolodymyrStetsenko/SECURITY-REVIEW"><strong>Research Library</strong></a>
    ·
    <a href="https://github.com/VolodymyrStetsenko/SecureVault-Foundry"><strong>Defensive Lab</strong></a>
    ·
    <a href="https://www.linkedin.com/in/volodymyr-stetsenko-656014246/"><strong>LinkedIn</strong></a>
    ·
    <a href="https://www.youtube.com/@Zero2Audit"><strong>YouTube</strong></a>
  </p>
</div>

---

## What I investigate

- Smart-contract logic and protocol architecture
- Privileged roles, admin keys, upgrade paths, multisigs, and timelocks
- Oracles, bridges, off-chain verification, wallets, and external dependencies
- On-chain incident chronology, asset flows, and economic extraction
- Defensive controls, monitoring rules, and safe local reproductions

My work is organised around one question:

> **Where did the system's security assumption stop being true?**

## Research operating system

```text
SIGNAL
  ↓
SOURCE VALIDATION
  ↓
SYSTEM & TRUST MODEL
  ↓
EXPLOIT CHAIN
  ↓
ON-CHAIN EVIDENCE
  ↓
DEFENSIVE LAB
  ↓
CONTROL MAP
  ↓
PUBLIC CASE FILE
```

Each completed case is designed to be independently reviewable. A public case file should contain the scope, confirmed evidence, uncertainty labels, root-cause model, defensive recommendations, and — where useful — an authorised local or fork-based reproduction.

## Evidence ledger

| Evidence | Type | What it demonstrates | Status |
|---|---|---|---|
| [Security Research Library](https://github.com/VolodymyrStetsenko/SECURITY-REVIEW) | Reports & case registry | Structured findings, severity tracking, and public research provenance | Active |
| [SecureVault Foundry Lab](https://github.com/VolodymyrStetsenko/SecureVault-Foundry) | Defensive engineering lab | Unit, attack-simulation, and invariant-testing workflow | Public |
| Echo Protocol eBTC / Monad | Incident case file | Privileged-role compromise, fake collateral, downstream loss, and defensive controls | In progress |
| Additional assessment reports | Portfolio evidence | Manual review, finding documentation, and report production | Publication queue |

> **Evidence rule:** I do not treat a claim as a credential. Public claims should be supported by a report, repository, reproducible command, transaction reference, or clearly labelled work-in-progress artifact.

## Publication model

My public security work is separated into four evidence classes:

1. **Incident case files** — real-world exploit-chain reconstruction and on-chain evidence.
2. **Security assessments** — scoped code or protocol reviews with findings and limitations.
3. **Defensive labs** — authorised local reproductions, tests, threat models, and mitigations.
4. **Methods** — reusable research templates, control maps, and analysis frameworks.

The canonical index is maintained in the [Security Research Library](https://github.com/VolodymyrStetsenko/SECURITY-REVIEW). Videos and social posts are distribution layers; the repository remains the source of record.

## Current build cycle

- Publish the Echo Protocol eBTC case file with a concise evidence map
- Produce an English technical video and a safe Foundry-style local lab
- Expand the public report registry with previously completed assessments
- Develop a repeatable **Exploit-Chain Framework** for privilege, dependency, and operational-risk analysis

## Scope and ethics

All technical reproductions are limited to systems I own, local environments, public test environments, historical fork analysis, or work for which explicit authorisation exists. Public research is intended for defensive education, risk reduction, and responsible security improvement.

## Contact

For security research, technical writing, incident-analysis collaboration, or protocol-readiness discussions:

- [LinkedIn](https://www.linkedin.com/in/volodymyr-stetsenko-656014246/)
- [X](https://x.com/carstetsen)
- [YouTube](https://www.youtube.com/@Zero2Audit)
- [Telegram](https://t.me/Zero2Auditor)

---

<div align="center">
  <sub>Independent research · Evidence before claims · Defensive work only</sub>
</div>
