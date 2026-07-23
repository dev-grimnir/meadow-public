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

- **North half / NW (butterfly zone):** **tarped down (2026-07-18).** Re-laid with the
  corrected method — scalp → flat → staggered field staples, grass band scalped down the
  middle. Both strips sit in contact, no doming. Watch the uphill corners after the first
  windy day, and a couple of slight tents near the strip tops (bit of thatch left under)
  — flatten with extra staples if easy. (First attempt ballooned over uncut grass with
  edge-only staples — that's the lesson logged in Method below.)
- **South half / SW (nectar / walnut zone):** **scalped hard and tarped down (2026-07-19);
  fully measured (2026-07-23).** Whole west slope now occulted — both halves down. The
  hard scalp gave irregular geometry (expected, and flagged in advance) and **room for four
  beds, not the planned three**: the bottom (road) and top (toe) bands went down as clean
  ~40' runs; the two inner beds were tarped in pieces around the spared bee-balm clumps.
  Established bee balm / bergamot at the walnut corner and mid-slope spared and cut around,
  per the standing decision. Final measurements + as-built map below.
- Design and measurements are **locked** (see `gardenmap.md`). **Not yet sown** — sowing
  is late Oct–Nov, after the tarp comes off the beds.

### Final south-half measurements (2026-07-23) — as-built tarp

Four beds, road (bottom of hill) → toe (top of hill). Outer two continuous; inner two
pieced around the spared bee-balm clumps. Photo on file is shot from the road looking
uphill = this map rotated 90° (per the standing map-orientation note below).

```text
   |G| WY |G| SB |G| BE |G| NA |G|   ← north end
   |G| WY |G| BS |G| BE |G| NA |G|
   |G| WY |G| BS |G| BE |G| NA |G|
   |G| WY |G| bb |G| BE |G| NA |G|
   |G| WY |G| SB |G| BE |G| NA |G|
   |G| WC |G| bb |G| bb |G| NA |G|   ← clump spans both inner beds
   |G| WC |G| SB |G| BE |G| NA |G|
   |G| WC |G| bb |G| BE |G| NA |G|
   |G| WC |G| SB |G| BE |G| NA |G|
   |G| WC |G| SB |G| BE |G| NA |G|   ← south end · WC at the walnut corner
      road                       toe
   (bottom of hill)        (top of hill)

   Bed 1  Bottom band   WY→WC   CONTINUOUS  ~40'2" (N 2'5", S 2') · ~89 ft²
   Bed 2  Lower band 1  SB/BS   BROKEN ×4   16'4" · 2'2"□ · 2'10"□ · 11'7"   (lower inner)
   Bed 3  Lower band 0  BE      BROKEN ×2   24' · 6'3"                       (upper inner)
   Bed 4  Top band      NA      CONTINUOUS  ~40'10" · ~117 ft²
   bb  established bee-balm / bergamot clump SPARED — cut around, left living
```

Totals: ~144 linear ft of ~2.5'-wide strip, ~353 ft² tarped (sits under the ~410 ft²
half, the balance being the grass bands + the spared-clump gaps). N–S orientation of the
clumps within the run is best-guess (assumed north = up); confirm on tarp-off day.

## Method — occultation → contour-band beds

- **Scalp the grass short first** and rake off the heavy clippings — the kill is *light
  exclusion* (the sod starves in the dark), not the plastic touching the soil, so a dark,
  staked-down dome still kills what's under it. Scalp anyway: tall grass tents the sheet and
  lifts the *edges*, where light leaks in around the margins and a grassy fringe survives —
  and the dome catches wind on the grade and ponds water. Snug contact only *speeds* the
  kill by trapping heat — both the sun's and the low-grade heat thrown off by the dead grass
  rotting underneath — a bonus, not the mechanism. (Learned the hard way on the NW half.)
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
- Beds **don't taper** (field-confirmed) — uniform strips. Planned ~3 per half; the south
  half's hard scalp actually left room for **4** (see the as-built measurements above).

## Layout (per `gardenmap.md`)

- **NW / north half** — butterfly, juglone-free. Front (short): Butterfly Weed,
  Golden Alexanders. Back (tall): Smooth Blue Aster, Mountain Mint (centered),
  Common Milkweed. ~326 ft².
