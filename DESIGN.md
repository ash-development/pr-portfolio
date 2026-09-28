---
name: Ash Schnoor
description: A dark sticker scrapbook for a music-social portfolio, hot pink on near-black.
colors:
  night: "#0F0B10"
  night-lifted: "#1A1318"
  cream: "#F6EEE9"
  soft-mauve: "#B9ADB3"
  hot-pink: "#E954AF"
  on-pink: "#0F0B10"
typography:
  display:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "clamp(5rem, 21vw, 17.5rem)"
    fontWeight: 800
    lineHeight: 0.8
    letterSpacing: "-0.045em"
    fontVariation: "\"opsz\" 96"
  headline:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 7vw, 5.5rem)"
    fontWeight: 800
    lineHeight: 0.9
    letterSpacing: "-0.035em"
    fontVariation: "\"opsz\" 96"
  title:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "clamp(1.6rem, 4.4vw, 3.4rem)"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.03em"
  lede:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 2.2vw, 1.75rem)"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.015em"
  body:
    fontFamily: "Nunito, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  body-large:
    fontFamily: "Nunito, system-ui, sans-serif"
    fontSize: "clamp(1.125rem, 1.6vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "0.14em"
  marquee:
    fontFamily: "Bricolage Grotesque, system-ui, sans-serif"
    fontSize: "clamp(1.3rem, 2.6vw, 2.1rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.08em"
  script:
    fontFamily: "Ballet, cursive"
    fontWeight: 400
    lineHeight: 1
rounded:
  badge: "0.3rem"
  tile: "0.35rem"
  focus: "4px"
  phone-screen: "2.15rem"
  phone: "2.8rem"
  pill: "999px"
spacing:
  grid-gap: "0.5rem"
  gutter: "clamp(1rem, 4vw, 3.5rem)"
  container: "78rem"
  scallop-radius: "14px"
  scallop-radius-narrow: "11px"
components:
  email-chip:
    textColor: "{colors.cream}"
    rounded: "{rounded.pill}"
    padding: "0.2rem 0.9rem 0.2rem 0.2rem"
  email-chip-hover:
    backgroundColor: "{colors.night-lifted}"
  email-chip-icon:
    backgroundColor: "{colors.hot-pink}"
    textColor: "{colors.on-pink}"
    rounded: "{rounded.pill}"
    size: "2.5rem"
  social-pill:
    backgroundColor: "{colors.on-pink}"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0.55rem 1.1rem"
  social-pill-hover:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.on-pink}"
  scallop-panel:
    backgroundColor: "{colors.hot-pink}"
    textColor: "{colors.on-pink}"
    padding: "calc(28px + clamp(1.25rem, 3vw, 2.25rem))"
  marquee-band:
    backgroundColor: "{colors.hot-pink}"
    textColor: "{colors.on-pink}"
    typography: "{typography.marquee}"
    padding: "clamp(0.8rem, 1.6vw, 1.15rem) 0"
  reel-tile:
    backgroundColor: "{colors.night-lifted}"
    rounded: "{rounded.tile}"
  view-badge:
    backgroundColor: "{colors.night}"
    textColor: "{colors.cream}"
    typography: "{typography.label}"
    rounded: "{rounded.badge}"
    padding: "0.3rem 0.55rem"
  phone-mockup:
    backgroundColor: "#000000"
    rounded: "{rounded.phone}"
    padding: "0.7rem"
    width: "min(100%, 20rem)"
---

# Design System: Ash Schnoor

## Overview

**Creative North Star: "The Sticker Scrapbook After Dark"**

A plain, quiet structure (one centered container, generous vertical breathing room, no nav) carries a handful of hand-made shapes that feel cut out and stuck on: a four-point sparkle, a twelve-point starburst, scalloped pink panels, a scalloped scroll badge, a cream scribble underline, a felt star with a stitched edge, and a cream cat sticker lounging on the name. The ground is near-black; hot pink is the lead voice and carries headlines, rules, shapes and whole bands. Cream is the reading color and the secondary display color.

