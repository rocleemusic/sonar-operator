# Output Schema

Every triage emits one record that **pastes straight into the MASTER sheet** — that's the CRM plug-in for v1. The primary cell is **column 15** (`CLAUDE NOTES / Warm Intro / Recommended Action / Score Breakdown`). The reader sees **the call and the opening first, the math second.**

## Column 15 — the record

```
[VERDICT] · [pursue mode, if PURSUE]
Action:   [the one next step — who to contact, about what]
The in:   [warmth-ladder result — name, role, tie; or "cold — no CRM match"]
Score:    [N]/107 · Tier [n] — [the 2–3 drivers]; [verdict path]
Catalyst: [type + the dated signal]      // if any
Flag:     [the gap + the one question]   // FLAG only
```

Concrete (obscured):

```
PURSUE · primary-vendor
Action:   Email Dana Reyes (Exec Producer) — October ship date, no audio team yet.
The in:   Warm — Dana Reyes, met at GDC 2025 (CRM).
Score:    69/107 · Tier 2 — audio gap 22, active dev 12, horror/narrative 10; PURSUE via live catalyst.
Catalyst: project — announced October ship window.
```

## Columns Sonar writes / updates

| Col | Field | Fills with |
|---|---|---|
| **15** | CLAUDE NOTES / Warm Intro / Recommended Action / Score Breakdown | **the record above (primary output)** |
| 2 | Score | the 0–107 total |
| 4 | CONTACTS | the matched contact + role (`contact-list.md`) |
| 5 | ACTION ITEM | the action line, restated |
| 8 | In-House Audio Credits / GDC attendees | the audio-gap read + confidence note |
| 9–13 | External Audio · Location · Est. Size · Funding/Ownership · Website | from the research pass |
| 14 | Why They're a Good Target / Key Insight | the one-line fit thesis |
| 16–20 | Platform · Genre · Notable Titles · Released (Year) · Dev Status | from the research pass |

Human-owned columns — **NOTES (3), ASSIGNED (7), DATE OF LAST CONTACT (6)** — are left alone unless empty.

## The drafted artifact

Alongside the record, Sonar drafts the verdict's artifact (`../rules.md`):
- **PURSUE** → outreach email — target = top role present (Producer > Audio Director > Studio Head > Art); proof-line = the genre-matched CCI credit (`cci-catalog.md`); opening = the in (`contact-list.md`).
- **NURTURE** → watchlist entry: the one trigger to watch.
- **DECLINE** → brief, professional pass.
- **FLAG** → the gap + the single question (`failure-modes.md`).

## Re-triage — the sheet is the state

A company already in the sheet → don't overwrite. **Diff** the new read against the prior row and propose the update (score moved, catalyst fired, contact warmed). The MASTER sheet *is* Sonar's memory.
