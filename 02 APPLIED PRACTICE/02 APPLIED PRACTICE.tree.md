```ruby
├── 2.1 Code Examples — practical usage from basic to advanced
│   ├── 2.1.1 Basic Examples — essential installations & components
│   │     ├── Grid & layout basics — container → row → col
│   │     ├── Buttons & utilities — color / size / spacing
│   │     ├── Typography & spacing utilities
│   │     ├── Navbar starter template
│   │     └── Responsive images & ratios (.img-fluid / .ratio)
│   │
│   ├── 2.1.2 Intermediate Examples — feature & behavior wiring
│   │     ├── Modal & collapse workflows
│   │     ├── Accordion (FAQ pattern)
│   │     ├── Offcanvas sidebar navigation
│   │     ├── Toast notifications
│   │     └── Cards + responsive grid layouts
│   │
│   └── 2.1.3 Advanced Examples — production-grade architecture
│         ├── Multi-level navbar & offcanvas hybrid
│         ├── Dark mode + theme switching via CSS variables
│         ├── Role-based layout for dashboards/CRM
│         ├── Accessibility-first implementation (WCAG AA)
│         └── Bootstrap + SPA frameworks (React, Vue, Angular)
│
├── 2.2 Hands-on Mini Projects — build-to-learn applications
│   ├── 2.2.1 Beginner Project — responsive landing page / portfolio
│   ├── 2.2.2 Intermediate Project — dashboard + charts + offcanvas
│   └── 2.2.3 Production Project — multi-theme authenticated interface
│
├── 2.3 Patterns & Workflows — engineering and design structure
│   ├── 2.3.1 Design Patterns — reusable UI logic
│   │     ├── Containerized layout hierarchy
│   │     ├── Utility-first enhancement before custom CSS
│   │     ├── Component composition
│   │     ├── Theming & variable-driven design
│   │     └── Progressive enhancement (HTML → CSS → JS)
│   │
│   ├── 2.3.2 Common Workflows — end-to-end sequences
│   │     ├── CDN → prototype → npm build pipeline upgrade
│   │     ├── Sass variable override workflow
│   │     └── Performance optimization & deploy workflow
│   │
│   └── 2.3.3 Anti-patterns — what to avoid
│         ├── Excessive nested containers
│         ├── Overuse of !important in CSS
│         ├── Using custom JS when native plugins exist
│         ├── Hard-coding breakpoints incorrectly
│         └── Importing full bundle when only 1–2 components needed
│
├── 2.4 Tools, Tips & Debugging Notes
│   ├── Browser DevTools debugging workflow
│   ├── JS plugin debugging with data-bs-* validation
│   ├── Accessibility testing (Lighthouse / aria roles)
│   └── Build troubleshooting (Sass, autoprefixer, imports)
│
├── 2.5 Real-World Use Cases — domain applications
│   ├── 2.5.1 Industry Use — dashboards / ecommerce / admin UIs
│   ├── 2.5.2 Business Systems — CRMs / SaaS / marketing pages
│   └── 2.5.3 System Integrations — frameworks & backends
│         ├── Bootstrap + React (React-Bootstrap)
│         ├── Bootstrap + Angular (ng-bootstrap)
│         ├── Bootstrap + Vue (bootstrap-vue-next)
│         ├── Bootstrap + Laravel / Django
│         └── Bootstrap + WordPress themes / Elementor / Oxygen
│
├── 2.6 Migration & Version Management — v4 → v5 → v5.4+ transition
│   ├── jQuery removal impact
│   ├── Popper v2 migration
│   ├── Forms & validation rewrite
│   ├── Deprecated utilities & replacements
│   └── Migration workflow & tools
│
├── 2.7 Icons Integration — modern visual systems
│   ├── Bootstrap Icons overview
│   ├── SVG sprite usage vs <i> icon fonts
│   ├── Tree-shaking icons with npm + Sass
│   └── Alternatives — FontAwesome / Heroicons / Feather
│
├── 2.8 Responsive Breakpoint Mastery — advanced responsiveness
│   ├── breakpoint utilities (col-md-*, d-lg-block, order-*)
│   ├── mobile-first grid workflows
│   ├── responsive anti-patterns & fixes
│   └── adaptive layout case studies
│
├── 2.9 Forms — advanced input & validation systems
│   ├── Floating labels
│   ├── Input groups + addon components
│   ├── Custom checkboxes, radios, switches & file uploads
│   ├── Native HTML5 + Bootstrap validation styles
│   └── integration with validator.js / custom JS validation
│
├── 2.10 Advanced Components & UI Behavior
│   ├── Carousel — touch swipe, captions, lazy loading
│   ├── Scrollspy + smooth scroll
│   ├── Tooltip & Popover advanced config
│   └── Offcanvas navigation design patterns
│
├── 2.11 Performance Optimization & Bundle Size Control
│   ├── PurgeCSS / LightningCSS / CSS minification
│   ├── Selectively importing JS plugins only
│   ├── bootstrap.bundle.min.js vs modular imports
│   ├── Optimize fonts & icon loads
│   └── Lighthouse / Core Web Vitals strategy
│
├── 2.12 Testing Bootstrap UIs
│   ├── Visual regression testing (Percy / Chromatic / Argos)
│   ├── Cypress / Playwright interaction tests
│   └── Testing JS plugin states & accessibility roles
│
└── 2.13 RTL & Internationalization
    ├── rtlcss build workflow
    ├── flipping layout logic
    └── spacing / alignment pitfalls (margin-left vs margin-end)
```