Type does the loud work. Bricolage Grotesque at 800 with tight negative tracking makes oversized stacked headlines; Ballet script appears only as short, tilted, hand-signed accents; Nunito keeps body copy round and friendly. Composition breaks the SaaS skeleton through offsets rather than cards: staggered skill lines, alternating left/right case heads, script tilted off the baseline.

The palette was changed by the owner from the original spec's cream ground and indigo headlines to this dark ground with #E954AF leading (2026-09-27). The spec's shapes, type, section structure and motion rules still hold; its palette does not.

**Key Characteristics:**
- Near-black ground, hot pink lead, cream reading text; three colors do almost everything.
- Oversized Bricolage 800 display, tight tracking, line-height under 1.
- Drawn SVG shapes as the ornament system; no stock icons, no photos standing in for missing work.
- Flat surfaces; depth only on physical objects (phone mockup, felt star).
- One ambient motion (marquee drift); everything else plays once or on hover, and all of it stands still under reduced motion.

## Colors

A three-voice dark palette: a warm plum-black ground, a single hot pink that leads, and a warm cream that reads.

### Primary
- **Hot Pink** (hot-pink): the lead color. Hero name and section headlines, the title rule and its sparkle, scalloped panels, marquee bands, the closing footer, stat numbers, caps role labels, the email-chip icon disc, scrollbar thumb and text selection.

### Neutral
- **Night** (night): page ground and theme color; also the view-count badge fill over reel thumbnails.
- **Night Lifted** (night-lifted): the one lifted band ("where i've worked"), reel-tile fallback fill, email-chip hover.
- **Cream** (cream): body text, case-study names, skill lines, the scribble stroke, focus rings, the cat sticker, and the sparkle inside the closing script.
- **Soft Mauve** (soft-mauve): quiet secondary text only: the scroll-cue line, organization sub-names ("The Fillmore").
- **On Pink** (on-pink): the same near-black as Night, used for every text or glyph that sits on a pink surface.

### Named Rules
**The Pink Leads Rule.** Hot pink is the voice, not an accent: headlines, rules, shapes and full-bleed bands. Body paragraphs are never pink; they are cream on dark or near-black on pink.

**The Dark-On-Pink Rule.** Anything readable on a pink surface uses On Pink. Cream is allowed on pink only as a decorative shape (the closing sparkle), never as text.

## Typography

**Display Font:** Bricolage Grotesque (with system-ui, sans-serif)
**Body Font:** Nunito (with system-ui, sans-serif)
**Script Accent:** Ballet (with cursive)

**Character:** A chunky, slightly quirky grotesque shouting in pink, a round humanist sans chatting underneath, and a thin script signing its name in the margins.

### Hierarchy
- **Display** (800, clamp(5rem, 21vw, 17.5rem), 0.8): the hero name only, stacked on two lines with the second line indented 0.34em.
- **Headline** (800, clamp(2.6rem, 7vw, 5.5rem), 0.9): section titles. Scale up for the Hello title (clamp(3rem, 8vw, 6rem)) and the closing title (clamp(3.4rem, 11vw, 9.5rem), 0.86, max 9ch); case-study names sit at clamp(2.4rem, 6.6vw, 5.25rem) in cream.
- **Title** (700, clamp(1.6rem, 4.4vw, 3.4rem), 1.12): the staggered skills list, cream.
- **Lede** (700 Bricolage, clamp(1.25rem, 2.2vw, 1.75rem), 1.25): the one-line hero statement, max 22ch.
- **Body** (400 Nunito, 1.0625rem, 1.65): default text. Body Large (clamp(1.125rem, 1.6vw, 1.3rem), 1.6) for intro paragraphs, held to 38-40ch. Case taglines use Nunito italic at clamp(1.2rem, 2vw, 1.55rem).
- **Label** (700 Bricolage, 0.8125rem, 0.14em, uppercase): roles, grid group names, view badges, social pills, the gondola link.
- **Marquee** (800 Bricolage, clamp(1.3rem, 2.6vw, 2.1rem), 0.08em, uppercase): marquee bands only.
- **Script** (400 Ballet, line-height 1): short accents ("Ash Schnoor" in the Hello title, "say hi"), always rotated -4 to -5deg and paired with a sparkle.

