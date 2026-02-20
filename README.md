# lab-journal

Lab-Journal is a structured research diary documenting ongoing work within the EUT-Lab ecosystem, including operator-theoretic, arithmetic, and computational investigations.

## Repository structure

```text
lab-journal/
├── journal/                  # Time-based research log entries
│   ├── daily/
│   ├── weekly/
│   └── monthly/
├── research/                 # Topic-based deep work
│   ├── operator-theory/
│   ├── arithmetic/
│   ├── computational/
│   └── shared/
├── data/                     # Datasets and generated outputs
│   ├── raw/
│   ├── processed/
│   └── external/
├── scripts/                  # Utility scripts for indexing/automation
├── templates/                # Reusable templates for entries and experiments
│   ├── entry/
│   └── experiment/
└── docs/                     # Methods, references, and project-level docs
    ├── methods/
    ├── bibliography/
    └── figures/
```

## Conventions

- Use ISO date formatting (`YYYY-MM-DD`) for daily logs.
- Keep one weekly summary per ISO week (`YYYY-Www.md`).
- Keep one monthly reflection per month (`YYYY-MM.md`).
- Add links between time-based logs (`journal/`) and topic notes (`research/`).
- Store immutable source datasets in `data/raw/`.

## Quick start

1. Copy a template from `templates/entry/` into `journal/daily/`.
2. Add topic notes under `research/<topic>/notes/`.
3. Track scripts and reproducible workflows under `scripts/`.
4. Store generated figures in `docs/figures/` and cite them from notes.
