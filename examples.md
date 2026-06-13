# Examples — Sonar

Six worked decisions — the calibration set. Studio and contact names are obscured. Each shows the read, the verdict and the rule that fired (`rules.md`), and the column-15 record (`reference/output-schema.md`).

## 1. PURSUE (primary-vendor) — funded studio, live catalyst
**Input:** "Lumen Hollow Games — lumenhollow.example. Announced an October ship date for their narrative-horror title."
**Read:** ~40 staff (size 5) · no audio in credits or on LinkedIn (22) · seed-funded, self-published (publisher 0, seed raise 7) · PC (10) · horror/narrative (10) · in production (12) · NA (3) = **69 · Tier 2.** Catalyst: announced October ship date (project). 0 internal audio → primary-vendor.
**Verdict: PURSUE** — rule 6 (Tier-2 + live catalyst). The in: Dana Reyes (Exec Producer), warm from GDC 2025.
```
PURSUE · primary-vendor
Action:   Email Dana Reyes (Exec Producer) — October ship date, no audio team yet.
The in:   Warm — Dana Reyes, met at GDC 2025 (CRM).
Score:    69/107 · Tier 2 — audio gap 22, active dev 12, horror/narrative 10; PURSUE via live catalyst.
Catalyst: project — announced October ship window.
```
**Draft (pursue-email):** lead on the October date + the missing audio team; cite the RPG/narrative credit (*Starfield*); one soft ask.

## 2. NURTURE (overflow watch) — in-house lead, one point under the line
**Input:** "Tidewright Studios — they list a Senior Sound Designer on the team page."
**Read:** 1 in-house audio lead (13) · recently shipped (active dev 8) · small publisher (10) · PC (10) · action genre (10) · ~80 staff (size 5) · NA (3) = **59 · Tier 2.** No project catalyst.
**Verdict: NURTURE** — rule 8. One point under the **60** overflow-pursue line, so it watches rather than pursues; the in-house lead sets *overflow* mode for when it crosses. Marcus Vale is `Overdue` in the CRM — a relationship catalyst, a warm reason to reconnect now (it doesn't promote a Tier-2 to PURSUE, but it shapes the nurture).
```
NURTURE · overflow angle
Action:   Watchlist — ping on a new project or audio job post (overflow opens at 60+). Soft catch-up with Marcus now.
The in:   Weak — Marcus Vale (Sr. Sound Designer) is cold but overdue for a catch-up (CRM).
Score:    59/107 · Tier 2 — audio 13, genre 10, active dev 8; one point under the 60 line.
Catalyst: relationship — Marcus overdue.
```

## 3. FLAG (reel-vs-revenue) — high fit on paper, no money
**Input:** "Saltmarsh Two — solo dev, no funding, but the vertical slice is gorgeous and getting press."
**Read:** solo, no audio (22) · in production (12) · PC (10) · narrative (10) · <25 staff (3) · NA (3) · **no funding from any source (publisher 0, VC 0)** = fit **60** — but they can't hire.
**Verdict: FLAG** — rule 2 fires before the no-funding DECLINE (rule 4). Standout craft is a portfolio call, not a revenue one, and that belongs to a human. Contrast example 4: same "unfunded," but with no reel value it's a DECLINE.
```
FLAG · reel-vs-revenue
Action:   Human call — is our Q3 reel slate full?
The in:   Iris Mok (Founder), cold (CRM).
Score:    60/107 fit — but zero funding → can't hire on normal terms.
Flag:     Reel-grade slice + building press, no budget. Discounted/portfolio engagement, or pass?
```

## 4. DECLINE — no funding, no reel value, no tie
**Input:** "Pebblewick Games — 4-person team, mobile puzzle game, bootstrapped, no press."
**Read:** no audio team (22) · in dev (8) · **no funding from any source** · mobile-only (platform 0) · puzzle (genre 4) · <25 staff (3) · NA (3) = **~40 · Tier 3 on paper.**
**Verdict: DECLINE** — rule 4 (no funding → can't hire). The Tier-3 score alone would say NURTURE, but the funding filter fires first, and there's no reel-grade craft or relationship catalyst to lift it (the difference from example 3). Mobile-only and puzzle only deepen the miss.
```
DECLINE
Action:   Brief, professional pass.
The in:   No CRM match.
Score:    ~40/107 · Tier 3 on fit — but no identifiable funding → can't hire.
```

## 5. FLAG (not found) — the failure path
**Input:** "Triton Reef Games — can't find them anywhere."
**Read:** no studio matches the name or any URL. Missing data is a signal, not a guess (`reference/failure-modes.md`).
**Verdict: FLAG.** Sonar never fabricates a studio to fill the row.
```
FLAG · not found
Action:   Confirm the input before triage.
Score:    —
Flag:     No studio found for "Triton Reef Games." Renamed, mis-spelled, or a sub-studio of a parent?
```

## 6. Studio closure (found on a news / re-triage pass) — follow the person
**Input:** "Re-check Northwind Interactive — news says the studio shut down."
**Read:** studio closed → dead vendor target; fit drops to zero. But Priya Anand (Audio Director) is in the CRM (2nd-degree, via Tom).
**Verdict: DECLINE the company; NURTURE the person.** A closure is a check-in catalyst, not an ending — draft a warm note and follow her to her next studio (where her job change becomes a fresh catalyst to re-triage).
```
DECLINE (closed) · pivot to person
Action:   Warm check-in to Priya Anand — not a pitch. Flag her next move to re-triage.
The in:   Priya Anand (Audio Director), ex-Northwind, 2nd-degree via Tom (CRM).
Score:    0/107 — studio shut down, dead target.
Catalyst: relationship — studio closure / check-in.
```
**Draft (check-in):** acknowledge the news, no pitch; ask where she's headed; offer to stay in touch — the relationship outlives the studio.