### Named Rules
**The Tight Display Rule.** Bricolage display always runs at weight 800, opsz 96, negative tracking (-0.035em to -0.045em) and line-height under 1. Balance-wrapped.

**The Signed Script Rule.** Ballet is a signature, not a typeface for sentences: two or three words, tilted, larger than the headline it joins (1.15em), in cream on dark or On Pink on pink.

**The Labels Follow Rule.** Caps labels name the thing they sit beside or under (a role under a case name, a group name over its grid). They never sit above a headline as a kicker.

## Layout

One centered container, min(100% - 2 x gutter, 78rem), with a fluid gutter (spacing.gutter). Sections stack in a single long scroll with no sticky nav: hero, marquee, hello, what I do, reverse marquee, where I've worked, the work, closing. Full-bleed color only comes from marquee bands, the lifted "worked" band and the pink closing footer; everything else sits on Night.

Vertical rhythm is generous and fluid: section padding runs roughly clamp(4rem, 9vw, 7.5rem) to clamp(4.5rem, 10vw, 8.5rem). The hero fills 100svh with content vertically centered.

Asymmetry comes from offsets, not columns: skill lines are indented 0 / 22% / 9% / 41% / 16% / 33% (collapsing to 0 / 12% alternating on narrow screens); even-numbered case studies right-align their head and swap the phone to the right; the Hello panel is indented clamp(0rem, 6vw, 5rem).

Grids: the case feed is 5fr / 6fr (phone / panel); the "worked" logo row and the reel grid are both four equal columns, dropping to two at 760px, the single breakpoint. The reel grid gap is tight (spacing.grid-gap) so thumbnails read as a contact sheet.

**The Logo Row Rule.** Organization logos sit in fixed-height cells (clamp(5rem, 9vw, 7.5rem)), contained and centered; wide wordmarks cap at 62% of that height so every logo reads at similar visual weight. A logo that is missing falls back to the organization name set in 800 Bricolage.

## Elevation & Depth

Flat by default. Surfaces separate by tone (Night to Night Lifted) and by full pink bands, not by shadow. Depth appears only on things that are meant to look like physical objects stuck onto the page.

### Shadow Vocabulary
- **Phone lift** (`box-shadow: 0 1.5rem 3rem -1rem rgb(0 0 0 / 0.7), 0 0.3rem 0.8rem rgb(0 0 0 / 0.5)`): the phone mockup only, plus a hairline cream outline at 14% opacity so the black bezel reads against Night.
- **Sticker drop** (`filter: drop-shadow(0 0.25rem 0.35rem rgb(16 16 16 / 0.22))`): the felt star resting on the phone.

### Named Rules
**The Objects Only Rule.** Shadows belong to objects (phones, stickers). Panels, bands, tiles and chips stay flat. Shadows are soft and blurred; no hard offset shadows.

## Shapes

Two families: soft rounds for interface, drawn silhouettes for ornament.

- **Interface rounds:** pills (rounded.pill) for the email chip and social links; a small corner (rounded.tile) on reel thumbnails and view badges; large device radii for the phone (rounded.phone) and its screen (rounded.phone-screen).
- **Scalloped panel:** a pink block whose every edge is a run of half-circles, cut with a radial-gradient mask (circle radius spacing.scallop-radius, spacing.scallop-radius-narrow under 760px). Padding clears two radii plus the content inset.
- **Four-point sparkle:** ends every title rule, prefixes script accents. Pink on dark, cream on pink.
- **Twelve-point starburst:** separates marquee words and prefixes grid group labels.
- **Scalloped circle badge:** 16-lobe pink rosette with a near-black arrow; the hero scroll cue.
- **Title rule:** a 3px pink rounded bar that runs into a 1.9rem sparkle, under every section headline.
- **Scribble:** two cream hand-drawn strokes (stroke-width 7, round caps) under the hero name.
- **Felt star:** a five-point pink star with a turbulence "felt" filter and a dashed near-black stitch, pinned to the phone's top-right corner at 12deg.
- **Cat sticker:** the cream-and-pink cat (images/cat.svg) lounging on the hero name, rotated -4deg.

