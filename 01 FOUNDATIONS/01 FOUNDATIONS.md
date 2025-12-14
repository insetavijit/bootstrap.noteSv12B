```ruby
├── 1.1 Definitions & Keywords — essential terminology & version context
│   ├── Bootstrap — 
		open-source front-end framework for HTML, CSS & JS, focused on responsive, mobile-first design. :contentReference[oaicite:1]{index=1}
│   ├── v5.x — current major release line. Latest patch as of 2025 is v5.3.8. :contentReference[oaicite:2]{index=2}
│   ├── CDN build / Compiled CSS-JS bundle — ready-to-use minified distribution for quick integration. :contentReference[oaicite:3]{index=3}
│   ├── Source build (Sass + JS modules) — customizable version, allowing theming, variable overrides, custom compilation. :contentReference[oaicite:4]{index=4}
│   ├── Utility API & Sass maps — system for generating utility classes and customizing theme via Sass variables & maps. :contentReference[oaicite:5]{index=5}
│   └── Mobile-first & responsive grid system — core layout paradigm using containers, rows, columns + breakpoints. :contentReference[oaicite:6]{index=6}
│
├── 1.2 Core Principles — architectural & design foundations
│   ├── Responsive, mobile-first design — layout and components adapt across device sizes by default. :contentReference[oaicite:7]{index=7}
│   ├── Vanilla JS over jQuery — starting v5, Bootstrap no longer depends on jQuery; uses modern JS for plugins/interactivity. :contentReference[oaicite:8]{index=8}
│   ├── Component + Utility-based UI toolkit — predefined, styled components and low-level utilities to build UI quickly and consistently. :contentReference[oaicite:9]{index=9}
│   ├── Theming & customization via Sass / CSS variables — makes it easier to adapt colors, spacing, typography, layouts for different themes. :contentReference[oaicite:10]{index=10}
│   └── Modern browser support & dropping legacy constraints — Bootstrap 5 drops support for IE10/IE11 and legacy browsers; focuses on modern browser standards. :contentReference[oaicite:11]{index=11}
│
├── 1.3 Mental Models for Important Concepts — intuitive conceptual frameworks
│   ├── UI-Toolkit as LEGO — treat components + utilities as building blocks to assemble UIs rapidly.  
│   ├── Layered styling → Base + Modifier + Utility — base classes provide structure, modifiers & utilities tweak appearance/behavior. :contentReference[oaicite:12]{index=12}  
│   ├── Responsive Grid as Flexible Skeleton — container → row → column and utilities provide flexible layout across devices. :contentReference[oaicite:13]{index=13}  
│   ├── Progressive Enhancement Approach — HTML first, apply styling via classes/variables; JS optional for behavior (modals, dropdowns, etc.). :contentReference[oaicite:14]{index=14}  
│   └── Theming via Variables rather than Ad-Hoc Overrides — by using Sass maps or CSS variables, customizing design remains manageable and maintainable. :contentReference[oaicite:15]{index=15}  
│
├── 1.4 Architecture Overview — structural and operational map of the framework
│   ├── 1.4.1 High-Level Diagram —  
│   │     Developer → (HTML + Bootstrap classes/utilities) → CSS (compiled from Sass + variables) + JS plugins (vanilla) → Browser renders responsive layout & behavior → User interacts → JS handles interaction components → final UI  
│   │  
│   ├── 1.4.2 Components & Responsibilities —  
│   │     • Layout & Grid (containers, rows, columns) → responsive page structure & alignment :contentReference[oaicite:16]{index=16}  
│   │     • Pre-styled UI Components (buttons, navbars, cards, modals, forms, navs & tabs, etc.) → uniform, accessible, ready-to-use UI elements :contentReference[oaicite:17]{index=17}  
│   │     • Utility Classes & Helpers (spacing, display, typography, colors, visibility, flexbox, etc.) → quick styling without writing custom CSS :contentReference[oaicite:18]{index=18}  
│   │     • JS Plugins / Behavior Modules (modals, dropdowns, tooltips/popovers, collapse, carousel, offcanvas, etc.) → interactivity & UI behavior without extra dependencies :contentReference[oaicite:19]{index=19}  
│   │     • Theme / Style Source Layer (Sass + variables + custom CSS) → for customization, theming, and design flexibility :contentReference[oaicite:20]{index=20}  
│   │     • Build & Distribution Layer — compiled bundles (for convenience) or source-based builds (for customization) via npm/CDN/package managers. :contentReference[oaicite:21]{index=21}  
│   │  
│   └── 1.4.3 Data / Build Flow —  
│         ↓ Write HTML + add Bootstrap classes/utilities or custom Sass  
│         ↓ If using source: compile Sass → CSS, bundle JS (plugins)  
│         ↓ Browser receives CSS + JS (or CDN bundle) → rendering + layout + behavior  
│         ↓ User interacts → JS plugins handle interactivity (modals, dropdowns, etc.) → UI updates  
│
├── 1.5 Internals & Mechanics — behind-the-scenes processes and how Bootstrap works under the hood
│   ├── Sass-based source + Utility API + Sass maps — Bootstrap’s customizability backbone; generates component and utility classes dynamically based on configuration. :contentReference[oaicite:22]{index=22}  
│   ├── Vanilla JS modules for components — no jQuery dependency; components written in modern JavaScript (ES6+), offering better compatibility especially with JS frameworks (React, Vue, Angular). :contentReference[oaicite:23]{index=23}  
│   ├── Flexbox-based responsive grid & layout system — layout logic implemented via CSS Flexbox (and optionally CSS Grid in opt-in mode) for robust, fluid layouts. :contentReference[oaicite:24]{index=24}  
│   ├── Build / Distribution Options — either include precompiled CSS/JS bundle via CDN/npm, or build from source (Sass + JS) for custom themes, tree-shaking, and size optimization. :contentReference[oaicite:25]{index=25}  
│   └── Theming & Mode Support (Dark Mode & Custom Color Modes) — v5.3 introduced built-in dark mode / multiple color mode support via Sass / CSS variables, enabling dynamic theming. :contentReference[oaicite:26]{index=26}  
│
└── 1.6 Limitations & Trade-offs — constraints, dropped legacy, and design decisions to consider
    ├── Dropped legacy browser support (IE10 / IE11 and older) — modern — may break compatibility for legacy-heavy projects. :contentReference[oaicite:27]{index=27}  
    ├── Class-heavy / markup-intensive HTML — using many utility classes, modifiers, and components can lead to verbose HTML structure.  
    ├── Bundle overhead if only a few components used — including full Bootstrap (CSS + JS) may be overkill for minimalistic projects.  
    ├── Custom theming requires build toolchain — to use Sass / variable override / custom builds, you need build tools (Sass compiler, autoprefixer, bundler) rather than simple CDN link.  
    ├── Migration cost — upgrading from older versions (v3/v4) requires handling dropped features, changed naming, reworked components & utilities. :contentReference[oaicite:28]{index=28}  
    └── Opinionated design choices — Bootstrap’s styling decisions (grid, default spacing, typography scale, component behavior) may limit full custom styling freedom; customizing deeply may conflict with defaults.  
```