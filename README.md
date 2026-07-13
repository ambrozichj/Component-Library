# Dwell Component Library

Reusable UI components for **dwellcc.org**, pulled straight from the live site — real markup, real CSS, real responsive behavior. Use these when building a new Dwell page or Rock HTML block instead of rebuilding components from scratch.

## Browse the gallery

**→ https://ambrozichj.github.io/Component-Library/**

A live, interactive catalog of every component: preview it, flip to **Code**, and **Copy**. This is the place to look while designing.

## Use a component

1. Open the [gallery](https://ambrozichj.github.io/Component-Library/), find the component.
2. Click **Code** → **Copy**.
3. Paste into your Rock HTML block (or any Dwell page). Each component is self-contained — its styles travel with it. On dwellcc.org the fonts (Circe/Lato), Font Awesome, jQuery, and GSAP are already loaded site-wide, so most components work as-is.

## Use it with Claude

Point Claude at the guide and ask it to build:

> Refer to `https://raw.githubusercontent.com/ambrozichj/Component-Library/main/CLAUDE.md` for Dwell design instructions and components, then build me a new [page/section].

Claude reads [`CLAUDE.md`](./CLAUDE.md) (design tokens, component index, rules) and pulls real component source from `library.html`.

## What's here

| File | Purpose |
|---|---|
| `library.html` | The gallery + all component source. Also the file you paste into a Rock block. |
| `CLAUDE.md` | Machine-readable guide for Claude: tokens, conventions, component index, dependencies, composition. |
| `index.html` | Redirect so the GitHub Pages root URL opens the gallery. |

## What's inside (24 components)

Foundations (colors, typography, buttons, eyebrow) · Page sections (hero, member notice, page title bar) · Cards (feature, featured events, image callout, link, icon, explore-interest, resource-type) · Lists (content rows, topic tiles) · Giving (info cards, split link rows, scripture quote) · Resources app (filter panel, grouped list, CTA) · Site chrome (header, footer).

See [`CLAUDE.md`](./CLAUDE.md) for the full index and when to use each.

## Design basics

- **Font:** Circe is primary across every component (headings 900; body 400/700).
- **Core colors:** dark teal `#03272D` · leaf green `#07841B` · lime `#72DB2B` · body text `#515E61`.
- Full palette, type scale, spacing, radii, and breakpoints are in [`CLAUDE.md`](./CLAUDE.md).

## Updating

Edit `library.html` (and mirror any component change in `CLAUDE.md`), then commit + push. GitHub Pages and the raw URLs update automatically.

---

Components mirror the public dwellcc.org site — no member data, giving details, or admin surfaces. Safe to keep public.
