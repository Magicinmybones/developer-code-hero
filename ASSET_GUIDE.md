# Asset and Implementation Guide

## 1. Reference Summary

The reference is the first viewport of a monochrome SaaS landing page for an AI-assisted developer workspace. It contains a bordered navigation bar, a centered hero message, two calls to action, a detailed code-editor preview, subtle plus-sign texture, diagonal hatch dividers, and a four-logo customer strip.

## 2. Coded Editor Section

The complete page and code-editor preview are implemented directly in the self-contained `index.html`. The editor is not an image asset.

The implementation includes:

- Window frame and colored traffic-light controls
- File Manager project header and active `card.jsx` tab
- Nested folder and file tree with CSS-drawn icons
- Editor gutter and line numbers
- Syntax-highlighted React example
- Precise panel borders, dimensions, spacing, clipping, and responsive overflow
- Subtle plus-grid backdrop

The supplied page already integrates the editor into the full landing page. Do not replace it with a screenshot.

## 3. Available Assets

### europa.png

Path: `assets/logos/europa.png`

Purpose: Europa symbol and wordmark from the first customer cell.

Background: Transparent.

### eclipseful.png

Path: `assets/logos/eclipseful.png`

Purpose: Eclipseful symbol and wordmark from the second customer cell.

Background: Transparent.

### ikigai-labs.png

Path: `assets/logos/ikigai-labs.png`

Purpose: Ikigai Labs symbol and wordmark from the third customer cell.

Background: Transparent.

### eightball.png

Path: `assets/logos/eightball.png`

Purpose: Eightball symbol and wordmark from the fourth customer cell.

Background: Transparent.

## 4. Remaining Elements to Recreate

- Off-white page and panel backgrounds
- Thin charcoal borders around the header, hero, and customer cells
- Diagonal hatch divider strips
- Navigation labels and dropdown chevrons
- Header's geometric circular mark
- Sign In, Register, Get Started, and Book a Call buttons
- Corner-bracket accents around outlined buttons
- Hero headline and supporting copy
- Customer-strip layout and cell dividers

Use HTML/CSS for these elements. Avoid rasterizing text, buttons, borders, patterns, or layout containers.
