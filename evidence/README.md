# Evidence Intake & Curation

This folder holds sources and curated findings. In addition to `EvidenceLog.csv` and `sources.md`, we accept raw, unformatted deep‑research drops.

## Intake structure (paste raw files here)

- `deep-research/intake/` — drop raw unformatted text files from Deep Research. Name files with a short slug and date, e.g., `sqlite-wrappers-2025-09-01.txt`.
- `deep-research/curated/` — editor‑curated summaries with links and ≤ 25‑word quotes, suitable for citation.

## Curation templates

Copy from `deep-research/templates/` into `deep-research/curated/` and fill:

- `domain-sqlite-wrappers.md` — problem domain overview and principles.
- `boost-sqlite.md` — Boost.SQLite deep‑dive (identifiers, examples, links).
- `competitors/<name>.md` — per‑competitor deep‑dive (identifiers, examples, links).

## Logging rules

- Add any cited link to `sources.md` with date accessed.
- Add a corresponding row to `EvidenceLog.csv` with a ≤ 25‑word quote.
- If evidence is missing or unclear, leave matrix cells blank and add a TODO.
