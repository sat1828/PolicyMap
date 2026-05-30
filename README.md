<div align="center">

<img width="1200" height="380" alt="banner" src="https://github.com/user-attachments/assets/73a95c4e-9309-4b4b-bce6-ca97c22ff54e" />

<br/>

![Research Date](https://img.shields.io/badge/Research_Date-May_2025-0369a1?style=flat-square&labelColor=0d1117)
![Platforms](https://img.shields.io/badge/Platforms_Audited-4-7c3aed?style=flat-square&labelColor=0d1117)
![Categories](https://img.shields.io/badge/Content_Categories-12-0891b2?style=flat-square&labelColor=0d1117)
![Gaps](https://img.shields.io/badge/Cross--Platform_Gaps-23-dc2626?style=flat-square&labelColor=0d1117)
![Sources](https://img.shields.io/badge/Primary_Sources-34-166534?style=flat-square&labelColor=0d1117)
![Quotes](https://img.shields.io/badge/Verbatim_Quotes-42-b45309?style=flat-square&labelColor=0d1117)
![Language](https://img.shields.io/badge/Language-HTML_100%25-6d28d9?style=flat-square&labelColor=0d1117)
![Methodology](https://img.shields.io/badge/Methodology-Primary_Sources_Only-1d4ed8?style=flat-square&labelColor=0d1117)

</div>

---

## What This Actually Is

Four platforms. Twelve categories of harmful content. One question applied identically to all of them: **what does the policy document actually say?**

Not what a news article said the policy says. Not what a platform's blog post announced. Not what a transparency report summarised. The live policy document — read verbatim, scored on a rubric written before a single document was opened, gaps catalogued with two-sided primary-source citations.

PolicyMap treats platform policy documents the way a lawyer treats a contract. The exact text matters. The absence of text matters. And the gap between what YouTube says and what Reddit says about the same piece of violent content has real consequences for real people — moderators, creators, at-risk users, journalists, regulators.

Every factual claim about what a platform's policy says traces back to a live-fetched primary source URL with a recorded access date. No secondary sources were used for any policy claim. If a fact can't be cited to a primary document, it doesn't appear in the report.

---

## Three Findings Worth Reading Twice

<img width="1100" height="360" alt="findings" src="https://github.com/user-attachments/assets/17873d55-9c70-4c82-b71f-00b87b574488" />

### Finding 1 — TikTok invented a third enforcement state

Remove or allow — that was the binary every content moderator worked with across every major platform. TikTok added a third option, documented explicitly in their FYF Standards page: **keep it up, make it algorithmically invisible to most users, call it "FYF-ineligible."**

A moderator following TikTok's policy must evaluate the same piece of borderline content twice: once for removal, once for FYF eligibility. YouTube, Reddit, and Meta have no equivalent documented tier. Their policies describe two outcomes. TikTok describes three.

This isn't about TikTok being more restrictive. It's about the rest of the industry not having caught up in their *written policy* — even though all three almost certainly suppress content algorithmically in practice.

**Documented as GAP-003 (HIGH severity) in the Gap Register.**

### Finding 2 — Reddit has no misinformation policy. Not a weak one. None.

Reddit's Content Policy contains no standalone misinformation rule. False health claims, election falsehoods, medical disinformation — none of it is explicitly prohibited at the platform level.

This wasn't assumed. It was confirmed by reading Reddit's own **AB587 regulatory compliance filing with the California Attorney General (Q4 2023)**, in which Reddit lists every site-wide rule that maps to a regulated content category. Misinformation does not appear. The filing explicitly maps Rule 2 (content manipulation) and Rule 5 (impersonation) — and nothing else. The **New York S895B compliance filing** corroborates this absence.

Reddit scores **1/5** in both health misinformation and elections misinformation. Every other platform in this audit scores 3 or higher. The gap is confirmed from Reddit's own hand.

**Documented as GAP-004 (HIGH severity) in the Gap Register.**

### Finding 3 — Meta's January 2025 LGBTQ+ rollback is live, rebuked, and unreversed

Meta's Hateful Conduct policy was revised in January 2025. The updated page explicitly permits content alleging mental illness or abnormality based on gender or sexual orientation. That language is in the live policy.

The **Meta Oversight Board issued a formal rebuke in April 2025**. GLAAD's Social Media Safety Index (published approximately May 2025) confirmed the change and downgraded Meta's score. As of the May 2025 research date, Meta had not reversed the change despite the Board's ruling. The Oversight Board's advisory opinion — the only mechanism of external policy accountability any of the four platforms has — was ignored.

**Documented in Meta platform profile and cross-referenced in GAP-002 (HIGH severity).**

---

## Platform Profiles

<img width="1100" height="460" alt="platforms" src="https://github.com/user-attachments/assets/60ebd0f1-f2cd-467c-8fd0-ecc8a39ac212" />

| Platform | Policy Home | Avg Score | Notes |
|---|---|:---:|---|
| **YouTube** | support.google.com/youtube | **4.3 / 5** | Perpetrator-footage absolute rule; strongest EDSA framework |
| **Meta / Instagram** | transparency.meta.com/policies | **4.1 / 5** | Jan 2025 LGBTQ+ rollback confirmed and in effect |
| **TikTok** | tiktok.com/community-guidelines | **3.2 / 5** | FYF de-amplification — the only documented third-tier enforcement |
| **Reddit** | redditinc.com/policies | **2.5 / 5** | No standalone misinformation policy; confirmed via own regulatory filings |

Scores use the **1–5 Specificity Scale** defined before any policy documents were read. **5** means tiered severity levels with explicit contextual exceptions and documented criteria for each tier. **1** means the policy is absent or too vague for a moderator to act on.

---

## Specificity Score Matrix

<img width="1100" height="540" alt="score_matrix" src="https://github.com/user-attachments/assets/a178480b-538b-465d-871b-e8304046d6fe" />

Full 12-category × 4-platform breakdown. Each cell score is sourced from primary policy documents and logged with verbatim citations in `PolicyMap_Audit_Matrix.xlsx`.

| Category | YouTube | Reddit | TikTok | Meta/IG | Cross-Platform Alignment |
|---|:---:|:---:|:---:|:---:|---|
| Graphic Violence: News Context | 5 | 3 | 3 | 5 | Moderate |
| Graphic Violence: Fictional | 4 | 2 | 3 | 4 | Moderate |
| Sexual Content: Adult | 4 | 2 | 3 | 4 | Moderate |
| **CSAM** | **5** | **5** | **5** | **5** | **Strong ✓ — all platforms align** |
| Hate Speech: Race & Ethnicity | 5 | 3 | 3 | 5 | Moderate |
| Hate Speech: Gender & Sexual Orient. | 4 | 3 | 3 | 4 | Moderate |
| **Misinformation: Health** | **4** | **1** | **3** | **3** | **⚠ Divergent — Reddit absent** |
| **Misinformation: Elections** | **3** | **1** | **3** | **3** | **⚠ Divergent — Reddit absent** |
| Harassment & Doxxing | 5 | 3 | 3 | 5 | Moderate |
| Self-Harm & Suicide | 5 | 3 | 3 | 4 | Moderate |
| Dangerous Activities & Challenges | 4 | 2 | 3 | 3 | Moderate |
| **Violent Extremism & Terrorism** | **5** | **3** | **4** | **5** | **Strong ✓** |
| **Platform Average** | **4.3** | **2.5** | **3.2** | **4.1** | |

**Strong** = all four platforms have explicit, actionable, tiered policy. **Divergent** = a moderator on one platform has no documented framework for a category where every other platform does.

---

## The 23 Documented Gaps

<img width="1100" height="420" alt="gaps" src="https://github.com/user-attachments/assets/e12515de-02c4-4cc9-b396-91e810f8a6dd" />

Every gap in the register has the same structure: Platform A verbatim quote with URL and access date, Platform B verbatim quote or an explicit documented statement of absence with source, a real-world scenario that falls through the crack, a harm potential assessment, a severity rating, and a harmonisation recommendation.

### 🔴 HIGH Severity — 8 Gaps

| ID | Gap | What It Means |
|---|---|---|
| GAP-001 | Educational Violence Threshold | Where exactly does "documentary" end and "gratuitous" begin — four platforms draw the line in four different places |
| GAP-002 | Slur Reclamation Standard | Four different tests for whether a slur is reclaimed by community use or still harmful — none of them documented with the same criteria |
| GAP-003 | FYF De-amplification vs. Removal | TikTok's third enforcement state has no documented equivalent on any other platform |
| GAP-004 | Misinformation Vacuum on Reddit | Absent at the platform level, confirmed from Reddit's own AB587 and NY S895B regulatory filings |
| GAP-005 | External Oversight Mechanism Gap | Only Meta has a documented external review body; the Oversight Board is the only cross-platform comparison point |
| GAP-006 | Newsworthiness Exception Transparency | The exception exists on all four platforms; the criteria for invoking it are documented differently on each |
| GAP-007 | Regional Content Modulation | Same content, different rules depending on user location — documented on TikTok, implied but undocumented elsewhere |
| GAP-008 | Safe Messaging Guidelines Adoption | WHO/AFSP safe messaging principles referenced inconsistently — TikTok cites them by name; Reddit does not document them at all |

### 🟡 MEDIUM Severity — 10 Gaps

| ID | Gap |
|---|---|
| GAP-009 | Escalation/Strike Systems — identical violations lead to structurally different consequences depending on platform |
| GAP-010 | Public Figure Exception Thresholds — who counts as "public enough" to lose certain harassment protections |
| GAP-011 | Animal Cruelty Exceptions — hunting, cultural practice, and news documentation are treated differently with no cross-platform consistency |
| GAP-012 | Coordinated Inauthentic Behaviour — definitions of "coordinated" diverge in operationally significant ways |
| GAP-013 | Glorification vs. Discussion — the line between discussing extremism and promoting it is drawn in different places |
| GAP-014 | Dangerous Challenges Threshold — platform specificity ranges from detailed criteria to near-absent |
| GAP-015 | Off-Platform Conduct Review — TikTok documents this; others do not, even though enforcement practice suggests it happens |
| GAP-016 | Satire Exception Documentation — exists as a concept on all platforms; explicit criteria exist on almost none |
| GAP-017 | Historical Documentation Exception — Nazi imagery, war crimes footage, atrocity evidence handled without consistent framework |
| GAP-018 | Creator/Platform Liability Chain — who bears formal responsibility when a creator's content causes downstream harm |

### 🟢 LOW Severity — 5 Gaps

| ID | Gap |
|---|---|
| GAP-019 | Policy Terminology Differences — "harmful," "dangerous," "objectionable" carry different meanings across the four policy documents |
| GAP-020 | Appeal Timeline Documentation — how long a removed creator has to appeal is specified on none of the four platforms |
| GAP-021 | Community Warning Labels — label design, trigger criteria, and skip-ability are documented inconsistently |
| GAP-022 | Context Burden Allocation — who proves context: the creator uploading, or the reviewer deciding |
| GAP-023 | Transparency Reporting Granularity — enforcement numbers are reported at different levels of specificity, preventing comparison |

---

## The Interactive Decision Tree

<img width="1100" height="700" alt="decision_tree" src="https://github.com/user-attachments/assets/fb0e7963-df9c-4cf7-8b87-65a2408235c8" />

`PolicyMap_ViolenceDecisionTree.html` — 711 lines of hand-written HTML and CSS, 29.2 KB, zero external dependencies. Open it in a browser and it works. Print it to PDF and it holds. Built to be used, not just read.

It maps the journey of a real-world violent video through six binary decision nodes, tracking how all four platforms would handle it simultaneously. Every node is YES or NO. Every terminal leads to a specific documented action.

**The six nodes:**

| Node | Question | Outcome if YES |
|:---:|---|---|
| 1 | Does this depict harm to a minor? | Immediate removal + NCMEC report. All platforms. Zero exceptions. |
| 2 | Does it glorify or incite violence? | Removal. No contextual exceptions. All platforms align. |
| 3 | Was it filmed by the perpetrator? | YouTube: absolute removal, no EDSA exception. Others: likely remove or NSFW. |
| 4 | Is context present *inside* the video? | If no: platform-specific (age-gate / restrict / label / NSFW). |
| 5 | Is the violence gratuitous beyond editorial purpose? | Removal even with context. EDSA does not protect gratuitous framing. |
| 6 | Platform-specific evaluation | YT: EDSA  ·  TK: FYF split  ·  RD: NSFW  ·  MT: Newsworthiness |

**Node 6 is where GAP-003 surfaces explicitly.** The HTML file includes a callout explaining that a TikTok moderator following the documented policy must evaluate the content *twice at this node* — once for removal, once for FYF eligibility. No equivalent dual-evaluation is documented on YouTube, Reddit, or Meta.

Color coding in the interactive version: **Red** (remove) · **Amber** (restrict) · **Grey** (human review) · **Blue** (platform-specific) · **Green** (document and close).

---

## Methodology

<img width="1100" height="400" alt="methodology" src="https://github.com/user-attachments/assets/150fdc64-d834-4f56-ab48-94713498ea8a" />

Five constraints. Applied in order. Violated at none.

**1. Primary sources only.** Every factual claim about what a platform's policy says traces to a primary document: a support page, a Community Standards page, a Transparency Center page, or an official regulatory filing. No journalism. No blog posts. No secondary summaries used for policy claims.

**2. Categories defined before research.** All 12 content categories were written down before any policy document was opened. Without this constraint, the natural tendency is to focus on categories where differences are interesting and ignore the ones where all four platforms agree. The categories force uniform coverage.

**3. Rubric defined before scoring.** The 1–5 specificity scale was defined and documented before the first score was assigned. Post-hoc score adjustment — "this feels like it should be a 4" — is not possible when the rubric predates the data.

**4. Two-sided citations for every gap.** Every gap documents Platform A's position with a verbatim quote and URL, and Platform B's position with a verbatim quote *or* an explicit documented statement of absence with a primary source. Absence is documented, not assumed. The Reddit misinformation gap is confirmed by Reddit's own AB587 filing, not by inference.

**5. Limitations stated without softening.** Single reviewer — inter-rater reliability is zero, and this is stated in the report exactly that way. Public-facing policies only — enforcement practice is not the same as written policy. English-language only. Policies may have changed since May 2025. None of these limitations are buried.

---

## Repository Architecture

<img width="1100" height="480" alt="architecture" src="https://github.com/user-attachments/assets/f5f4e9be-7b05-4b7e-9cc5-8dd486600c11" />

```
PolicyMap/
│
├── PolicyMap_Report_v1.0.docx
│   └── ~10,000 words · ~35 pages
│       Executive Summary · Methodology · 4 Platform Profiles
│       Cross-Platform Matrix · 23-gap Gap Analysis
│       4 Recommendations · Appendices A/B/C
│       All policy claims → primary source · May 2025
│
├── PolicyMap_Audit_Matrix.xlsx
│   ├── Tab 1: Master Matrix
│   │   └── 48 cells (12 categories × 4 platforms)
│   │       Specificity scores · enforcement · appeal · exception Y/N
│   │       Source URLs · verbatim quotes per cell
│   ├── Tab 2: Gap Register
│   │   └── All 23 gaps · Platform A/B quotes · real-world scenarios
│   │       Severity ratings · harmonisation recommendations
│   └── Tab 3: Platform Profiles
│       └── Aggregate scores · unique features · strength ratings
│
├── PolicyMap_ViolenceDecisionTree.html
│   └── 711 lines · 29.2 KB · 6-node YES/NO flowchart
│       Colour-coded: Red/Amber/Grey/Blue/Green
│       GAP-003 callout embedded · Printable to PDF · No dependencies
│
├── README.md
├── CHANGELOG.md
├── .gitignore
│
├── docs/
│   └── index.html — GitHub Pages landing page
│
├── research_notes/
│   ├── YouTube_notes.md   — 9 verbatim quotes · EDSA framework · score rationale
│   ├── Reddit_notes.md    — 10 verbatim quotes · misinfo absence · AB587/S895B
│   ├── TikTok_notes.md    — 15 verbatim quotes · FYF tier · regional modulation
│   └── Meta_notes.md      — 8 verbatim quotes · Jan 2025 changes · Oversight Board
│
└── sources/
    ├── sources_master_list.csv   — 34 primary source URLs
    │                               Platform · Category · Access Date · Section Map
    └── policy_excerpts.md        — 42 verbatim quotes tagged with source IDs
```

---

## Four Key Verbatim Quotes

These were fetched from live policy pages during research. Full citations with access dates are in `sources/policy_excerpts.md`.

**YouTube** — on perpetrator footage:
> *"Footage filmed by the perpetrator during a deadly or major violent event, in which weapons, violence, or injured victims are visible or audible [is not allowed even with EDSA context]."*
> — support.google.com/youtube/answer/2802008, accessed May 2025

This is YouTube's hardest documented rule. No amount of educational framing, documentary context, or news value overrides it. No other platform in the audit has an equivalent written restriction.

**Reddit** — from AB587 Q4 2023 filing with the California Attorney General:
> *"Reddit's Content Policy more broadly prohibits content manipulation (Rule 2) and impersonation in a misleading or deceptive manner (Rule 5)."*
> — oag.ca.gov, Q4 2023

The filing lists every site-wide rule that maps to a regulated category. Misinformation is absent. The gap is confirmed by Reddit's own regulatory submission.

**TikTok** — on FYF eligibility:
> *"When we identify content that falls under the 'FYF Ineligible' standards in our Community Guidelines, it won't be recommended in the FYF."*
> — tiktok.com/community-guidelines/en/fyf-standards, confirmed live May 2025

The only place in four platforms' policy documents where de-amplification is documented as a formal enforcement action distinct from removal.

**Meta** — on LGBTQ+ hateful conduct (added January 2025):
> *"We do allow allegations of mental illness or abnormality when based on gender or sexual orientation, given political and religious discourse about transgenderism and homosexuality."*
> — transparency.meta.com/policies/community-standards/hateful-conduct/, confirmed live May 2025

Added January 2025. Rebuked by Meta Oversight Board April 2025. Not reversed as of research date.

---

## Deliverables Summary

| File | Format | Size | What It Contains |
|---|---|---|---|
| `PolicyMap_Report_v1.0.docx` | Word | ~35 pages | Full audit narrative — profiles, gap deep-dives, methodology, limitations, recommendations |
| `PolicyMap_Audit_Matrix.xlsx` | Excel | 3 tabs | Every number behind the README — 48-cell matrix, 23-gap register, platform profiles |
| `PolicyMap_ViolenceDecisionTree.html` | HTML | 29.2 KB / 711 lines | Interactive flowchart — open in browser, print to PDF, no dependencies |
| `research_notes/*.md` | Markdown | 4 files | Working documents — all verbatim quotes, score rationale, access dates |
| `sources/sources_master_list.csv` | CSV | 34 rows | Every primary source URL with access date, platform, category, and report section |
| `sources/policy_excerpts.md` | Markdown | 42 quotes | Tagged verbatim excerpts cross-referenced to source IDs |

---

## Policy Change Monitor

The CHANGELOG documents which policies are most likely to have changed since the May 2025 research date. Verify before any operational use.

| Platform | Policy | Change Likelihood | Monitor At |
|---|---|:---:|---|
| Meta | Hateful Conduct | 🔴 HIGH | transparency.meta.com/policies/community-standards/hateful-conduct/ |
| Reddit | Content Policy | 🔴 HIGH | redditinc.com/policies/content-policy |
| TikTok | FYF Standards | 🟡 MEDIUM | tiktok.com/community-guidelines/en/fyf-standards |
| YouTube | Medical Misinformation | 🟡 MEDIUM | support.google.com/youtube/answer/13813322 |
| All | Election Misinformation | 🔴 HIGH during cycles | All platform Community Guidelines pages |

---

## Who This Is For

**Trust & Safety professionals** who need a cross-referenced primary-source view of how four major platforms handle identical content categories — not press releases, not platform-authored transparency summaries, but the actual policy text side by side.

**Policy researchers and journalists** who need a sourced, structured comparative starting point with citations they can independently verify. Every source URL is in `sources/sources_master_list.csv` with its access date.

**Creators** who want to understand exactly why the same video gets removed on TikTok and age-gated on YouTube and marked NSFW on Reddit — and what the policy document actually says caused that difference.

**Academics** working on platform governance, content moderation, or media law who need a rigorous entry point into any of the 12 categories, with documented methodology and stated limitations.

---

## Citation

```
PolicyMap: A Cross-Platform Community Guidelines Audit for Trust & Safety Professionals.
Version 1.0. Research date: May 2025. Primary policy sources accessed May 2025.
https://github.com/sat1828/PolicyMap
```

---

## Disclaimer

Independent academic analysis. Not affiliated with or endorsed by YouTube, Reddit, TikTok, Meta, or any of their parent companies. All policy citations are from primary platform policy documents accessed May 2025. Policies change — verify currency before any operational use.

---

<div align="center">

*34 primary sources · 42 verbatim quotes · 4 platforms · 12 categories · 23 gaps · 0 secondary sources used for policy claims*

</div>
