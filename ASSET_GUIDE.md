# Asset Guide

## 1. Reference Summary

The reference is the first viewport of a monochrome SaaS landing page for an AI-assisted developer workspace. It contains a bordered navigation bar, a large centered hero message, two calls to action, a detailed code-editor product preview, subtle plus-sign background texture, diagonal hatch dividers, and a four-logo customer strip.

The product preview and customer wordmarks are provided as assets because reproducing their detailed text, iconography, and brand forms in HTML/CSS would reduce visual fidelity. The rest of the composition should be recreated in code.

## 2. Available Assets

### hero-editor-preview.png

Path: `assets/images/hero-editor-preview.png`

Purpose: The large product-editor mockup shown in the lower half of the hero. It includes the window chrome, traffic-light controls, file tree, tab bar, line numbers, and syntax-highlighted code exactly as visible in the reference.

Placement: Centered below the CTA buttons. In the reference it is wide, slightly inset from the hero edges, and clipped by the bottom of the hero section.

Background: Opaque, preserving the editor panel's original white and light-gray surfaces.

Recommended usage: Render directly as a responsive image with its natural aspect ratio. Do not recreate or overlay the editor UI in HTML. Let the hero container clip the lower portion when matching the reference viewport.

### europa.png

Path: `assets/logos/europa.png`

Purpose: Europa symbol and wordmark from the first customer cell.

Background: Transparent.

Recommended usage: Center inside the first bordered logo cell. Preserve aspect ratio and render in the supplied charcoal tone.

### eclipseful.png

Path: `assets/logos/eclipseful.png`

Purpose: Eclipseful symbol and wordmark from the second customer cell.

Background: Transparent.

Recommended usage: Center inside the second bordered logo cell. Preserve aspect ratio.

### ikigai-labs.png

Path: `assets/logos/ikigai-labs.png`

Purpose: Ikigai Labs symbol and wordmark from the third customer cell.

Background: Transparent.

Recommended usage: Center inside the third bordered logo cell. Preserve aspect ratio.

### eightball.png

Path: `assets/logos/eightball.png`

Purpose: Eightball symbol and wordmark from the fourth customer cell.

Background: Transparent.

Recommended usage: Center inside the fourth bordered logo cell. Preserve aspect ratio.

## 3. Elements Claude Should Recreate

The following should not be treated as image assets:

- Off-white page background and the slightly lighter panel surfaces
- Thin charcoal borders around the header, hero, and customer cells
- Diagonal hatch divider strips above and below the hero
- Faint repeating plus-sign texture behind the editor preview
- Navigation labels and small dropdown chevrons
- Header's simple geometric circular mark, which can be recreated with CSS or inline SVG
- Sign In, Register, Get Started, and Book a Call buttons
- Corner-bracket accents around outlined buttons
- Hero headline, muted second line, and supporting copy
- Centered spacing, grid structure, responsive behavior, and clipping
- Customer-strip cell dividers

Use clean HTML/CSS for these elements. Avoid rasterizing text, buttons, borders, patterns, or layout containers.
