# App Starter (A/B/C follow-through)

If you want to go beyond a profile README, this is a simple, scalable starter layout.

## Recommended structure

```text
.
├── README.md
├── src/
│   └── ... application code
├── tests/
│   └── ... automated tests
├── docs/
│   └── ... architecture and onboarding notes
├── .github/
│   └── workflows/
│       └── ci.yml
└── <tool manifest>
    ├── package.json (Node/TS)
    ├── pyproject.toml (Python)
    ├── Cargo.toml (Rust)
    └── go.mod (Go)
```

## Non-negotiables for maintainability
1. A one-command local start in `README.md`.
2. A one-command test run in `README.md`.
3. CI that runs lint + tests on every PR.
4. Clear contribution guide (`CONTRIBUTING.md`) once collaborators join.

## Suggested first milestones
1. Pick one language/runtime and add the proper manifest.
2. Add a tiny `src` feature with one matching test.
3. Add CI for that single test.
4. Expand only after basic quality checks are green.
