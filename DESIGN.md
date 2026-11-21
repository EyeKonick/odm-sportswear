---
name: ODM Sportswear
description: Clean sportswear-retail storefront where the team's own finished kit is the product on the shelf.
colors:
  royal-blue: "#012c95"
  signal-red: "#d7141a"
  utility-black: "#000000"
  ink: "#0b0f1e"
  white: "#ffffff"
  on-blue: "#dfe6fb"
  muted-slate: "#4a5068"
  hairline: "#e3e5ec"
  wash: "#f3f4f7"
  on-black: "#e9e9e9"
  on-black-muted: "#9aa0b4"
typography:
  display:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "7.1rem"
    fontWeight: 300
    lineHeight: 0.93
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "30px"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.01em"
  title:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "0.12em"
  body:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  lede:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0.03em"
  label:
    fontFamily: "Jost, system-ui, sans-serif"
    fontSize: "12.5px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.16em"
  script:
    fontFamily: "Mrs Saint Delafield, cursive"
    fontSize: "84px"
    fontWeight: 400
    lineHeight: 1
rounded:
  none: "0px"
spacing:
  gutter-desktop: "56px"
  gutter-tablet: "32px"
  gutter-mobile: "20px"
  container-max: "1440px"
  stack-sm: "16px"
  stack-md: "40px"
  stack-lg: "72px"
  section: "112px"
components:
  button-primary:
    backgroundColor: "{colors.utility-black}"
    textColor: "{colors.white}"
    rounded: "{rounded.none}"
    typography: "{typography.label}"
    height: "50px"
    padding: "0 24px"
  button-primary-hover:
    backgroundColor: "{colors.signal-red}"
    textColor: "{colors.white}"
  button-outline-on-blue:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    rounded: "{rounded.none}"
    height: "50px"
    padding: "0 24px"
  button-outline-on-blue-hover:
    backgroundColor: "{colors.white}"
    textColor: "{colors.royal-blue}"
  button-outline-on-white:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    height: "50px"
    padding: "0 24px"
  button-outline-on-white-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
  nav-cta:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "12px 16px"
  nav-cta-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
  utility-bar:
    backgroundColor: "{colors.utility-black}"
    textColor: "{colors.on-black}"
    height: "32px"
  nav-bar:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    height: "68px"
  page-panel:
    backgroundColor: "{colors.royal-blue}"
    textColor: "{colors.white}"
  design-card-frame:
    backgroundColor: "{colors.wash}"
    rounded: "{rounded.none}"
  contact-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "12px 36px"
  footer:
    backgroundColor: "{colors.utility-black}"
    textColor: "{colors.on-black}"
---

# Design System: ODM Sportswear

## Overview

**Creative North Star: "The Team Shelf"**

A clean sportswear-retail storefront in which the team's own finished kit is the product on the shelf. The ground is white; royal blue arrives as full-bleed field panels at the top of every page and in the ordering band; black is the utility bar, the primary button and the footer. Real ODM mockups do the selling: they sit on the blue panel or on a pale wash, lift off it with one soft shadow, and on Home, Browse Designs and Contact an object (mockup or contact card) overhangs the panel's bottom edge into the white page below.

Type is all Jost: light-weight uppercase display set big, tracked uppercase labels, and calm mixed-case body. One handwritten accent, Mrs Saint Delafield, names the kit or the idea it sits beside. Red is a signal, never a field: hairline rules, the active-nav underline, hover and focus. Everything is square-cornered. The system refuses the dark, flame-and-neon "athletic" template.

**Key Characteristics:**
- White ground, royal-blue field panels, black utility bar, buttons and footer.
- Jost light uppercase display, tracked uppercase labels, one script accent.
- Red only as hairlines, active-nav underline, hover and focus.
- Square corners everywhere; 1px and 1.5px lines carry structure.
- One soft drop-shadow family under mockups and overhanging cards.
- Real mockups at or below natural size; logos exactly as supplied.

## Colors

A three-ink retail palette (blue, black, red) on white, with cool neutrals that lean slightly toward the blue.

### Primary
- **Royal Field Blue** (royal-blue): full-bleed page-head panels on every page, the "How ordering works" band, step numerals and filter-type tags on white, the check icons in lists, the script accent on light grounds, text selection and the browser theme color.

### Secondary
- **Signal Red** (signal-red): the 56 x 3px section rule above every headline, the active and hovered nav underline, active filter, text-link and phone-link hover, the primary button's hover fill, footer link underline on hover, and the 2px focus ring.

