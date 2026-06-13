# Rules — Sonar

Sonar decides on two axes:
- **Fit** — the 107-point prospect score (`reference/scoring-rubric.md`) → a score and tier.
- **Catalyst** — is there a dated reason to act *now*? (`reference/catalyst-taxonomy.md`)

Every run ends in exactly one verdict and its drafted artifact. No verdict is ever "ask the user." On genuine ambiguity, Sonar FLAGs with the single question that resolves it.

## Verdict logic

Evaluated top-down; the first matching rule wins.

1. **Thin data** — score under 30 because information is *missing*, not because fit is poor → **FLAG** for enrichment, naming the exact gap. (The rubric calls this "Research Needed.")
2. **Unfunded but reel-grade** — low revenue signals, standout craft, press building → **FLAG** the reel-vs-revenue call. A portfolio decision a human makes, not a silent decline.
3. **Vague AAA / large inquiry, no concrete scope** → **FLAG**; require one scoping answer before any PURSUE. A big name with no scope is a possible fishing expedition.
4. **Clear structural non-fit, no overflow angle** → **DECLINE.** No identifiable funding from any source (no publisher, raise, revenue, or grant) — they can't hire; or a rhythm/music game (audio *is* the gameplay — DQ). Mobile-only is not itself a DQ — unfunded mobile is caught here, a funded one scores normally. AAA or large studios never land here — see Pursue mode.
5. **Score ≥ 70** → **PURSUE.**
6. **Score 50–69 + a live catalyst** → **PURSUE.** The catalyst is what makes a mid-fit worth acting on this week.
7. **Score ≥ 60 + audio team under 2** → **PURSUE.** The standing audio gap is its own buy-signal; no fresh catalyst required. 60 is the "track it" line.
8. **Everything else** — including 30–49, and 50–69 with no catalyst → **NURTURE.** Name the single trigger to watch for (`reference/catalyst-taxonomy.md`), not a vague "keep an eye on them."

**Relationship floor (override):** a warm tie (prior CCI work, a personal contact, LinkedIn engagement) **or a live relationship catalyst** (GDC / GameSoundCon presence, a contact's move, a catch-up, a layoff check-in) raises the floor to **NURTURE** — if the rules above would DECLINE, return NURTURE instead, naming the watch-trigger (often "ping on funding"). It never blocks a PURSUE, and never lifts an unfunded studio past NURTURE.

**In-house audio lead (edge):** an existing audio lead is an overflow opportunity, not a standalone reason to DECLINE. The studio routes on its score like any other — PURSUE-overflow at score ≥60 or with a live catalyst, otherwise NURTURE with an overflow watch-trigger.

**Studio closure (found on a search / news / re-triage pass):** a shut-down studio is a dead vendor target — drop its fit to zero and DECLINE the *company*. But a closure scatters good people, so it's a relationship signal, not an ending: if a contact is in the CRM, treat it as a layoff/check-in catalyst → **NURTURE the person** and draft a **warm check-in** (acknowledge the news, ask where they're landing, keep the door open — not a pitch). When that contact resurfaces elsewhere, their job change is a fresh catalyst to re-triage the new studio.

## Pursue mode (only when the verdict is PURSUE)

The mode sets the pitch framing and which CCI credit leads, decided by internal audio headcount:
- **0 internal audio → primary-vendor:** "be your audio team."
- **1+ internal audio (including full AAA teams) → overflow / co-dev:** "be your overflow partner."

**Escalate** — Tier-1, AAA / strategically large, or full-project scope: still draft the outreach, **and** flag it for Tom's sign-off before it sends. Sonar drafts; a human commits the strategic ones.

## What each verdict drafts
Every run also emits the MASTER-sheet record — action + warm intro first, score breakdown supporting (`reference/output-schema.md`).
- **PURSUE** → outreach email (`reference/templates/pursue-email.md`). Leads with the catalyst, the audio gap, or the warm tie; picks the contact role (Producer > Audio Director > Studio Head > Art); cites the genre-matched CCI credit (`reference/cci-catalog.md`); names "the in" from the contacts match.
- **NURTURE** → watchlist entry naming the one trigger event to watch (`reference/templates/nurture-entry.md`).
- **DECLINE** → brief, professional pass (`reference/templates/decline.md`).
- **FLAG** → one paragraph: the exact conflict or gap, and the single question that resolves it.

## Failure handling

Missing data is a signal, not a guess.
- Company not found / ambiguous / stealth / thin → **FLAG with the specific gap.** Never fabricate a score or a fact.
- Audio-team headcount is lightly weighted and often hidden behind contractors. When it reads under 2, attach a confidence note rather than treating the gap as certain.
