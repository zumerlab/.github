<div align="center">

# ZumerLab

**Embracing the unconventional.**

We build open-source tools that push the boundaries of what's possible on the web — from radial CSS layouts to ultra-fast DOM capture and spatial zoom navigation.

[![GitHub Org](https://img.shields.io/badge/GitHub-ZumerLab-181717?logo=github)](https://github.com/zumerlab)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

</div>

---

## Our Projects

### 💫 Orbit — Radial UI Framework

[![Stars](https://img.shields.io/github/stars/zumerlab/orbit?style=flat&label=Stars)](https://github.com/zumerlab/orbit) [![npm](https://img.shields.io/npm/v/@zumer/orbit?label=npm)](https://www.npmjs.com/package/@zumer/orbit)

**Orbit** is a CSS framework for building radial UIs — gauges, donuts, knobs, pie menus, dashboards — with **CSS only**. No layout JavaScript required. It works with plain HTML and any framework (React, Vue, Svelte).

Radial UIs usually require JavaScript to compute angles, radii, and positions. Orbit handles all of that with CSS classes and a couple of Web Components. Drop in two files and start building.

**Use cases:** dashboards, speedometers, IoT thermostats, activity rings, knob controls, radial menus, watch faces, and more.

🔗 [Repository](https://github.com/zumerlab/orbit) · [Documentation](https://zumerlab.github.io/orbit-docs/)

---

### 📸 SnapDOM — DOM Capture Engine

[![Stars](https://img.shields.io/github/stars/zumerlab/snapdom?style=flat&label=Stars)](https://github.com/zumerlab/snapdom) [![npm](https://img.shields.io/npm/v/@zumer/snapdom?label=npm)](https://www.npmjs.com/package/@zumer/snapdom)

**SnapDOM** is a next-generation DOM capture engine — ultra-fast, modular, and extensible. It converts any DOM subtree into a self-contained representation that can be exported to SVG, PNG, JPG, WebP, Canvas, or Blob.

It captures full DOM with embedded styles, pseudo-elements, and fonts. It's 100% based on standard Web APIs with zero dependencies. SnapDOM also features a plugin system for custom transforms and exporters.

**Performance:** captures simple elements in ~0.5 ms and complex page views in ~17.5 ms — orders of magnitude faster than alternatives.

🔗 [Repository](https://github.com/zumerlab/snapdom) · [Demo](https://snapdom.dev)

---

### 🔍 Zumly — Spatial Zoom Navigation

[![Stars](https://img.shields.io/github/stars/zumerlab/zumly?style=flat&label=Stars)](https://github.com/zumerlab/zumly) [![npm](https://img.shields.io/npm/v/zumly?label=npm)](https://www.npmjs.com/package/zumly)

**Zumly** is a JavaScript library for hierarchical zoom navigation. Users move in depth (Z) through discrete views laid out in the XY plane, with spatial transitions instead of flat screen swaps.

It's framework-agnostic and supports pluggable transition drivers (CSS, WAAPI, Anime.js, GSAP, Motion, or custom), a built-in router plugin, lateral navigation, and multiple view sources including HTML strings, URLs, async functions, and web components.

**Ideal for:** menus, stories, dashboards, exploratory UIs, and any interface where spatial context between parent and child should persist.

🔗 [Repository](https://github.com/zumerlab/zumly)

---

## Quick Install

```bash
# Orbit
npm install @zumer/orbit

# SnapDOM
npm install @zumer/snapdom

# Zumly
npm install zumly
```

---

## Philosophy

At ZumerLab we believe the web deserves richer interaction models beyond flat rectangles and page swaps. Our tools are lightweight, dependency-free when possible, and designed to work with any framework or vanilla HTML. Everything is MIT-licensed.

---

## Get Involved

We welcome contributions, ideas, and feedback across all our projects.

❤️ [Sponsor us](https://github.com/sponsors/tinchox5)


 <div align="center">
   **MIT Licensed** · Made with ❤️ by the ZumerLab team
    </div>
