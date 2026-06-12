# Finding — [SHORT TITLE, e.g., "Missing Signer Check in Withdraw Instruction"]

---

### 🗂 Metadata

| Field                   | Value                                                                    |
|-------------------------|--------------------------------------------------------------------------|
| **Finding ID**          | AUDIT-[YEAR]-[###] _(e.g., AUDIT-2025-007)_                             |
| **Week**                | [NUMBER]                                                                 |
| **Researcher**          | [GitHub handle] / [X handle]                                            |
| **Date Reported**       | [YYYY-MM-DD]                                                             |
| **Severity**            | 🔴 Critical / 🟠 High / 🟡 Medium / 🟢 Low / ℹ️ Informational           |
| **Category**            | [e.g., Missing signer check, Arithmetic overflow, PDA seed collision]   |
| **Affected Function**   | [instruction name or function]                                          |
| **Status**              | 🔴 Open / 🟡 In Review / ✅ Fixed / ❌ Won't Fix                         |

---

### 📋 Description

> _Write 2–3 sentences a non-technical manager can understand, then go deeper for devs._

[Clear explanation of the vulnerability — what's wrong and why it matters.]

---

### 💥 Impact

[What can an attacker do? Quantify wherever possible.]

- **Worst case**: [e.g., drain all vault funds]
- **Likelihood**: [High / Medium / Low — and why]
- **Affected users/assets**: [e.g., all depositors, ~$500k TVL at risk]

---

### 🔬 Proof of Concept

> ⚠️ **REQUIRED** — must be independently verifiable without guesswork.

[Choose one or more of the following:]
- TypeScript/Rust test that triggers the vulnerability
- Step-by-step transaction sequence with account setups
- Code diff showing the exact exploit path

**Expected behavior:**
[What should happen under normal conditions]

**Actual behavior:**
[What actually happens — the bug]

```rust
// PoC code here
```

---

### ✅ Recommended Fix

[How to patch it. Include before/after code if possible.]

**Before:**
```rust
// Vulnerable code here
```

**After:**
```rust
// Fixed code here
```

---

### 🔗 References

- [Link to affected file / line number in repo]
- [Related audit findings, CVEs, or Solana docs if applicable]

---

### 📝 Audit Trail

| Date       | Action           | By            |
|------------|------------------|---------------|
| YYYY-MM-DD | Finding reported | [Researcher]  |
| YYYY-MM-DD | Acknowledged     | [Team]        |
| YYYY-MM-DD | Fix deployed     | [Dev]         |
