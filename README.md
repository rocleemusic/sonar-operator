# Sonar — Prospect Qualification Operator

Drop this folder into a Claude project and Sonar becomes a first-pass business-development screener for a boutique game-audio studio. Give it a studio — a name, a URL, or a pasted inbound inquiry — and it returns one decision and the response that decision needs: an outreach email to PURSUE, a watchlist entry to NURTURE, a brief professional DECLINE, or a FLAG for the one call a human should make. It decides; it never hands the question back.

## Setup
1. Create a project in Claude (claude.ai → Projects, or Claude Desktop). Enable web search — Sonar researches live.
2. Add every file in this folder to the project's knowledge.
3. *(Optional, for "the in")* Add the team's Contacts CRM export — schema and demo rows are in `reference/contact-list.md`. Add the MASTER target sheet to re-triage against prior rows.
4. Project instructions: *"Read identity.md and rules.md. You are Sonar. Decide, don't ask — return one verdict and its drafted artifact."*

## Use it
Paste `Qualify [studio name]: [url]` — or paste an inbound inquiry.
Expect back: the fit score and tier, the catalyst (or its absence), the verdict, the **column-15 record** that pastes straight into the sheet, and the drafted response. Not a question.

See `examples.md` for five worked decisions — one per verdict, plus a not-found failure. It doubles as the calibration set.

## What's in the folder
| File | Its one job |
|---|---|
| `identity.md` | Who Sonar is, what it owns, what it refuses |
| `rules.md` | The verdict logic, pursue modes, edges, escalation — the heart |
| `examples.md` | Five worked decisions / the calibration set |
| `reference/scoring-rubric.md` | The 107-point fit framework (the fit axis) |
| `reference/catalyst-taxonomy.md` | What counts as a reason to act now (the catalyst axis) |
| `reference/cci-catalog.md` | Featured work by genre — the credit a PURSUE cites |
| `reference/contact-list.md` | The contacts schema + how "the in" is chosen |
| `reference/output-schema.md` | The column-15 record + the sheet column map |
| `reference/failure-modes.md` | When to FLAG instead of guess |
| `reference/research-sources.md` | Where to look, in priority order |
| `reference/templates/` | Drafted-response templates, one per verdict |

## Make it yours
Sonar screens game-audio prospects, but the shape is generic. Swap three files and it qualifies prospects for any vendor business: `scoring-rubric.md` (your ICP and weights), `catalyst-taxonomy.md` (your reasons to act now), and `cci-catalog.md` (your proof/credits). The verdict logic in `rules.md` carries over unchanged.

## Roadmap
v1 output pastes into the target sheet — that's the CRM plug-in, by hand. Next: a live CRM / chat-bot front end that watches the team's prospect channel, runs the triage, and posts the verdict in-thread.
