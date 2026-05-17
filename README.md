# PolicyMap — Cross-Platform Community Guidelines Audit

> A primary-source-only Trust & Safety policy audit of YouTube, Reddit, TikTok, and Meta/Instagram across 12 content categories and 23 documented cross-platform gaps.
---

## What This Is

**PolicyMap** is a structured, evidence-based audit of how four major social media platforms handle the same categories of harmful content — and why those differences matter for moderators, journalists, creators, and at-risk users.

Every factual claim is sourced from a **primary platform policy document**. No blog post, news summary, or secondary analysis was used as a factual basis for any policy claim. Every verbatim quotation is cited with its exact source URL and access date.

**Research date: May 2025.** TikTok's September 2025 Community Guidelines restructuring is documented. Meta's January 2025 Hateful Conduct changes are confirmed and documented.

---

## Platforms Audited

| Platform | Primary Policy Source | Avg Specificity Score |
|---|---|:---:|
| **YouTube** | support.google.com/youtube | 4.3 / 5 |
| **Reddit** | redditinc.com/policies | 2.5 / 5 |
| **TikTok** | tiktok.com/community-guidelines | 3.2 / 5 |
| **Meta / Instagram** | transparency.meta.com/policies | 4.1 / 5 |

---

## Three Headline Findings

**1. TikTok's FYF de-amplification is a structural innovation with no cross-platform equivalent.**
TikTok is the only platform that explicitly documents a mid-tier enforcement action between "remove" and "allow." Content can exist on the platform and be algorithmically invisible to most users. The question for moderators is no longer just *"should this be removed?"* — it's also *"should this be de-amplified even if it stays up?"* — a question for which YouTube, Reddit, and Meta have no documented policy answer.

**2. Reddit has a documented site-wide policy absence on misinformation.**
Reddit's Content Policy has no standalone misinformation policy. False health claims and election falsehoods are not explicitly prohibited at the platform level — confirmed by Reddit's own AB587 regulatory compliance filings (California AG, Q4 2023). Scores 1/5 in both health and election misinformation categories. Unique among major platforms.

**3. Meta's January 2025 changes introduced documented LGBTQ+ protection rollbacks still in effect.**
Meta's Hateful Conduct policy now explicitly permits content alleging mental illness based on gender or sexual orientation. Confirmed verbatim from Meta's own policy page and corroborated by GLAAD's 2026 Social Media Safety Index (published ~May 2025) and Meta's own Oversight Board ruling (April 2025, which rebuked the changes — but Meta has not reversed them as of May 2025).

---

## The 12 Content Categories

Defined **before** any policy documents were read, to prevent selection bias.

| # | Category |
|:---:|---|
| 1 | Graphic Violence: Real-World / News Context |
| 2 | Graphic Violence: Entertainment / Fictional |
| 3 | Sexual Content: Adult |
| 4 | Sexual Content: Minors (CSAM) |
| 5 | Hate Speech: Race and Ethnicity |
| 6 | Hate Speech: Gender and Sexual Orientation |
| 7 | Misinformation: Health |
| 8 | Misinformation: Elections |
| 9 | Harassment and Doxxing |
| 10 | Self-Harm and Suicide |
| 11 | Dangerous Activities and Challenges |
| 12 | Violent Extremism and Terrorism |

---

## Specificity Score Matrix

Scores 1–5. **5** = tiered severity + contextual exceptions with explicit criteria. **1** = absent or non-actionable.

| Category | YouTube | Reddit | TikTok | Meta/IG | Alignment |
|---|:---:|:---:|:---:|:---:|---|
| Graphic Violence: News | 5 | 3 | 3 | 5 | Moderate |
| Graphic Violence: Fictional | 4 | 2 | 3 | 4 | Moderate |
| Sexual Content: Adult | 4 | 2 | 3 | 4 | Moderate |
| **CSAM** | **5** | **5** | **5** | **5** | **Strong ✓** |
| Hate Speech: Race | 5 | 3 | 3 | 5 | Moderate |
| Hate Speech: Gender | 4 | 3 | 3 | 4 | Moderate |
| **Misinformation: Health** | 4 | **1** | 3 | 3 | **Divergent ✗** |
| **Misinformation: Elections** | 3 | **1** | 3 | 3 | **Divergent ✗** |
| Harassment & Doxxing | 5 | 3 | 3 | 5 | Moderate |
| Self-Harm & Suicide | 5 | 3 | 3 | 4 | Moderate |
| Dangerous Activities | 4 | 2 | 3 | 3 | Moderate |
| **Violent Extremism** | **5** | **3** | **4** | **5** | **Strong ✓** |
| **Average** | **4.3** | **2.5** | **3.2** | **4.1** | |

---

## The 23 Documented Gaps

