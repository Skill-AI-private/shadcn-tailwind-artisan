<div align="center">

# shadcn & Tailwind Artisan (`shadcn-tailwind-artisan`)

**Production shadcn/ui Component Registries, Tailwind CSS v4 & Radix Accessibility**  
*The Scalable UI Component Engineering Standard for AI Coding Agents.*

[![Version](https://img.shields.io/badge/version-1.0.0-18181B.svg?style=flat-square&labelColor=09090B)](https://github.com/Skill-AI-private/shadcn-tailwind-artisan)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-Supported-18181B.svg?style=flat-square&labelColor=09090B)](https://ui.shadcn.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-v4%20Theme%20Tokens-18181B.svg?style=flat-square&labelColor=09090B)](https://tailwindcss.com)
[![Harnesses](https://img.shields.io/badge/compatibility-Antigravity%20|%20Claude%20Code%20|%20Cursor%20|%20Copilot-18181B.svg?style=flat-square&labelColor=09090B)](https://github.com/Skill-AI-private/shadcn-tailwind-artisan)
[![License](https://img.shields.io/badge/license-MIT-18181B.svg?style=flat-square&labelColor=09090B)](LICENSE)

<br/>

```text
==========================================================================================
                   SHADCN & TAILWIND ARTISAN ARCHITECTURE MATRIX
==========================================================================================

  [01] OFFICIAL REGISTRY COMPONENT SCAFFOLDING
       +-- Automated CLI integration via `npx shadcn@latest add <component>`
       +-- Zero reinventing the wheel for Dialogs, Sheets, Popovers, and Data Tables
       +-- Standardized component directory structures under `@/components/ui/`

  [02] TAILWIND CSS V4 SEMANTIC TOKEN ARCHITECTURE
       +-- Modern CSS theme tokens via `@theme` directives and CSS custom properties
       +-- Built-in light/dark theme persistence across surface, border, and text tokens
       +-- Strict mobile-first responsive scaling across standard breakpoints

  [03] WAI-ARIA ACCESSIBILITY & FOCUS MANAGEMENT
       +-- 100% keyboard accessibility: full Tab navigation, Esc dismissal, Arrow menus
       +-- Accessible icon button naming via explicit `aria-label` attributes
       +-- Focus visible rings enforced (no silent `outline-none` accessibility bugs)
==========================================================================================
```

</div>

---

## Technical Specifications

`shadcn-tailwind-artisan` guides coding assistants away from brittle custom CSS and arbitrary inline styles. It enforces the use of headless Radix primitives wrapped in clean Tailwind v4 utility tokens.

### Core Disciplines

* **Registry First:** Prohibits raw, hand-rolled implementations of common UI primitives. Always prefers the official `shadcn/ui` registry.
* **Token Consistency:** Ensures all custom styling references global semantic tokens (`bg-background`, `text-foreground`, `border-border`) rather than hardcoded hex values.
* **Accessibility Parity:** Guarantees that all modals, menus, and form controls strictly comply with WAI-ARIA standards and keyboard navigation semantics.

---

## Installation

### Windows (PowerShell)
```powershell
git clone https://github.com/Skill-AI-private/shadcn-tailwind-artisan.git "$HOME\.gemini\config\skills\shadcn-tailwind-artisan"
```

### macOS & Linux (Bash)
```bash
git clone https://github.com/Skill-AI-private/shadcn-tailwind-artisan.git ~/.gemini/config/skills/shadcn-tailwind-artisan
```

---

## Directory Structure

```text
shadcn-tailwind-artisan/
|-- SKILL.md                                           # Core Component Engineering Rules
|-- README.md                                          # Technical specification
`-- references/                                        # Progressive disclosure playbooks
    |-- 01-shadcn-cli-and-component-catalog.md        # CLI commands & form handling
    |-- 02-tailwind-v4-and-responsive-patterns.md      # Theme tokens & responsive layouts
    `-- 03-radix-primitives-and-accessibility.md       # WAI-ARIA standards & keyboard navigation
```

---

<div align="center">

*Engineered for autonomous software agents within the Skill-AI-private suite.*

</div>
