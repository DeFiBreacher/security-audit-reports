# 🔐 DeFiBreacher — Security Audit Portfolio

> Independent Security Researcher specializing in **Solidity** & **Rust** smart contract audits.
> Hunting critical vulnerabilities across DeFi protocols — one finding at a time.

<div align="center">

[![Findings](https://img.shields.io/badge/Total%20Findings-0-1a1a2e?style=for-the-badge&logo=shield&logoColor=white)](./findings/)
[![Criticals/Highs](https://img.shields.io/badge/Criticals%20%2F%20Highs-0-c0392b?style=for-the-badge&logo=bug&logoColor=white)]()
[![Fixed](https://img.shields.io/badge/Fixed-0-27ae60?style=for-the-badge&logo=checkmarx&logoColor=white)]()
[![Protocols](https://img.shields.io/badge/Protocols%20Audited-0-8e44ad?style=for-the-badge&logo=ethereum&logoColor=white)]()

</div>

---

## ⚡ At a Glance

| 🔴 Critical | 🟠 High | 🟡 Medium | 🟢 Low | ℹ️ Info |
|:-----------:|:-------:|:---------:|:------:|:-------:|
| 0 | 0 | 0 | 0 | 0 |

> Findings span EVM bytecode quirks, reentrancy patterns, oracle manipulation, access control flaws, and economic exploits.

---

## 📋 Findings

| ID | Title | Protocol | Severity | Date | Status |
|----|-------|----------|----------|------|--------|
| — | *No public findings yet* | — | — | — | — |

> Each entry links to a full report: vulnerability description, root cause, on-chain PoC, and remediation guidance.

---

## 🗂 Repository Structure

```
audits/
├── README.md                    ← Portfolio index (you are here)
├── findings/                    ← One file per finding
│   └── AUDIT-YYYY-###.md        ← Named by year and sequence
└── templates/
    └── finding-template.md      ← Standard finding format (PoC required)
```

---

## 🚦 Severity Definitions

| Level | Criteria |
|-------|----------|
| 🔴 **Critical** | Direct loss of funds, full protocol compromise, no preconditions needed |
| 🟠 **High** | Significant user impact; may require specific conditions to trigger |
| 🟡 **Medium** | Limited blast radius, or requires chaining with other issues |
| 🟢 **Low** | Minor risk; best-practice fix recommended |
| ℹ️ **Informational** | No immediate risk; code quality or design suggestion |

---

## 📌 Status Definitions

| Status | Meaning |
|--------|---------|
| 🔴 **Open** | Reported, awaiting acknowledgement from the team |
| 🟡 **In Review** | Team is actively investigating or developing a fix |
| ✅ **Fixed** | Patch deployed and verified by researcher |
| ❌ **Won't Fix** | Acknowledged but accepted risk or out of scope |

---

## 🛠 Adding a Finding

```bash
# 1. Copy the template
cp templates/finding-template.md findings/AUDIT-YYYY-###.md

# 2. Fill out all sections (PoC is mandatory)

# 3. Add a row to the Findings table above

# 4. Update the At a Glance counters

# 5. Commit with a descriptive message
git add .
git commit -m "finding: AUDIT-YYYY-### [Protocol] [Title] [Severity]"
git push origin main
```

---

## 🧪 Tooling & Methodology

| Phase | Tools / Approach |
|-------|-----------------|
| Static Analysis | Slither, Semgrep, custom detectors |
| Fuzzing | Echidna, Foundry invariant tests |
| Formal Verification | Certora Prover (selective) |
| Manual Review | Line-by-line Solidity/Rust + economic modeling |
| PoC | Foundry fork tests against mainnet state |

---

## 📬 Contact & Links

| Platform | Handle |
|----------|--------|
| ✍️ Medium | [@DeFiBreacher](https://medium.com/@DeFiBreacher) |
| 🐦 X / Twitter | [@DeFibreacher](https://x.com/defibreacher) |
| 💬 Telegram | [@DeFiBreacher](https://t.me/DefiBreacher) |

> For private disclosure requests or audit engagements, reach out via Telegram or X DM.

---

<div align="center">

*Smart contracts don't lie — but they do surprise you.*

</div>
