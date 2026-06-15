# 🔐 Security Audit Portfolio

> Independent Security Researcher specializing in Solidity/Rust smart contract audits.
> This repository contains all public audit findings, organized by severity and protocol.

[![Findings](https://img.shields.io/badge/Total%20Findings-0-blue)](./findings/)
[![Criticals/Highs](https://img.shields.io/badge/Criticals/Highs-0-red)]()
[![Mediums](https://img.shields.io/badge/Medium-0-yellow)]()
[![Low](https://img.shields.io/badge/Low-0-blue)]()
[![Fixed](https://img.shields.io/badge/Fixed-0-brightgreen)]()

---

## 📊 Stats

| 🔴 Critical | 🟠 High | 🟡 Medium | 🟢 Low |
|:-----------:|:-------:|:---------:|:------:|
| 0           | 0       | 0         | 0      | 

---

## 📋 Findings

| ID | Title | Protocol | Severity | Date | Status |
|----|-------|----------|----------|------|--------|
| — | _No findings yet_ | — | — | — | — |

> Each finding links to a full report with description, impact, PoC, and recommended fix.

---

## 🗂 Repository Structure

```
audits/
├── README.md                  ← Portfolio index (you are here)
├── findings/                  ← One file per finding
│   └── AUDIT-YYYY-###.md
└── templates/
    └── finding-template.md    ← Standard finding format
```

---

## 🚦 Severity Definitions

| Level | Description |
|-------|-------------|
| 🔴 Critical | Direct loss of funds, full protocol compromise, no preconditions needed |
| 🟠 High | Significant impact, may require specific conditions to exploit |
| 🟡 Medium | Limited impact or requires chaining with other issues |
| 🟢 Low | Minor issue, informational fix recommended |
| ℹ️ Informational | No immediate risk, best practice suggestion |

---

## 📌 Status Definitions

| Status | Meaning |
|--------|---------|
| 🔴 Open | Reported, awaiting acknowledgement |
| 🟡 In Review | Team is investigating or working on a fix |
| ✅ Fixed | Patch deployed and verified |
| ❌ Won't Fix | Acknowledged but out of scope or accepted risk |

---

## 🛠 How to Add a Finding

```bash
# 1. Copy the template
cp templates/finding-template.md findings/AUDIT-YYYY-###.md

# 2. Fill it out (PoC is required)

# 3. Add a row to the Findings table above

# 4. Update the Stats table counts

# 5. Commit and push
git add .
git commit -m "finding: AUDIT-YYYY-### [title] [Severity]"
git push origin main
```

---

## 📬 Contact

- GitHub: [@DeFiBreacher](https://github.com/defibreacher)
- X: [@DeFibreacher](https://x.com/defibreacher)
- Telegram:[@DeFiBreacher](https://t.me/DefiBreacher)
