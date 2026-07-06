# West Slope Map — Analysis Notes

Companion to `gardenmap.md`. Records the design review behind the current
layout so the reasoning isn't lost between revisions. The layout renders live as the
[west-slope map](https://dev-grimnir.github.io/meadow-public/map.html); the one-page
habitat & compliance case is the
[habitat record](https://dev-grimnir.github.io/meadow-public/habitat.html).

Slope orientation reminder:
- **Bands run as contour columns:** Band 1 = LOW/road edge, Band 2 = middle,
  Band 3 = HIGH point.
- **Height tiering:** Band 1 shortest (front), Band 3 tallest (back), for the
  layered look from the road.
- **Moisture:** Not a real gradient. The whole face is a 45° slope that sheds
  water, and the level ground at the toe never pools — so Band 1 drains as
  sharply as the rest. Assign bands by height and juglone tolerance only.
- **Juglone:** South end only (black walnut at southwest corner).
  North/north edge end (above the stairs) is juglone-free.
- **Butterfly territory = the north half** (above the stairs): both monarch
  larval hosts plus the black swallowtail host live here.

---

## Height Re-Tier (2026-06)

Every species sits in the band its mature height belongs to. Sorting all eleven
by height partitions **exactly** into the three band capacities (66 / 68 / 53
cells), so nothing changed in the seed counts — only which band each occupies:

| Band | Height | North half (above stairs) | South half (below stairs) |
|------|--------|---------------------------|---------------------------|
| 1 (front) | 1–2.5 ft | Golden Alexander, Butterfly Weed | White Yarrow, Wild Columbine |
| 2 (middle) | 2–4 ft | Smooth Blue Aster, Mountain Mint | Scarlet Bee Balm, Blazing Star, Purple Bee Balm |
| 3 (back) | 3–6 ft | Common Milkweed | New England Aster |

Front-to-back now runs short→tall on both halves. (Butterfly weed and milkweed
held their bands; yarrow and columbine came out of the middle band where they
were buried; smooth blue aster and the orphan mint went back to the middle.)

---

## Golden Alexander → Butterfly Territory (2026-06)

Height-only logic had put GA in the front-south band. But GA is the **black
swallowtail larval host**, so it belongs where the butterflies are. Swapped GA
(6) to Band 1 **north** with the monarch hosts; columbine (6) took GA's old
front-south cells. The swap is count-neutral and juglone-neutral (both species
tolerate juglone), and it lands columbine at the **walnut corner**, where the
tree's part shade actually suits it better than open sun.

---

## Juglone Handling

Butterfly Weed (poor tolerance) and Common Milkweed (marginal) are the only two
juglone-shy species, and both sit **entirely north of the stairs**, clear of the
walnut. Everything below the stairs — yarrow, columbine, bee balm, blazing star,
bergamot, New England aster — is juglone-tolerant.

---

## Butterfly Optimization

- **North half = the butterfly/monarch zone.** Both monarch hosts (Butterfly
  Weed front, Common Milkweed back) plus the black swallowtail host (Golden
  Alexander) are clustered here, with a nectar succession layered in: columbine
  isn't here anymore, but GA (Apr–Jun) → butterfly weed/milkweed (Jun–Jul) →
  mountain mint (Jun–Sep) → smooth blue aster (Aug–Oct) keeps it fed.
- **South half = nectar engine.** Yarrow + bee balm + blazing star + bergamot
  (summer) → New England aster (Aug–Oct), with columbine at the walnut corner
  for early spring.
- **Fall fuel = two strong blocks.** New England Aster (27, Band 3 south) +
  Smooth Blue Aster (21, Band 2 north) = 48 positions (~26% of the slope) for
  the late Sept–Oct monarch migration.
- **NO cutback or string-trim — anywhere, any season.** Stems stand year-round.
  Swallowtails overwinter as chrysalises on the standing stems and eclose in spring
  (~Apr–Jun); a late-March knock-down would shred the next generation. Let new
  growth rise through the old stems. (See `plantingplan.md`.)
- **Mountain mint** — best nectar magnet here — is a 17-cell block in the center
  of Band 2 north. Expanding it is the one remaining butterfly upgrade, but it
  takes positions from other species (a count change), so it's left open.

---

## Watch Items

- **Band 3 is a dedicated spreader band.** Milkweed (rhizomatous) north, New
  England Aster (self-seeder) south. Manage the path (`xx`) edges so they
  don't march downslope into Band 2 by years 2–3.
- **Columbine in/near the walnut.** Juglone-tolerant and gets the part shade it
  likes at the corner, but may still go summer-dormant — a brief gap the
  adjacent yarrow fills.
- **Mountain mint also spreads** — kept centered in Band 2 north; let it fill
  its block but watch the downhill edge.

---

## Planting Combinations (Tried & Working)

**South-Frontage Success Combo:** Coneflower + Bee balm (direct-sown, full clearing)
- Establishes well; validates the direct-sow + full-clearing approach.
- Coneflower provides structure; bee balm fills in horizontally.
- Both drought-tough for full sun.

**West Slope Combo (South):** Scarlet Bee Balm + Purple Bee Balm / Wild Bergamot (juglone-tolerant)
- Both fibrous-rooted = container-to-ground transplant OK.
- June establishment excellent; ready for year-two vigor.
- Juglone-safe; the walnut cannot suppress them.
