# Ship 1 - Node/JS Track

**Welcome to Edge Labs!** This is your Ship 1 project — adding **delete** functionality to a browser-based JavaScript app.

---

## Quick Overview

You're building on Ship 0 by adding a **Delete** feature that removes an entry by its **timestamp** (ISO string). Look for `// TODO:` comments in the code — they tell you exactly what to implement!

**What you'll learn:**
- DOM rendering and event handling in JavaScript
- Working with ISO timestamps and simple state
- More Git/GitHub practice

---

## Get Started (Choose Your Path)

### New to This? Start Here!
1. **[SETUP.md](SETUP.md)** — Step-by-step setup guide  
2. **[DEVELOPMENT.md](DEVELOPMENT.md)** — What to build and how to code it  
3. **[TROUBLESHOOTING.md](TROUBLESHOOTING.md)** — When things go wrong

### Already Set Up? Jump to Coding!
- **[DEVELOPMENT.md](DEVELOPMENT.md)** — Start building your features

---

## Project Files

ship1-template-node/

SETUP.md # Setup instructions

DEVELOPMENT.md # Coding guide

TROUBLESHOOTING.md # Problem solutions

GLOSSARY.md # Term definitions

src/ship1/ # Your code goes here (index.html, app.js, logic.js, storage.js)

tests/ # Tests to run (Hard Mode)

data/ # Optional seed data

yaml
Copy code

---

## What to Build

### Baseline (Required)
- Add a **Delete** button that removes an entry by its exact timestamp `t` (ISO string)
- Keep entries displayed **newest-first**
- Persist changes (same storage key as Ship 0)
- Files: `src/ship1/index.html`, `src/ship1/app.js`, `src/ship1/logic.js`, `src/ship1/storage.js`
- Look for `// TODO:` comments!

### Hard Mode (Optional — choose 1–2)
- **Undo delete** (single-level undo is fine)
- **Bulk delete** (multi-select entries and remove all at once)

---

## Quick Test

After setup, serve the project and verify you can delete by timestamp:

```bash
npx http-server src/ship1 -p 8080
# then open http://localhost:8080
(For Hard Mode tests, see DEVELOPMENT.md and run npm test.)

Submit Your Work
Repository URL: https://github.com/YOUR-USERNAME/edge-f25-ship1-YOUR-NAME

Branch name: firstname-lastname

What you completed: Baseline or Hard Mode

Submit: Google Form

Need Help?
GLOSSARY.md — Explains confusing technical terms

TROUBLESHOOTING.md — Solutions to common problems

Slack — Ask your labmates and Exec Team

Office Hours — Get personalized help

Remember: Every expert was once a beginner!

You've Got This!
Break it down into small steps, use the detailed guides, and ask for help when you need it. Welcome to coding!