### Neutral
- **Utility Black** (utility-black): the 32px utility bar, primary buttons, footer, skip link.
- **Ink** (ink): all body and heading text on white; dark outline buttons and the nav CTA border; the 1px rule that heads lists, product-type rows and the filter bar.
- **White** (white): page ground, text and outlines on blue, contact card.
- **On-Blue Mist** (on-blue): ledes and step body copy on the blue panel.
- **Muted Slate** (muted-slate): secondary text on white and wash (card meta, intro paragraphs, field labels, captions).
- **Hairline** (hairline): 1px dividers on white (product-type columns, step tops, contact-card rows, section separators).
- **Mockup Wash** (wash): the quiet ground of design-card frames and the Contact "What to prepare" band.
- **On-Black** (on-black) and **On-Black Muted** (on-black-muted): utility-bar and footer text; muted for footer labels, icons and the base line.

### Named Rules
**The Red Is a Signal Rule.** Signal Red is never a panel, card, text block or large fill. It appears as hairlines (the 56 x 3px rule, 1.5px underlines), the active-nav underline, hover states (including the primary button's hover fill) and the focus ring. If red covers an area at rest, it is wrong.

**The Blue Is a Field Rule.** Royal blue is used as a full-bleed panel or as small accents on white (numerals, tags, icons, script). It never becomes a button fill; on blue, buttons are black primary or white outline.

## Typography

**Display Font:** Jost (with system-ui, sans-serif), weights 300 / 400 / 500 / 600, self-hosted via Fontsource.
**Script Font:** Mrs Saint Delafield (with cursive), weight 400.

**Character:** Geometric, airy Jost in light uppercase reads like a retail storefront sign; the handwritten script is a single signature flourish that names the kit.

### Hierarchy
- **Display** (300, 7.1rem at desktop; 6.2rem at 1280px, 5.2rem at 1100px, 3.4rem at 640px; line-height 0.93; uppercase): Home hero headline, and inner page heads and the Home "How ordering works" title at 5.6rem (4.4rem tablet, 3rem phone).
- **Headline** (400 with 600 bold words, 30px / 23px phone, line-height 1.2, 0.01em, uppercase): section headings, always preceded by the red rule. The bold half carries the key phrase ("Featured **designs**").
- **Title** (500, 15 to 19px, 0.12 to 0.14em tracking, uppercase): design-card names, step titles, checklist items.
- **Body** (400, 16px, line-height 1.55); secondary paragraphs at 14.5 to 15.5px in Muted Slate, capped near 34 to 48ch.
- **Lede** (400, 17px, line-height 1.5, 0.03em): the paragraph under a display headline, 38 to 46ch.
- **Label** (500, 12.5 to 13px, 0.14 to 0.16em, uppercase): nav, buttons, field labels, text links, footer column heads.
- **Large figure** (300, 28 to 56px): step numerals and the Contact phone and shop links, tabular numerals.
- **Script** (400, 84px base; 56 to 72px in context, 60px phone): one name or phrase, rotated -5 to -8 degrees.

### Named Rules
**The Script Ground Rule.** The Mrs Saint Delafield accent is white on the royal blue panel and where it crosses a saturated photo (Home hero "Aurora Vega"). On light grounds (white or the wash) it is royal blue, as on the Contact "Names & numbers" caption. It is never set over pale photo areas. One script line per view, decorative only (aria-hidden or doubled by real text).

**The Light Caps Rule.** Display is Jost 300 uppercase; weight comes from size, not boldness. Bold (600) appears only as the emphasised half of a headline.

## Layout

A 1440px max container with a 56px gutter (32px below 1100px, 20px below 640px). Every page opens with the same stack: 32px black utility bar, 68px white nav, then a full-bleed royal-blue panel (590px on Home, shorter on inner pages, 64px top / 72px bottom padding). Sections breathe at 104 to 128px vertical padding; inner gaps step through 16, 40, 56 and 72px.

The signature move is the overhang: the Home hero mockup (560px wide), the Browse Designs header mockup (440px) and the Contact card each start on the blue panel and cross its bottom edge into the white below. Grids: product types in six equal columns divided by hairlines (three at tablet, two at phone); featured designs three-up (two, then one); the gallery two-up; order steps four-up (two, then one). Breakpoints at 1280, 1100, 760, 640 and 560px collapse absolute hero positioning into a flowing stack.

**The Natural Size Rule.** A real mockup is never displayed wider than its natural pixel width (the Home hero is capped at 560px for a 630px source; gallery frames stay under the 975 to 1200px sources). Frames share one aspect ratio (979 / 923) so captions align; images fill with object-fit cover, never upscaled.

## Elevation & Depth

Flat surfaces with one soft drop-shadow family that only ever sits under real objects: mockups and the overhanging cards. Shadows are long, low and negatively spread so they read as a single soft pool beneath the object, never as an outline.

### Shadow Vocabulary
- **Overhang** (`box-shadow: 0 30px 60px -24px rgba(0, 0, 0, .4)`): the hero mockup, the Browse Designs header mockup and the Contact card where they overhang the blue panel.
- **Resting mockup** (`box-shadow: 0 24px 44px -30px rgba(1, 20, 70, .45)`, hover `0 34px 56px -30px rgba(1, 20, 70, .55)` with a 4px lift): design-card frames on white and wash.

### Named Rules
**The One Shadow Rule.** Only mockups and overhanging cards cast a shadow, and only this soft family. Buttons, nav, panels, chips and text never do.

## Shapes

Square corners throughout (0px radius): buttons, cards, frames, panels, inputs. Structure is drawn with lines: 1px Hairline dividers, 1px Ink rules that head lists and the filter bar, 1.5px outlines on secondary buttons, 1.5px underlines on links and active nav, and the 56 x 3px red rule. The only curves are in the supplied logos and the script.

**The Logos As Supplied Rule.** The chrome wordmark, varsity badge, O-M mark and tagline lockup are placed exactly as supplied: cropped only, never redrawn, recolored, outlined, shadowed or restyled.

## Components

### Buttons
- **Shape:** square (0px), 50px tall, 24px side padding, 12px icon gap, Label type at 13px / 0.14em.
- **Primary:** Utility Black fill, white text, optional Messenger icon; hover fills Signal Red.
- **Outline on blue:** 1.5px white border, white text; hover inverts to white fill with Royal Blue text.
- **Outline on white:** 1.5px Ink border, Ink text; hover fills Ink.
- **Focus:** 2px Signal Red outline, 3px offset (global).

### Text Link
- Label type (11.5 to 12.5px, 0.16em), 1.5px currentColor underline, trailing arrow icon at 14px; hover turns red. A quiet variant uses Muted Slate with a Hairline underline.

### Navigation
- **Utility bar:** 32px black, 12.5px On-Black text, phone and shop links with 14px icons.
- **Main nav:** 68px white; O-M mark plus tracked 0.22em wordmark left, centred uppercase links (13px, 0.16em, 44px gaps), 1.5px underline that turns red with red text on hover and on the current page; an outlined "Order on Messenger" CTA right (hover fills Ink). Below 760px the links wrap to a scrollable second row and the wordmark hides below 1100px.

### Chips (filters)
- Unboxed uppercase labels (13px, 0.16em) with a small muted count; pressed and hover states turn red, pressed adds the 1.5px red underline. The bar is closed by a 1px Ink rule.

### Cards / Containers
- **Design card:** Wash frame at 979 / 923, resting-mockup shadow, hover lift 4px and 1.025 image zoom; caption with Title-style name, muted meta, and (in the gallery) a blue type label.
- **Contact card:** white, overhang shadow, 12px 36px padding, rows split by Hairlines, each a field label over a black primary button or a 300-weight large figure link.
- **Order steps:** top-ruled columns with a 56px light numeral (blue on white, white on blue), uppercase title, muted body.

### Footer
- Black, three columns (tagline lockup and line, Order links with 16px icons, Pages); links underline in red on hover; base line above a 1px #222 rule.

### Motion
- Easing `cubic-bezier(.16, 1, .3, 1)`. Color changes 0.2s; card lift 0.5s; image zoom 0.8s; hero mockup rises 18px over 1s on load; filtered cards fade up 10px over 0.6s. All motion and smooth scroll are disabled under reduced motion.

## Do's and Don'ts

### Do:
- **Do** open every page with the black utility bar, white nav and a royal-blue panel holding a Jost 300 uppercase display title.
- **Do** put a 56 x 3px Signal Red rule above every section headline.
- **Do** set the script accent white on blue or over a saturated photo, and royal blue on white or wash.
- **Do** let one real mockup or card overhang the blue panel's bottom edge, carrying the overhang shadow.
- **Do** show mockups at or below their natural width, in the shared 979 / 923 frame on the wash ground.
- **Do** keep every corner square and draw structure with 1px and 1.5px lines.

### Don't:
- **Don't** use Signal Red as a fill, panel or running-text color; at rest it appears only as hairline rules and the active nav or filter, otherwise only on hover and focus.
- **Don't** set the script over pale photo areas, or use more than one script line per view.
- **Don't** add rounded corners, extra shadow styles, or shadows on buttons, panels or text.
- **Don't** upscale a mockup past its natural pixel width.
- **Don't** redraw, recolor, outline or restyle any ODM logo; use it exactly as supplied.
- **Don't** use dark, flame, neon or gradient "athletic" treatments.
