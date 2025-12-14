
> [!quote] **Lord Krishna** (Spiritual Teacher, Mathura, c. 3228 BCE)  
> **Teaching Arjuna balance amidst duality — light and dark, joy and sorrow**
> 
> > समदुःखसुखं धीरं सोऽमृतत्वाय कल्पते ॥
> 
> **“The one who stays balanced in joy and sorrow is fit for true mastery.”**  
> _Bhagavad Gita — Chapter 2, Verse 15_

# **How to Approach : Dark Mode & Theme Switching via CSS Variables**

> **Senior Developer Guidance:**  
> Dark mode is not just a color inversion — it’s a **contrast, readability, and context strategy**. Design themes as **tokenized systems** (CSS variables) rather than hard-coded colors. Switch themes by toggling variable scopes, not rewriting styles. This keeps design systems maintainable, scalable, and framework-agnostic.

Dark mode and theme switching in modern UI engineering should be built on **CSS custom properties (variables)** for colors, borders, backgrounds, and surface tokens. By defining semantic tokens (e.g., `--bs-body-bg`, `--bs-body-color`, `--bs-surface`, `--bs-accent`), you can flip themes by toggling a root class (like `.theme-dark`) or `data-theme` attribute without touching component markup.

Integrated with Bootstrap’s existing variable system, this approach allows you to layer project-specific design tokens on top of Bootstrap, enabling per-user preferences, OS-level media queries (`prefers-color-scheme`), and role- or brand-based theme variants.

### **Topics Overview**

|Topic|Brief Description|
|---|---|
|**Design Tokens & CSS Variables**|Defining semantic color/background tokens for themes|
|**Light vs Dark Theme Foundations**|Contrast ratios, surface hierarchy, elevation, readability|
|**Theme Scope & Toggle Mechanisms**|`:root`, `.theme-dark`, `[data-theme]` switching strategies|
|**Bootstrap Variable Integration**|Mapping project tokens to Bootstrap CSS variables|
|**Prefers-Color-Scheme & User Preference**|Respecting OS-level dark mode and storing user choices|
|**Component-Safe Theming**|Ensuring buttons, cards, navbars, forms adapt without custom rewrites|
|**Transition & Motion Considerations**|Optional smooth transitions on theme change (opacity, color)|
|**Real-World Patterns**|App dashboards, code viewers, documentation, multi-brand SaaS theming|

---