## Components

### Email Chip
Friendly and small: the contact link as a pill with a pink icon disc.
- **Shape:** full pill; 2.5rem pink disc holding a stroked envelope in On Pink.
- **Color:** cream bold text on Night, no fill at rest.
- **Hover:** fills Night Lifted (0.2s).

### Social Pills
- **Style:** On Pink pills with cream caps label, on the pink footer.
- **Hover:** inverts to cream fill, On Pink text.

### Scalloped Panel
The signature container. Pink, scallop-edged, On Pink text. Used for the Hello intro and beside each phone mockup (with the organization name as an On Pink headline). Reveals on scroll.

### Marquee Band
Full-bleed pink band of uppercase 800 Bricolage words separated by On Pink starbursts, drifting linearly (38s default, 30s and reversed for the second band). Content repeats to overfill and loops at -50%.

### Phone Mockup
A black device frame (padding 0.7rem, 9:19.5 screen, top-cropped cover image, drawn pill notch) holding one real post that links out. Carries the phone lift shadow and the felt star, which tilts to 4deg and scales 1.03 on hover. Reveals once on scroll (fade and 2rem rise, 0.9s).

### Reel Grid
Four-column contact sheet of 9:16 thumbnails, each linking to the post, each carrying a Night view-count badge (caps, 0.75rem) at bottom-left. Thumbnails scale 1.03 on hover inside their clipped tile. Headed by a pink caps group label with a starburst.

### Case Head
Case name in cream headline type, pink caps role below, Nunito italic tagline (max 34ch), then optional stats: pink 800 numbers at 1.6rem with body-weight units and a cream caps link to the full archive. Alternates left and right alignment by case.

### Scroll Cue
Scalloped pink badge (6.25rem, 5rem narrow) beside a Soft Mauve line; rotates 20deg on hover and smooth-scrolls to Hello.

### Asset Slots
Every image-bearing block reads from a config object at the top of the script (portrait, hello photo, hero sticker, logos, feeds, grids, socials). An empty slot removes its block entirely and the layout closes around it (the Hello section switches to a solo layout; a role with no feed shows only its head).

### Motion
Ease is cubic-bezier(0.16, 1, 0.3, 1) throughout. The scribble draws once on load (1.5s, second stroke delayed); the marquee is the only continuous motion; reveals, felt-star tilt and badge rotation are one-shot or hover. Smooth scroll is enabled only when reduced motion is not requested; under reduced motion the marquee stops, the scribble shows fully drawn and reveals are shown immediately.

## Do's and Don'ts

### Do:
- **Do** set every headline in Bricolage 800 with negative tracking and line-height under 1, in Hot Pink on dark or On Pink on pink.
- **Do** end each section headline with the pink title rule and sparkle.
- **Do** put readable text on pink in On Pink (#0F0B10).
- **Do** reach for the drawn shapes (sparkle, starburst, scallop, scribble, felt star) instead of icons for ornament.
- **Do** keep the marquee the only ambient motion and give every animation a reduced-motion fallback.
- **Do** size logos in fixed-height cells with wide wordmarks capped at 62% of the cell.
- **Do** omit a block whose real asset is missing.

### Don't:
- **Don't** set cream text on Hot Pink; it falls below 3:1.
- **Don't** add placeholders, stock icons or stand-in imagery for missing work.
- **Don't** put caps labels above headlines as kickers.
- **Don't** add shadows to panels, bands or tiles, and don't use hard offset shadows anywhere.
- **Don't** use Ballet for more than a few words or leave it untilted.
- **Don't** reintroduce the spec PDF's cream ground or indigo headlines; the dark palette supersedes them.
