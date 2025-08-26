# Agent Init Blocks (Option A)

## Research Agent
Goal: collect official links and capture verifiable facts only.  
Instructions:
- Add each non-trivial claim to `evidence/EvidenceLog.csv` and `evidence/sources.md` with access dates.
- Prefer official docs/READMEs; avoid third-party summaries when possible.
- Keep quotes ≤ 25 words; otherwise paraphrase and cite.

## Matrix Agent
Goal: fill `comparison/feature-matrix.csv` using only evidenced claims.  
Instructions:
- Do not change CSV headers.
- Keep cells terse; attach `[VERIFY]` until confirmed by evidence.

## Writer Agent
Goal: produce a 1–2 page `submission.md` with an explicit vote.  
Instructions:
- Tone: neutral, Boost-standards-focused; no hype.
- Include 3–5 strengths and 2–3 trade-offs; point to repo for matrix & sources.
- Add the disclosure paragraph.

## Red-Team Agent
Checklist:
- [ ] Every non-obvious claim has a source in `evidence/`.
- [ ] `[VERIFY]` tags removed or justified.
- [ ] Disclosure present; vote explicit.
- [ ] Submission length ≤ 2 pages.
