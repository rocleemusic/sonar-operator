# Research Sources

## Source Priority Order

Work through these in order. Stop when you have enough data to score confidently.

1. **LinkedIn** — Employee count, job postings (especially audio roles), key contacts
2. **MobyGames** — Game credits, audio staff history: `mobygames.com/company/[id]`
3. **Crunchbase** — Funding rounds, investors, founding date
4. **IGDB / Giant Bomb** — Game titles, release dates, platforms
5. **Publisher press releases** — Announced titles, dev status
6. **Job boards** (Hitmarker, Games Industry Biz) — Active audio job postings reveal team gaps
7. **GDC session schedule** — Confirms attendance for conference targeting

---

## Known Challenges

- **LinkedIn direct fetching consistently fails** — pivot immediately to web search for LinkedIn data
- **Funding data conflicts** — cross-reference Tracxn, press releases, and PitchBook; they often disagree. Note the discrepancy in your analysis.
- **Publisher relationships often matter more than studio size** — a small studio with a major publisher deal scores higher than a mid-size studio without one
- **Sequential narrowing searches work best for sparse indie studio data** — start broad, narrow by platform/genre/location

---

## Audio Gap Search Protocol

Run these in order to detect whether a studio has in-house audio:

1. LinkedIn search: `"[Company] sound designer"` or `"[Company] audio"`
2. MobyGames credits on their most recent shipped title — who did audio?
3. Current job boards — are they actively hiring audio roles?
4. Company website About/Team page
5. Shipped game credits (end credits often list outsourced audio vendors)

**Signal:** No audio staff on LinkedIn + outsourced credits = strong audio gap → score 20 pts
