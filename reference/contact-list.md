# Contact List — Template & Demo Rows

The compliant, manual input for "the in." Sonar matches a prospect to this list on **Company**, picks the contact by **role priority**, and reads **warmth** to choose the opening. No scraping — this is the team's own CRM export.

## Schema (Contacts CRM)
`Name · Company · Contact Info · Days Since Contact · Follow-up Date · Last Contact · LinkedIn · Notes · Overdue · Role · Status · Where Met`

## How Sonar uses it
- **Match** on `Company` (exact, then fuzzy).
- **Role priority** for the target: **Producer > Audio Director > Studio Head > Art** (`../rules.md`, methodology).
- **Warmth ladder** (`Status` + `Where Met`): **Existing CCI > Warm > 2nd-degree intro > Cold.** Warmer = a more personal opening; warm contacts skip generic outreach.
- **`Overdue = Yes`** is a built-in catch-up excuse — a live **relationship catalyst** (`catalyst-taxonomy.md`).
- No match → outreach goes cold: lead with the catalyst or the audio gap, and pick the role from the studio's org chart, not this list.

## Demo rows (obscured — illustrative names only)

| Name | Company | LinkedIn | Last Contact | Overdue | Role | Status | Where Met |
|---|---|---|---|---|---|---|---|
| Glen Ostrander | Harborlight Studio | /in/demo-gostrander | Apr 28, 2026 | Yes | Studio Head | Existing CCI | Prior project |
| Dana Reyes | Lumen Hollow Games | /in/demo-dreyes | May 2, 2026 | No | Executive Producer | Warm | GDC 2025 |
| Priya Anand | Northwind Interactive | /in/demo-panand | Feb 14, 2026 | No | Audio Director | 2nd-degree (via Tom) | Referral |
| Marcus Vale | Tidewright Studios | /in/demo-mvale | Mar 13, 2026 | Yes | Senior Sound Designer | Cold | LinkedIn |
| Iris Mok | Saltmarsh Two | /in/demo-imok | Jun 1, 2026 | No | Founder | Cold | Twitter/X |

Each ties to a demo studio in `../examples.md`: **Lumen Hollow** (PURSUE — a warm Producer is the in), **Tidewright** (NURTURE/overflow — the in-house lead, and `Overdue` gives the catch-up), **Saltmarsh Two** (FLAG). Harborlight and Northwind show the warmest rungs (Existing CCI, a 2nd-degree intro via Tom).
