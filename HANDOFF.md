# Green Mountain Renovations — handoff at ~60%

**Live:** https://10elizabethbell.github.io/greenMountainRenovations/ · **Repo:** https://github.com/10elizabethbell/greenMountainRenovations · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (Essex County Contractor Referrals group post)

## What's built
- One page, phone first: header (house mark from the logo + name, **Message me** top-right in place of a phone number), hero "Walls built to last." with the owner's promise and two buttons (Free estimate → form, See my work → gallery).
- **Signature element: the wall.** A drywall wall with paper-taped seams and screw heads. The gold taping knife from their logo skims joint compound along the seams by itself: a first pass down each seam, then a wider feathering pass beside it, lifting off the wall between passes. Each pass stamps the blade edge (feathered sides, lap ridges, drag streaks); wet grey mud dries to the page's flat white. After two full routes (~27 s) the coat fades and a fresh wall goes up. Touch or mouse takes the knife (drag works up, down and sideways on phones; the page doesn't scroll from the wall), and it goes back to auto after 2.2 s idle. After ~600px of dragging the hint says "Ready for paint." Tunables are at the top of the first `<script>` IIFE (`KNIFE`, `DRY`, `WET`, `FEATHER`, `AUTO_SPEED`, `RESET_LOOPS`, `IDLE_MS`, `LIFT_PX`, `REWARD_PX`).
- Moving skim-coat edges between every section (organic wavy fill, paused off screen).
- What I do (Hanging / Taping / Finishing / Renovations rows; each pre-ticks that service in the form), How it works (3 steps), My work (a full-width still of the taped wall, then their 2.2 s walkthrough clip and a corner still, held up with paper joint tape) with the big "Click to see more of my work." Facebook link, Where I work, Free estimate form, footer with the full circular logo, tagline, Facebook and Messenger.
- **Contact wiring:** the form composes a message (name, town, services, job, when), shows it, tries to copy it, and gives an **Open Messenger** button (`https://m.me/61594566614771`, checked: redirects to a Messenger thread). Messenger links can't pre-fill text, so the visitor pastes it; if copy is blocked (Facebook's in-app browser), the note says press-and-hold to copy.
- Favicon / home-screen icon: the house-and-knife mark cropped from their logo. og:image 1200×630 (logo + headline).

## Assumptions I made
- **One-person business, "I" voice:** from "message me for a free estimate!". Change to "we" if it's a crew.
- **Colors:** green #0F402D and gold #DEAC39 sampled from the logo; joint-compound white (#F1F0EC, also the canvas dry colour `DRY_RGB`) as the light ground.
- **"Renovations" as a service:** from the business name and Muse's category "drywall / home renovation"; the caption itself only says hung, taped, finished.
- **How it works copy** ("I look it over and give you a straight price before any work starts", "I feather every coat out until the seams disappear, then leave it ready for paint") is inferred from "free estimate" and normal drywall practice. Check with the owner.
- **Promise line** ("I don't call a wall done until you can't find a seam once the paint goes on.") is my wording in the owner's voice, not theirs.

## Placeholders and gaps
- **No phone number anywhere**, so the top-right corner holds "Message me" (Messenger). When a number exists: put it top-right as a `tel:` link, switch the form to an `sms:` handoff, and add it to the footer.
- **No email** → no footer email (rule: footer only, never invented).
- **Kingston's state is unknown**; the page says "Kingston and the surrounding area" only. Brief flags a mismatch (ad ran in an Essex County, NJ group).
- **Photos:** the downloadable Facebook video is only 3.2 s of one job, not twelve. I used 2.2 s of it (trimmed before a person walks through the doorway) and two stills. Frames are soft video stills; real photos would be a big upgrade.
- No reviews, prices, hours, licensing or insurance on the page (none stated).
- The tagline "Where quality matters" is hidden in the header below 430px wide (it crowded "Message me"); it's still the footer close.
- Logo is the 720px Facebook profile image; a vector would sharpen the footer seal and favicon.

## Questions for the owner
- Phone number, and do you take texts?
- Which Kingston (state), and which towns around it?
- Can you send photos of the twelve portfolio jobs (and any before/afters)?
- Your first name, to put on the page?
- Do you do repairs/patches, ceilings, texture, painting? (The logo has a paintbrush/knife; only hanging, taping and finishing are stated.)
- Solo or a crew? Licensed/insured (only if you want it said)?

## Ideas not built (yours to pick)
- **Runner-up world:** layered green mountain ridgelines (the name) with morning mist that parts under the finger; gold sun as the accent.
- Mud crumbs that fall off the knife on fast strokes; a sanding-dust puff when the coat dries.
- "Finished!" moment when the visitor covers both seams (the wall flashes painted, then resets).
- Before/after slider once real before/after pairs exist (taped vs. painted).
- Gallery of all twelve jobs when the photos arrive; a "Which one's your favourite?" pick (their own caption) as a playful vote.
- Self-hosted slab display face matching the logo's collegiate lettering (craft floor asks for it; house style says system stack, so I didn't).

## Review notes
- Impeccable: ran the finish reviewer and critique, audit, polish, harden, clarify, adapt, optimize, animate, typeset, layout, colorize, delight, distill, bolder, quieter and overdrive (live and onboard skipped). Applied fixes include a rebuilt mud renderer, focus rings that show on light sections, form borders at 3:1, errors tied to their fields, hover accents only on mouse devices, a stale-message guard on the form, landscape fixes and copy cuts.
- Not applied: changing "Click to see more of my work." to "See more of my work on Facebook". The wording comes from your finishing rules.
- Detector: ignores recorded in `.impeccable/config.json` (system font, compound-white ground, overflow clip, wall canvas padding, logo-lockup caps). `flat-type-hierarchy` left standing: it only counts the 14–24px UI sizes, and the display headings carry the hierarchy.
- No concept roll was run (unattended build); the world was chosen from the trade.

## Not verified
- Real-device touch on iOS/Android (Chromium touch emulation passed; WebKit audit passed for layout only).
- Messenger handoff inside Facebook's in-app browser on a real phone (link redirect checked with curl only), and whether clipboard copy works there.
- Frame rate on older phones (canvas capped at 1.5x on phones).