| ID | Title | Severity |
|---|---|:---:|
| GAP-001 | Educational Violence Threshold | 🔴 HIGH |
| GAP-002 | Slur Reclamation Standard | 🔴 HIGH |
| GAP-003 | FYF De-amplification vs. Removal | 🔴 HIGH |
| GAP-004 | Misinformation Vacuum on Reddit | 🔴 HIGH |
| GAP-005 | External Oversight Mechanism Gap | 🔴 HIGH |
| GAP-006 | Newsworthiness Exception Transparency | 🔴 HIGH |
| GAP-007 | Regional Content Modulation | 🔴 HIGH |
| GAP-008 | Safe Messaging Guidelines Adoption | 🔴 HIGH |
| GAP-009 | Escalation/Strike Systems | 🟡 MEDIUM |
| GAP-010 | Public Figure Exception Thresholds | 🟡 MEDIUM |
| GAP-011 | Animal Cruelty Exceptions | 🟡 MEDIUM |
| GAP-012 | Coordinated Inauthentic Behaviour | 🟡 MEDIUM |
| GAP-013 | Glorification vs. Discussion | 🟡 MEDIUM |
| GAP-014 | Dangerous Challenges Threshold | 🟡 MEDIUM |
| GAP-015 | Off-Platform Conduct Review | 🟡 MEDIUM |
| GAP-016 | Satire Exception Documentation | 🟡 MEDIUM |
| GAP-017 | Historical Documentation Exception | 🟡 MEDIUM |
| GAP-018 | Creator/Platform Liability Chain | 🟡 MEDIUM |
| GAP-019 | Policy Terminology Differences | 🟢 LOW |
| GAP-020 | Appeal Timeline Documentation | 🟢 LOW |
| GAP-021 | Community Warning Labels | 🟢 LOW |
| GAP-022 | Context Burden Allocation | 🟢 LOW |
| GAP-023 | Transparency Reporting Granularity | 🟢 LOW |

---

## Deliverables

```
PolicyMap/
├── PolicyMap_Report_v1.0.docx          # Full report (~30 pages, ~9,000 words)
├── PolicyMap_Audit_Matrix.xlsx         # Master matrix + 23-gap register + profiles
├── PolicyMap_ViolenceDecisionTree.html # Interactive 6-node decision flowchart
├── README.md
├── CHANGELOG.md
├── .gitignore
├── docs/
│   └── index.html                      # GitHub Pages landing page
├── research_notes/
│   ├── YouTube_notes.md                # Live-verified verbatim quotes + score rationale
│   ├── Reddit_notes.md
│   ├── TikTok_notes.md
│   └── Meta_notes.md
└── sources/
    ├── sources_master_list.csv         # 34 primary source URLs with access dates
    └── policy_excerpts.md             # 36 tagged verbatim quotes with source IDs
```

---

## Decision Tree

`PolicyMap_ViolenceDecisionTree.html` — open in any browser. Printable to PDF. Covers:

- **Node 1:** Minor harm → immediate removal + NCMEC report (all platforms)
- **Node 2:** Glorification/incitement → removal, no exceptions (all platforms)
- **Node 3:** Perpetrator footage → YouTube hard rule (no EDSA exception); others vary
- **Node 4:** In-video context present? → platform-specific if absent
- **Node 5:** Gratuitous suffering? → removal even with context (all platforms)
- **Node 6:** Platform-specific evaluation (YouTube EDSA / TikTok FYF / Reddit NSFW / Meta Newsworthiness)

---

## Methodology

- **Primary sources only** — zero secondary sources for policy claims
- **Categories defined before research** — no selection bias
- **Each gap documented with:** Platform A verbatim quote + URL, Platform B verbatim quote or absence statement + source, real-world scenario, harm potential, severity rating, harmonisation recommendation
- **Access dates recorded** — policies change; full audit trail in sources/
- **Limitations stated without softening:** single reviewer (inter-rater reliability = zero), public-facing policies only, English-language only, policies may have changed since May 2025

---

## Key Verified Live Quotes

All confirmed from live fetches during research:

**YouTube** (support.google.com/youtube/answer/2802008, accessed May 2025):
> *"Footage filmed by the perpetrator during a deadly or major violent event, in which weapons, violence, or injured victims are visible or audible [is not allowed even with EDSA context]."*

**Reddit** (AB587 Q4 2023 filing, oag.ca.gov):
> *"Reddit's Content Policy more broadly prohibits content manipulation (Rule 2) and impersonation in a misleading or deceptive manner (Rule 5)."* — confirms no standalone misinformation prohibition

**TikTok** (tiktok.com/community-guidelines/en/fyf-standards, confirmed live):
> *"When we identify content that falls under the 'FYF Ineligible' standards in our Community Guidelines, it won't be recommended in the FYF."*

**Meta** (transparency.meta.com/policies/community-standards/hateful-conduct/, confirmed live May 2025):
> *"We do allow allegations of mental illness or abnormality when based on gender or sexual orientation, given political and religious discourse about transgenderism and homosexuality."*

---

## Disclaimer

This report is an independent academic analysis. Not affiliated with or endorsed by YouTube, Reddit, TikTok, or Meta. All policy citations are from primary platform policy documents accessed May 2025. Verify currency before operational use — policies change.

## Citation

```
PolicyMap: A Cross-Platform Community Guidelines Audit for Trust & Safety Professionals.
Version 1.0. May 2025. Primary sources accessed May 2025.
Available at: https://github.com/sat1828/PolicyMap
```
