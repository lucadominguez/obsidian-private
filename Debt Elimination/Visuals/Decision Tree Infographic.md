# The Debt Elimination Decision Tree — Visual Reference

> Companion to [[Articles/01 - They're Counting On You]]
> [Open full interactive version in browser →](debt-decision-tree.html)

---

## The Decision Framework

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'fontSize':'11px'}}}%%
graph TD
    START["💸 YOU HAVE DEBT"] --> Q1{"Past statute<br/>of limitations?"}
    
    Q1 -->|"YES"| IGNORE["🚫 IGNORE<br/>Legally dead.<br/>Don't pay a cent.<br/>Don't acknowledge in writing."]
    Q1 -->|"NO / UNSURE"| VALIDATE["📬 SEND VALIDATION<br/>LETTER<br/>Certified mail.<br/>FDCPA §1692g.<br/>They must prove you owe it."]
    
    VALIDATE --> Q2{"Can they<br/>validate?"}
    Q2 -->|"NO (70%)"| DEAD["💀 DEBT IS DEAD<br/>$22K eliminated<br/>this way across<br/>7 accounts"]
    Q2 -->|"YES"| SETTLE["💰 NEGOTIATE<br/>Stop paying 4-6mo.<br/>Counter at 25-30%.<br/>Get agreement IN WRITING.<br/>Cashier's check only."]
    
    SETTLE --> Q3{"On credit<br/>report?"}
    Q3 -->|"YES"| DISPUTE["📋 DISPUTE<br/>All 3 bureaus.<br/>30-day deadline.<br/>Pay-for-delete if<br/>verified."]
    Q3 -->|"NO"| CLEAN["✅ REBUILD<br/>Secured card.<br/>Under 10% utilization.<br/>420 → 780 in 3 years."]
    DISPUTE --> CLEAN

    style START fill:#1e293b,stroke:#38bdf8,color:#f8fafc
    style Q1 fill:#1e293b,stroke:#fbbf24,color:#fde68a
    style Q2 fill:#1e293b,stroke:#fbbf24,color:#fde68a
    style Q3 fill:#1e293b,stroke:#fbbf24,color:#fde68a
    style IGNORE fill:#7f1d1d,stroke:#ef4444,color:#fca5a5
    style DEAD fill:#7f1d1d,stroke:#ef4444,color:#fca5a5
    style VALIDATE fill:#1e3a5f,stroke:#38bdf8,color:#bae6fd
    style SETTLE fill:#1e293b,stroke:#fbbf24,color:#fde68a
    style DISPUTE fill:#1e293b,stroke:#a78bfa,color:#ddd6fe
    style CLEAN fill:#14532d,stroke:#22c55e,color:#bbf7d0
```

---

## Key Stats

| Metric | Value |
|---|---|
| Total debt eliminated | $87,000 |
| Validation letter success rate | ~70% |
| Debt eliminated via validation | $22,000 |
| Best settlement | $14K → $4,200 (30%) |
| Credit score | 420 → 780 |
| Time to rebuild | ~3 years |
| Cost to access full library | $99/mo |

---

## The Weapons In Order

| Priority | Weapon | When | Cost |
|---|---|---|---|
| 1st | Statute of limitations | Debt is 3-6+ years old | $0 |
| 2nd | Debt validation letter | Within 30 days of contact | ~$5 |
| 3rd | Settlement negotiation | Debt is valid & collectible | 25-40% of balance |
| 4th | Credit report dispute | Negative items on report | ~$5/letter |
| 5th | Pay-for-delete | Verified debt, want clean report | Negotiated |

[Open full interactive decision tree →](debt-decision-tree.html)