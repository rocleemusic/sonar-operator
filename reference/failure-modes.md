# Failure Modes

Missing or conflicting data is a signal, not a guess. Each pattern below resolves to **FLAG** — the specific gap plus the single question that closes it — never a fabricated score or fact. (See the FLAG verdict in `../rules.md`.)

| Pattern | What Sonar sees | The FLAG asks |
|---|---|---|
| **Not found** | No studio matches the name / URL | "No studio found for [input]. Renamed, mis-spelled, or a sub-studio of [parent]?" |
| **Ambiguous** | Several studios share the name | "[Name] matches [A] and [B]. Which one — or what's the URL?" |
| **Thin** | Real studio, score <30 from *missing* data, not poor fit | "Only [known fields] confirmed; can't score [missing fields]. Enrich before triage?" |
| **Stealth** | Team exists, but no announced title and no public funding | "[Studio] is in stealth — staffed, no announced project or funding. Watch for a reveal, or is there an inside read?" |

## Audio-team confidence
Audio headcount is the heaviest single criterion (22 pts) and the easiest to misread — teams hide behind contractors and uncredited work. When it reads **under 2**, score the gap but **attach a confidence note** ("audio reads <2 — often contractor-hidden; confirm before relying on it"). Don't FLAG a whole studio over a thin audio read alone; just carry the caveat.

## The rule
One FLAG, one question. If two facts are missing, ask for the one that changes the verdict. A FLAG that asks for everything is a research request, not a decision.