- **SW / south half** — nectar, walnut / juglone. **4 beds as-built** (see measurements
  above). Front: White Yarrow, Wild Columbine (at the walnut corner). Mid-low: Scarlet Bee
  Balm, Blazing Star. Mid-high: **Black-Eyed Susan** (replaced purple bee balm — see decision
  below). Back (tall): New England Aster. Established bergamot persists only as the spared
  clumps, not re-sown. ~410 ft².
- Beds ~487 ft² total; grass bands ~249 ft².

## Decision (settled 2026-07-18) — SPARE the established bee balm

Established **bee balm + bergamot are already spread across the slope**, including where
the New England Aster bed goes. **Call made: spare the established plants — especially
the Scarlet Bee Balm (SBB)** — do not tarp over them. They're established, and they were
planted with the kids; they stay. On plastic day, **cut the tarp around each clump** and
keep it as an anchor. The New England Aster bed becomes a **bee-balm / aster mix** — good
habitat, stacks summer + fall bloom (and the standing-rule spring aster-pull below now
applies to keeping that mix in balance).

Options not taken, kept for the record:
- **Move** — bee balm transplants well (fibrous roots); dig/divide and consolidate the
  clumps out of the seedbed, then tarp clean. (Not doing this — leaving them in place.)
- **Sacrifice** — tarp over and resow; only for thin or mildewed clumps. Reserve for any
  thin/mildewed clump not worth sparing.

## Decision (settled 2026-07-23) — Black-Eyed Susan for purple bee balm (sown mid-high bed)

**Dropped purple bee balm (wild bergamot) from the sown plan; sowing Black-Eyed Susan
in the mid-high south bed instead.** Reasoning: scarlet bee balm and bergamot are the same
genus (*Monarda*), same height, overlapping bloom, both mildew-prone, and they **hybridize
freely** — sown side by side they'd blur to a muddy pink-red over a few years. The bergamot
isn't lost: it **already persists in the spared clumps** (the `bb` islands), so we stop
*sowing* it, not remove it. Black-Eyed Susan earns the slot: yellow (a color the bed lacks),
mid-to-late-summer bloom that **bridges Scarlet Bee Balm (summer) → New England Aster (fall)**,
**juglone-tolerant** (matters on the walnut side), goldfinch seed heads (ties to the standing
leave-the-stems rule), and a **Silvery Checkerspot** larval host.

- **Open — sow-day seed choice:** *R. hirta* (short-lived, reseeds/drifts — meadow, more
  finch seed, needs the same spring volunteer-pull as the aster) vs. *R. fulgida* (clumping,
  longer-lived, tidier, less management). Decide when ordering seed (mid-August).
- Code **BE** now slots into the mid-high bed in `gardenmap.md` in place of PB.

## Standing rules / long-term

- **No cutback or string-trim on native stems, any season** — swallowtail chrysalises
  overwinter on them. The grass bands can be trimmed; the block stems cannot.
- New England Aster self-seeds and drifts into the bee balm over years — **pull the
  aster volunteers out of the bee balm bed each spring.** Goldfinches (and others) eat
  the standing seed heads: a partial check on its spread, plus winter bird food.
- The grass bands are a **temporary erosion scaffold** — pulled once the meadow's own
  roots take over erosion duty (2–3 years), then those strips get planted out.

## ASCII map convention (standing — don't improvise a new one)

Draw **every** ASCII map of the slope in the `gardenmap.md` template, keeping its
orientation. Do not invent a different axis (e.g. road-on-the-right, compass-rotated):

- **Orientation:** `<- road/LOW (short) ----------- toe/HIGH (tall) ->` — **road on the
  LEFT, toe on the RIGHT**, fall line horizontal, water flows road → toe (left → right).
  `LOW`/`HIGH` = plant height (short/tall), not ground elevation. **North is up:** north
  half drawn above south half; within a half, rows run top → bottom = north end → south end.
- **Grass contour bands** = the vertical `|G|` columns between bed columns (they run the
  full slope length, across the fall line). Beds are two-letter codes; always include the
  code legend (G, BW, GA, SA, MT, MW, WY, WC, SB, BS, BE, NA; `bb` = spared bee-balm/bergamot
  clump). (PB / purple bee balm retired from the sown map 2026-07-23 — kept only as `bb`.)
- The interactive `map.html` should render this **same** orientation. It is currently
  drawn 90° rotated from the template (fall line vertical, road at top) — that is the
  known map bug to fix.
