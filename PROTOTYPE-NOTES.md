# Opening prototype v0.2 — Daryl by the Numbers

Status: opening section only, for Avery + Mira review. Not merged, not the final site, not for Daryl yet.

## What is in it (v0.2, 2026-11-09)
- Opening scrapbook cover only, per Mira + Avery's 2026-11-09 opening brief — deliberately less crowded than the mockup (about 30–40% less busy): lots of cream negative space around one dominant title card.
- Title as real, selectable text, not baked into an image: **"Daryl, by the Numbers"** in Shrikhand (chunky, rounded, flower-power; system fallback if the font does not load). "Daryl" warm burnt orange, "by the" dusty teal, "Numbers" deep plum/burgundy. Supporting text, exact: "Est. January 15, 1960" and "A life in numbers, stories, and little wonders."
- Callie: the real photograph, as a separate layer peeking from the right edge of the title card — never over the title text. No speech bubble. The photo is the extreme close-up Avery sent 2026-11-09: one expressive brown eye, enormous nose in the foreground. Source file: `0008E6A2-7A2B-4414-9B48-B3DBAF1608C1-photo-155C163A-9F5C-43D5-966F-7A1833C11F7B.jpg` (sha256 `285805d602a0486d4a55577865c6515612d6483aed748eaccc091aa77dea3f2a`, 1125×975). Published copy is an optimized resize only: `assets/callie-opening.jpg`, 800×693, 84 KB, no AI recreation, no crop from the mockup. Alt text describes Callie peeking, her eye and nose. Her white cutout background blends into the paper with `mix-blend-mode: multiply`.
- Decorations, few and deliberate only: vinyl record tucked top-left, small California sunset illustration top-right, Montréal postcard (Saint Joseph's Oratory dome, "Montréal", fleur-de-lis stamp) bottom-left, wave strip at the base, one small surfboard tip, three flower blossoms total. All decorative SVGs are `aria-hidden`. No spiral-bound edge, no VW van, no guitar pick — those mockup motifs are held for later sections.
- Transition strip beneath the cover, exact line: "And just how much life fits into one lifetime?" — leading into a stub heading only: "A Life by the Numbers".
- Mobile-first, one continuous vertical scroll, no tap-to-enter, no page-turning, no loading sequence, no fixed obstructing decorations. Subtle entrance positioning only; reduced-motion disables the card/strip/Callie rotations. Text never overlaps Callie's image or decorations: the title card reserves space for her (padding-top on narrow phones, padding-right on wider screens).
- Prototype banner at the top makes clear this is a review prototype, not the final site.

## What is deliberately NOT in it (v0.2)
- No lifetime statistics, birthday almanac, or historical timeline redesign — the "A Life by the Numbers" heading is a stub only.
- No other Daryl photos, no ink portrait, no dime, no birthday club. The other eight Callie photos Avery sent 2026-11-09 (rainbow bandana full-body, blue/purple bandana front, pink/purple bandana profile, pink collar front, close-up with teeth showing, sideways head, heart-shaped leg pose, full side profile) are saved in Avery's files for later Callie cutouts — none of them are committed in this pass.
- No invented personal facts. No mockup used as a background or asset — it is a design reference only.

## Technical notes
- `index.html` (single file, inline CSS, no JS) + `assets/callie-opening.jpg`. External dependency: Google Fonts (Shrikhand + Caveat) with system-font fallbacks.
- Local test 2026-11-09: served the folder locally, `index.html` 200, `assets/callie-opening.jpg` 200, title / est / transition text present.
- Push note: the photo is a binary file, so the GitHub snapshot-push route (UTF-8 only) cannot carry it — this push uses the gh-api contents route, as v0.1 did.

## v0.1 history (superseded by v0.2)
- v0.1 (2026-10-28, head `dcc8b818`) was a full-page sample scroll: opening, Daryl herself, time-travel sample cards, birthday-club structure, future sample, and the dime spin prototype. It is replaced on this branch by the opening-only v0.2. Its section order and sample content live in `~/workspace/daryl/plan-2026-10-28.md`.

## Next steps after review
1. Avery + Mira approve / correct the opening: title type, Callie position/size, decoration balance, negative space.
2. Only then use the opening as the visual foundation for the rest of the site.
3. Birthday-club dates, historical details, and future event dates/status still need verification before publication.
