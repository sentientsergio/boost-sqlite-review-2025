# Comparison Notes (how to read the matrix)

- Cells marked **[VERIFY]** are seeded expectations. Replace them only after checking the official docs/README of each library.
- Keep the scope aligned with Option A (light comparison). Avoid deep performance claims unless first-party and clearly scoped.
- If evidence is missing, leave the cell blank and add a TODO in this file rather than guessing.
- Treat `sqlite_orm` as an ORM layer (a different category) and explain trade-offs succinctly.

## Deep-Research Curation flow (for this matrix)

- Use curated files from `evidence/deep-research/curated/` as the single source of truth for competitor summaries.
- If a cell lacks a first-party citation, leave it blank and add a TODO here with a pointer to the intake file.
- Prefer naming concrete identifiers (types/functions) in notes when clarifying differences.
