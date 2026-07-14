# Aurora Mart — Low-Fidelity Wireframe

A low-fidelity wireframe of the Aurora Mart mobile shopping app, converted as plain HTML/CSS from a figma design.
This represents the structural blueprint that the high-fidelity Aurora Mart UI was later
designed from.

## What this is
Converted from a Figma low-fidelity design into a working HTML/CSS build,
A single wireframe screen (Home) showing layout, content hierarchy, and navigation flow —
with no color, no real copy, and no real imagery, per standard low-fidelity wireframing
conventions:

- **Grayscale only** — no brand color or gradients
- **Greeked text** — gray bars stand in for headings and body copy, representing length/weight
  instead of real content
- **Placeholder imagery** — every photo spot is a dashed, hatched box labeled "image"
- **Flat, unstyled controls** — buttons are plain outlined rectangles, icons are bare circles
- **Structure over style** — the goal is to communicate what goes where, not the final look

## Screens / sections included

All on one scrollable page, matching the section order of the final design:

1. Status bar + header
2. Search bar
3. Category shortcuts
4. Hero banner / carousel
5. Flash Deals (product grid)
6. Today's Savings (stat summary)
7. Recommended for You (product grid)
8. Why Aurora Mart? (feature list)
9. Top Customer Reviews
10. Quick Categories (list)
11. Shop the Look (community posts)
12. Bottom navigation

## Files

```
aurora-mart-wireframe/
├── index.html   — page structure and content placeholders
├── styles.css   — grayscale wireframe styling
└── README.md    — this file
```

## How to run

No build step or dependencies. Just open `index.html` in any browser, or double-click the
file. For a live-reload dev view, you can also serve it locally:

```
cd aurora-mart-wireframe
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Using this in Figma / Adobe XD

This project is plain HTML/CSS, not a native `.fig` or `.xd` file. To bring it into Figma:

- **html.to.design plugin** (Figma) — import `index.html` directly as editable frames, or
- **Manual trace** — open the page in a browser, screenshot each section, and paste into a
  Figma frame at 390px width (the design's base mobile width), then trace over with Figma's
  native shape and text tools.


