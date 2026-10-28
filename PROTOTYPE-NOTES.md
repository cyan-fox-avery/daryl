# Visual prototype v0.1 — Daryl by the Numbers

Status: visual prototype for Avery + Mira review only. Not merged, not the final site, not for Daryl yet.

## What is in it
- One long, mobile-first vertical scroll, California / bohemian vintage scrapbook styling: layered paper cards, tape, Polaroid-style placeholders, terracotta / sage / turquoise / coral / honey.
- Proposed section order from the 2026-10-28 plan: opening → Daryl herself → time-travel sample cards → "You're in Good Company…" birthday-club structure → future / horizon sample → closing + dime secret.
- Sample historical cards only, from Mira's approved selections: Montréal Métro 1966, Expo 67, Montréal Olympics 1976, Wikipedia January 15, 2001, Montréal 375th 2017, Québec total solar eclipse April 8, 2024.
- Birthday-club structure sample: Molière 1622, Martin Luther King Jr. 1929, Pitbull 1981, and Daryl as final star member, born January 15, 1960. Dates are draft — to verify before publication, per Mira's brief.
- Future sample: Los Angeles Olympics 2028 (verify date/status), Peanuts centennial 2050, and one "Next Great Leaps" YES concept labelled explicitly as aspirational, not a prediction: first human footprints on Mars.
- Dime interaction: upright 3D spin around the vertical axis via CSS 3D transforms, fast start, smooth slow-down, slight wobble, settles, re-spinnable. Reduced-motion fallback: gentle flip instead of spin. Coin faces are prototype drawings, not coin photos; monarch obverse is marked "to be determined" — no monarch is asserted.
- Callie: a labelled peek note, not a real photo cutout, placed so it never blocks text.

## What is deliberately NOT in it
- No real Daryl photos, no Callie photos, no ink portrait. Placeholders only, until Avery approves specific files for the public repo.
- No MAYBE, NO, or UNRATED "Next Great Leaps" content presented as settled. No full historical catalogue, no full birthday-club list, no full future calendar — samples only.
- No invented personal facts, no invented dime/mother backstory, no explanation of the dime in the site copy (the prototype label "The very bottom" is a review label only).
- No 2027 event presented as confirmed. No Pages publishing decision is made by this prototype alone — see below for the preview branch.

## Technical notes
- Single self-contained index.html, inline CSS/JS, no external dependencies, no external fonts or images. System fonts only, with a handwritten-style fallback stack.
- Touch targets: spin button is 48px+ high. Headings are semantic. Reduced-motion media query disables card/photo rotation and the JS spin animation.
- To test locally: serve this folder and open index.html on a phone-sized viewport. JS syntax was checked before push (see commit history / local check in the working session).

## Next steps after review
1. Avery + Mira approve / correct the section order, look, and sample tone.
2. Review MAYBEs and refine copy.
3. Verify birthday-club dates, historical details, and future event dates/status.
4. Decide which photos / Callie cutouts to use and approve files for publication.
5. Build the full site from the structured content source, keeping YES/MAYBE/NO/UNRATED labels intact.
