# Scoring Rubric

The **fit** axis. Sonar reads this against the catalyst axis to reach a verdict (see `../rules.md`). A 107-point framework producing a score and tier. Three recalibration principles:
- **Size is a signal, not a gate.**
- **An existing audio team is an overflow signal, never a disqualifier.**
- **Funding is the gating cluster** — a studio with no funding from *any* source can't hire (see Disqualifiers).

## 107-Point Scoring Framework

| Criteria | Points | Notes |
|---|---|---|
| Audio Team Gap | 22 | 0 internal = 22. 1–2 = 13. 3–4 = 5. 5+ = 0 (no gap — an *overflow* signal, never a DQ). Core value-prop. See the confidence note. |
| Publisher Backing | 18 | Major publisher = 18. Smaller / indie publisher = 10. Self-published, no publisher = 0 (other funding may score below). Unknown = 5. |
| VC / Other Funding | 12 | Any non-publisher funding source. $10M+ raised = 12. Smaller raise = 7. Notable revenue / grant / crowdfund = 5. None = 0. |
| Active Development | 12 | In production on an unshipped title = 12. Shipped in the last 12mo = 8. Between projects = 3. Proximity-to-need. |
| Platform: PC/Console | 10 | PC/Console = 10. Mixed incl. mobile = 6. Mobile-only = 0 (not a DQ — see filters). |
| Genre Audio Needs | 10 | High = 10 · sports/fighting = 7 · puzzle/casual = 4 · rhythm/music = DQ. Scale below. |
| Existing CCI Relationship | 10 | Prior CCI work = 10 (WARM LEAD — `../rules.md` sets a NURTURE floor; flag explicitly). |
| Company Size | 8 | Sweet spot 50–75 = 8. 25–200 = 5. <25 or >200 = 3. **Never a gate, never zero** — large studios route to overflow. |
| Geographic Proximity | 5 | California = 5. Other North America = 3. International = 1. |

**Maximum: 107.** Thresholds (70 / 60 / 50 / 30) are calibrated to this max — see Tiers. **Publisher + VC/Other = 30 points of funding signal**, the heaviest cluster: budget is what makes a studio able to hire.

### Genre scale (within the 10 Genre points)
- **High (10):** RPG · shooter · action-adventure · horror · VR · narrative.
- **Mid-high (7):** sports · fighting / wrestling. (CCI's NBA 2K / WWE credits — corrects the old "sports = 5.")
- **Low (4):** puzzle · casual.
- **DQ (filter):** rhythm / music games — audio *is* the gameplay. Routes to DECLINE (see `../rules.md`).

### Audio-gap confidence note
Audio headcount is often hidden behind contractors and uncredited work. When it reads under 2, score the gap but attach a confidence note rather than treating the gap as certain.

---

## Tier Definitions

Reconciled with `../rules.md` — the verdict logic governs the *action*; this table sets the tier *label*.

| Tier | Score | Meaning |
|---|---|---|
| Tier 1 — Priority | 70+ | Strong fit → PURSUE. Escalate Tier-1 / AAA / full-scope to Tom. |
| Tier 2 — Strong Fit | 50–69 | PURSUE with a live catalyst, or if audio team <2 at 60+; otherwise NURTURE. **60 is the "track it" line.** |
| Tier 3 — Possible Fit | 30–49 | NURTURE — name the trigger to watch. |
| Research Needed | <30 | Thin data, not necessarily poor fit → FLAG for enrichment. |

---

## Disqualifiers & filters

Route to a verdict regardless of score:
- **No funding from any source** (no publisher, raise, notable revenue, or grant/crowdfund) → **DECLINE** — they can't hire. Exceptions (see `../rules.md`): reel-grade craft → **FLAG** (reel-vs-revenue); a warm tie or relationship catalyst → **NURTURE** (keep-warm watchlist).
- **Rhythm / music game** → **DECLINE** (audio is the gameplay).
- **In acquisition / transition** → **FLAG** (timing uncertain); don't treat the score as final.
- **Studio closed / shut down** → dead target: drop fit to zero and DECLINE the company. But a closure is a relationship catalyst — with a known contact, pivot to a person-level check-in (`../rules.md`).

**Not disqualifiers** (recalibrated — these used to auto-fail):
- **Studio size** — large headcount never disqualifies; it lowers the size signal and routes to overflow / co-dev.
- **5+ internal audio staff** — scores 0 on the gap, but is an *overflow* opportunity, not a DQ. AAA is never auto-declined.
- **Mobile-only** — scores 0 on platform, not a standalone DQ. Unfunded mobile is caught by the funding filter; a funded or sizable mobile studio scores normally (Marvel Snap precedent).

---

## Audio Team Gap Detection

To gauge the gap (the heaviest single criterion — 22 pts):
- Search LinkedIn: "[Company] sound designer" / "[Company] audio."
- Check MobyGames credits for recent games — who did the audio?
- Check current job postings — are they hiring audio? (Also a catalyst.)
- Check the company website About / Team pages.
- Check shipped-game credits.

No audio staff on LinkedIn + credits show outsourced audio → score 22. Apply the confidence note: absence of evidence is often contractor-hidden audio, not a confirmed gap.

---

## Conference presence

GDC / GameSoundCon attendance is a **catalyst** (a reason to act *now*), not a fit-score bonus — see `catalyst-taxonomy.md`. It no longer adds points here.

---

## Scoring Example

**Northpeak Games (Seattle, illustrative):**
no internal audio (22) + in production (12) + no major publisher, VC-funded (publisher 0) + $40M raised (12) + PC (10) + shooter / high genre (10) + ~50 employees, sweet spot (8) + other NA (3) + no CCI relationship (0) = **77 → Tier 1.** The $40M raise alone clears the funding filter — any source counts.

---

## Output

Sonar's output maps to the MASTER sheet — see `output-schema.md` for the column map and the column-15 record format. Contacts come from `contact-list.md`.
