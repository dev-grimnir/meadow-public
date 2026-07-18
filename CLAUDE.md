# Repository Guidance

This repository is **mostly documentation** — Markdown notes for a native pollinator
garden and its IPMC §302.4 compliance record — now paired with a small **static GitHub
Pages front end**: five self-contained pages (`index.html` home page, `table.html`
sortable/filterable species table, `calendar.html` bloom calendar, `map.html`
planting-map schematic, `habitat.html` habitat/compliance record) rendering from
`data/species.csv` and `data/layout.csv`.
Almost everything here is prose; the only code is those static pages.

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

# West-Slope Build — Working Memory

Running state and standing decisions for the west-slope conversion, so nothing
gets lost between sessions. Companion to `gardenmap.md`, `gardendesign.md`, and
`plantingplan.md`. Locations are compass/slope only.

## Current state (2026-07)

- **North half / NW (butterfly zone):** re-laid with the corrected method — scalp →
  flat → staggered field staples, grass band scalped down the middle. Sits in contact,
  no doming. **Most of the north half tarped; ~28% of the whole west slope done.**
  (First attempt ballooned over uncut grass with edge-only staples — that's the lesson
  logged in Method below.)
- **South half / SW (nectar / walnut zone):** not started. Plastic + staples on hand.
- Design and measurements are locked (see `gardenmap.md`). **Not yet sown** — sowing
  is late Oct–Nov, after the tarp comes off the beds.

## Method — occultation → contour-band beds

- **Scalp the grass short first** and rake off the heavy clippings — tall grass tents the
  plastic off the soil into a domed air pocket that catches wind, ponds water, and won't
  make the contact that kills the sod. (Learned the hard way on the NW half.)
- Tarp the whole bed with opaque plastic (3' roll here) to kill the sod and the surface
  weed seedbank. **Buy the plastic ~1 ft wider than the killed strip** — the extra is your
  staple margin and the material to fold or patch the corners; a roll the same width as
  the bed leaves nothing to work with. (With the 3' roll: keep the killed strip ~2.5' and
  ~3" of margin each side.)
- **Staple, never weight** — 45° grade, weights roll. **Staple the field on a staggered
  ~2–3 ft grid, not just the edges** — edge-only lets the middle balloon. **Double the
  corners** — fold the corner over, or patch it with an offcut, and staple through the
  doubled ply; corners lift first, the uphill ones worst.
- Leave the tarp on the beds until sow day.
- **Sow day:** pull the tarp, rake off the loose dead thatch (leave the killed root
  mat — it holds soil), press seed in, don't bury (light germinators). No jute needed
  — the beds are short runs between bands.
- Beds **don't taper** (field-confirmed) — uniform strips, ~3 per half.

## Layout (per `gardenmap.md`)

- **NW / north half** — butterfly, juglone-free. Front (short): Butterfly Weed,
  Golden Alexanders. Back (tall): Smooth Blue Aster, Mountain Mint (centered),
  Common Milkweed. ~326 ft².
- **SW / south half** — nectar, walnut / juglone. Front: White Yarrow, Wild Columbine
  (at the walnut corner). Mid: Scarlet Bee Balm, Blazing Star, Purple Bee Balm.
  Back (tall): New England Aster. ~410 ft².
- Beds ~487 ft² total; grass bands ~249 ft².

## Open decision — PLASTIC DAY, not sow day

Established **bee balm + bergamot are already spread across the slope**, including
where the New England Aster bed goes. The tarp kills them, so the call is made **when
the plastic goes down**, per clump:

- **Spare** — cut the tarp around the clump, keep it as an established anchor (that
  bed becomes a bee-balm / aster mix — good habitat, stacks summer + fall bloom).
- **Move** — bee balm transplants well (fibrous roots); dig/divide and consolidate the
  clumps out of the seedbed, then tarp clean.
- **Sacrifice** — tarp over and resow; only for thin or mildewed clumps.

## Standing rules / long-term

- **No cutback or string-trim on native stems, any season** — swallowtail chrysalises
  overwinter on them. The grass bands can be trimmed; the block stems cannot.
- New England Aster self-seeds and drifts into the bee balm over years — **pull the
  aster volunteers out of the bee balm bed each spring.** Goldfinches (and others) eat
  the standing seed heads: a partial check on its spread, plus winter bird food.
- The grass bands are a **temporary erosion scaffold** — pulled once the meadow's own
  roots take over erosion duty (2–3 years), then those strips get planted out.
