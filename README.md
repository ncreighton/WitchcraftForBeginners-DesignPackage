# WitchcraftForBeginners Design Package

Complete design package for WitchcraftForBeginners.com - tokens, v0 prompts, CLAUDE.md.

## What's Included

```
├── CLAUDE.md                     # Full project configuration
├── design-reference/
│   ├── tokens/
│   │   ├── variables.css         # CSS custom properties
│   │   └── tailwind.config.js    # Tailwind config
│   ├── v0-prompts/               # READY TO PASTE into v0.dev
│   │   ├── hero.md
│   │   ├── navigation.md
│   │   ├── cards.md
│   │   ├── footer.md
│   │   └── newsletter.md
│   └── v0-components/            # Save v0 exports here
```

## Quick Start

1. Open a v0 prompt file (e.g., `design-reference/v0-prompts/hero.md`)
2. Copy everything below the `---` line
3. Paste into https://v0.dev
4. Generate → iterate → export code
5. Save to `design-reference/v0-components/Hero.tsx`
6. Tell Claude Code: "Implement hero from v0 reference"

## Brand Specifications

| Element | Value |
|---------|-------|
| Primary | #4A1C6F (deep purple) |
| Secondary | #C9A962 (gold) |
| Background | #0D0D0D (near-black) |
| Display Font | Cinzel |
| Body Font | Lora |
| Voice | Mystical warmth, accessible wisdom |

## Components Ready

- ✅ Hero (full viewport, left-aligned, staggered animations)
- ✅ Navigation (transparent → solid scroll)
- ✅ Article Cards (3-column grid, hover effects)
- ✅ Newsletter (triple moon, "Join the Circle")
- ✅ Footer (4-column, gold accents)

## Anti-Patterns (embedded in all prompts)

- NO Halloween imagery
- NO centered layouts
- NO sans-serif fonts
- NO "Learn More" CTAs
- NO bright saturated colors

---

*Part of the [visual-to-code-pipeline](https://github.com/ncreighton/visual-to-code-pipeline) system*
