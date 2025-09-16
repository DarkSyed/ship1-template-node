# Ship 1 — Node/JS

**Baseline (Required)**  
Add a **Delete** button that removes an entry by its timestamp `t` (ISO string). Keep newest-first ordering and persist to `localStorage` (key: `edge_ship_log`).

**Hard (choose 1–2)**  
- Undo delete (single-level undo is fine)  
- Bulk delete (checkbox multi-select → delete)

## Why this exists (unchanged spirit from Ship 0)
- Same ES modules + DOM vs pure-logic separation
- Same persistence (localStorage on the same origin)
- Same Git flow + screenshot evidence

## Quick Start
```bash
nvm use
npx http-server src/ship1 -p 8080
# open http://localhost:8080
