---
name: BI-Vision Networks
description: See it. Secure it. Connect it.
colors:
  deep-navy: "#062B57"
  royal-blue: "#1464B8"
  safety-yellow: "#FFBE18"
  true-white: "#FFFFFF"
  pale-blue-gray: "#EAF2F8"
  near-black-navy: "#071828"
typography:
  display:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(3.5rem, 8vw, 6rem)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "-0.025em"
  body:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  body-compact:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  lead:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "1.15rem"
    fontWeight: 400
    lineHeight: 1.5
  title:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "2rem"
    fontWeight: 700
    lineHeight: 1
  service-title:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "1.8rem"
    fontWeight: 700
    lineHeight: 1
  wordmark:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "1.55rem"
    fontWeight: 700
    lineHeight: 0.78
  wordmark-secondary:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "1.28rem"
    fontWeight: 700
    lineHeight: 0.78
  step-number:
    fontFamily: "Barlow Condensed, Arial Narrow, sans-serif"
    fontSize: "1.65rem"
    fontWeight: 700
    lineHeight: 1
  label:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    lineHeight: 1.4
  label-compact:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 600
    lineHeight: 1.4
  label-micro:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 600
    lineHeight: 1.4
  note:
    fontFamily: "Source Sans 3, Segoe UI, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.5
rounded:
  sm: "4px"
  md: "10px"
  pill: "999px"
spacing:
  xs: "8px"
  sm: "12px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  section: "clamp(64px, 9vw, 120px)"
components:
  button-primary:
    backgroundColor: "{colors.safety-yellow}"
    textColor: "{colors.near-black-navy}"
    rounded: "{rounded.sm}"
    padding: "14px 22px"
  button-secondary:
    backgroundColor: "{colors.deep-navy}"
    textColor: "{colors.true-white}"
    rounded: "{rounded.sm}"
    padding: "14px 22px"
---

# Design System: BI-Vision Networks

## Overview

**Creative North Star: "The Connected Field Report"**

The interface combines the clarity of professional field-engineering documentation with the welcome of a capable local installer. Bright white space makes the service approachable; disciplined navy fields communicate protection; yellow connection lines guide attention from a need to the next action.

The system is minimalist, not sparse. Typography, verified project photography, and clear section rhythm do the work. It rejects hacker theatrics, generic SaaS cards, and invented proof.

**Key Characteristics:**

- Bright, structured, and immediately readable
- Real installation imagery instead of decorative stock claims
- Condensed, equipment-label display typography
- Yellow used as a connection and action signal
- Flat surfaces with decisive tonal transitions

## Colors

Deep navy carries trust and technical discipline; safety yellow is reserved for action and connection.

### Primary

- **Deep Protection Navy:** Dominant brand field for the project story, footer, and strong text.
- **Safety Signal Yellow:** Primary actions, focus indicators, and the route-line motif.

### Secondary

- **Connected Royal Blue:** Links, supporting details, and selected states.

### Neutral

- **True White:** Main page canvas and clear reverse text.
- **Field Sheet Blue-Gray:** Section separation and quiet surfaces.
- **Near-Black Navy:** Body text and maximum-contrast details.

**The Signal Rule.** Yellow marks an action, a connection, or a numbered process step. It is never ambient decoration.

## Typography

**Display Font:** Barlow Condensed (with Arial Narrow fallback)  
**Body Font:** Source Sans 3 (with Segoe UI fallback)

**Character:** The pairing contrasts narrow, decisive headlines with humanist, highly legible supporting copy. It feels like durable equipment labeling translated into approachable service communication.

### Hierarchy

- **Display** (700, fluid, 0.95): Hero statements only; never exceed 6rem.
- **Headline** (700, fluid, 1): Major section ideas.
- **Title** (600, 1.25rem, 1.2): Service and process titles.
- **Body** (400, 1.0625rem, 1.6): Explanations capped at 68ch.
- **Label** (600, 0.875rem, 0.06em): Short operational labels only.

**The Plain-Language Rule.** Technical precision belongs in the nouns and verbs, not in dense jargon or all-caps paragraphs.

## Elevation

The design is flat by default. Depth comes from tonal fields, image cropping, dividers, and overlapping route-line details. Shadows appear only on temporary navigation or focused interactive states and remain tight.

**The Field-Flat Rule.** If a section needs a large soft shadow to feel organized, its spacing and hierarchy are wrong.

## Components

### Buttons

- **Shape:** Firm, gently eased corners (4px), never bubble-like.
- **Primary:** Safety yellow with near-black navy text and a directional arrow.
- **Hover / Focus:** Slight color darkening; a high-contrast 3px focus ring with offset.
- **Secondary:** Deep navy with true-white text or a simple text link with a directional arrow.

### Cards / Containers

- **Corner Style:** Restrained (10px maximum).
- **Background:** White or field-sheet blue-gray.
- **Shadow Strategy:** None at rest.
- **Border:** Full-perimeter hairline only when separation is necessary.
- **Internal Padding:** 24–32px from the documented spacing scale.

### Inputs / Fields

- **Style:** Visible labels, white background, full navy hairline, 4px corners.
- **Focus:** Royal-blue border plus a safety-yellow outer ring.
- **Error / Disabled:** Text and icon reinforce color; errors appear below their field.

### Navigation

White and compact with the placeholder shield and wordmark at left, direct section links, and a yellow call action. Mobile navigation uses an accessible disclosure panel and retains the call action.

### Connection Route

A thin yellow line with circular terminals links project imagery, steps, and CTAs. It remains semantic SVG/CSS, never rasterized with text.

## Do's and Don'ts

### Do:

- **Do** use verified BI-Vision installation photography and accurate project scope.
- **Do** reserve yellow for actions, focus, and meaningful connection lines.
- **Do** adapt the composition for mobile rather than shrinking the desktop layout.
- **Do** keep body copy at least 1rem with strong contrast and comfortable measure.
- **Do** respect reduced-motion preferences.

### Don't:

- **Don't** use hacker or cyberpunk surveillance aesthetics.
- **Don't** use generic SaaS landing-page templates, hero metrics, or repeated icon cards.
- **Don't** use luxury black-and-gold styling, excessive glow, or glassmorphism.
- **Don't** invent locations, awards, review counts, testimonials, or certifications.
- **Don't** use gradient text, cream or beige surfaces, decorative grid backgrounds, or colored side-stripe borders.
- **Don't** embed important copy inside raster images.
