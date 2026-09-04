# Methodology — Corporate Track Record

> 🇨🇳 [中文版](METHODOLOGY.zh-CN.md)

## 1. Purpose and current scope

Corporate Track Record is a **source-backed, bilingual documentation
repository** about the publicly known conduct of companies as *employers*,
with emphasis on:

1. the companies themselves (the "record"),
2. how their **downstream customers / supply-chain partners responded**
   (investigations, audits, contract measures, statements), and
3. what a worker or consumer should reasonably watch out for.

**Current state (2026-09):** the repository only accepts **blacklist**
entries (verified labor-conduct controversies). A **red list** (exemplary
employers) is planned; the directory and file schema below already support
it, so no future restructuring is needed. Folders are named `cases/`, not
`blacklist/`, for this reason.

## 2. What qualifies for inclusion

An entry may be created only when **all** of the following hold:

- The company is clearly identifiable: full legal name (Chinese + English
  where available) and, if listed, exchange + ticker.
- The incident was already reported by **at least one authoritative media
  outlet** (national press, financial news wire, industry press with
  editorial standards) **or** is documented by an **official body**
  (labor bureau finding, court judgment, regulator statement, company
  announcement, investor-relations filing).
- Core facts are corroborated by **more than one independent source**, or
  by a single official document (e.g., a government notice).
- Every factual claim in the case file is linked to a numbered source with
  outlet, title, date and URL (see §5).

Mere rumours, anonymous forum posts, screenshots of chats without media
verification, or unproven single-person accusations do **not** qualify.

## 3. Evidence levels

Each case file marks claims so readers can tell apart:

| Level | Meaning | Example phrasing used |
|---|---|---|
| **[OFFICIAL]** | Government notice, court document, company announcement, regulator statement | "According to the Changzhou Human Resources and Social Security Bureau notice…" |
| **[MEDIA]** | Reported by an authoritative outlet, attributed to named reporters | "Nandu Bay Financial News reported…" |
| **[PARTY]** | Claim by affected individuals/employees, as relayed by media (may include recordings); inherently one-sided | "Affected graduates told reporters…" |
| **[MARKET]** | Analyst comment, speculation, market inference — NOT treated as fact | "Some analysts linked the timing to…" |

A case file may open **only** with facts at [OFFICIAL]/[MEDIA] level.
[PARTY] claims are always attributed ("alleged", "told reporters") and are
never the sole basis for the entry's headline classification.

## 4. Anti-misidentification rules (avoid false accusations)

1. **Title neutrally.** File titles describe the event ("2026 mass
   dismissal of 107 new graduates"), not a legal conclusion ("unlawful
   dismissal"), unless a court or regulator has made that finding.
2. **Complete narrative.** Always record the company's own response,
   the regulatory outcome, **and every downstream-customer response** we
   can find. A record that shows only one side is itself misleading.
3. **Separate facts from opinions.** Editorial/analyst comments go to the
   [MARKET] level and never into the facts summary.
4. **Dates are evidence.** Every timeline entry carries a date from a
   source; never reconstruct a date from memory.
5. **Status matters.** Update the `Status:` field when the case develops;
   "under investigation" must never be written as "confirmed guilt".
6. **Protect individuals.** Affected workers are referred to the way the
   reporting outlets did — normally pseudonymised. No home addresses,
   personal ID numbers, phone numbers or private photos of individuals.
7. **Corrections.** Errors are fixed by PR or issue, and the correction is
   logged in the case file's "Corrections" section. Errata are not
   silently edited away.

## 5. Source rules

- Numbered sources `[1]…[n]` at the bottom of each case file, in both
  language versions. When an item first breaks and later develops, keep
  the original source AND add the follow-up.
- Required per source: outlet, title, publication date, URL, and (where
  useful) the specific claim it supports.
- Prefer primary over secondary: official notices and company filings over
  commentary; dated articles over AI-generated summaries.
- If a fact is only available from a single source, say so explicitly in
  the text ("reported only by…, unverified elsewhere").

## 6. Downstream-response tracking

If the recorded company is a supplier (as in most cases), the case file
MUST contain a dedicated section *"Downstream customer & partner
responses"* listing every response found — e.g.:

- customer launched / completed an audit or investigation,
- customer issued a public statement,
- customer paused or terminated purchase orders,
- customer requested remediation and follow-up verification,
- customer publicly declined to comment (also worth noting).

When the case file is updated, this section is re-checked and its
"as of" date updated.

## 7. File schema

```
corporate-track-record/
├── README.md               # EN index (default language)
├── README.zh-CN.md         # 中文索引
├── METHODOLOGY.md          # this file (EN)
├── METHODOLOGY.zh-CN.md
├── CONTRIBUTING.md
├── LICENSE                 # CC BY 4.0
└── cases/
    └── <entity-slug>/      # e.g. xingyu-601799
        ├── en.md           # EN case file
        └── zh.md           # 中文案件档案
```

- **English is the default language**; every page carries a switch link at
  the top (`🇬🇧 EN` / `🇨🇳 中文`).
- Case slugs use the company's romanised short name + ticker/registration
  suffix to stay unique, e.g. `xingyu-601799`.
- Every case file begins with the same metadata block:
  `Entity / Industry / Board verdict / First reported / Status /
  Last updated`, then: Summary → Facts → Timeline → Company response →
  Downstream responses → Regulatory → Implications for workers →
  Sources → Corrections.

## 8. Disclaimers

- Recording a controversy is **not** a finding of liability; inclusion
  reflects that the event is publicly documented, nothing more.
- Nothing here is legal advice or investment advice.
- Companies are welcome to respond: see CONTRIBUTING.md for the reply
  process. Responses are added to the case file with their sources.
