# Repository Guidance

This repository is **mostly documentation** — Markdown notes for a native pollinator
garden and its IPMC §302.4 compliance record — now paired with a small **static GitHub
Pages front end**: three self-contained pages (`index.html` sortable table,
`calendar.html` bloom calendar, `map.html` planting-map schematic) that render from
`data/species.csv` and `data/layout.csv`. Almost everything here is prose; the only
code is those static pages.

## Git workflow (standing instructions)

The repository owner has set these as durable, standing permissions for **every**
session. Do not ask again, and do not deviate without a new explicit instruction:

- **Commit and push changes directly to `main`.** This file is the explicit, standing
  authorization to push to `main` — you do not need to ask first.
- **Do NOT create per-session branches, and do NOT push any `claude/*` branch.** If a
  session starts checked out on an auto-generated working branch, commit your work there
  and push it to `main` with `git push origin HEAD:main`. Never push the throwaway
  branch to the remote — those leftover branches are unwanted clutter.
- **Do NOT open pull requests** unless explicitly asked. Direct commits to `main` are
  the expected workflow for this docs repo.

## Workflow modes: hardware vs. software

This project iterates in two explicit, named modes. Assume **hardware mode** unless the
owner has said we are in software mode.

- **Hardware mode — design only.** Work out structure, schema, content, naming, and
  approach by discussing it. Do **not** create, edit, move, or commit any repository
  file while in hardware mode. The only exception is a specific, explicit "do X now"
  instruction from the owner. Stay here, iterating, until the design is settled.
- **Software mode — implementation.** Once the owner calls software mode, build the
  agreed design in the repo: write and move files, generate outputs, and commit.

Always iterate in hardware mode first, and switch to software mode only when the owner
says so. If it is unclear which mode we are in, ask before writing anything.
