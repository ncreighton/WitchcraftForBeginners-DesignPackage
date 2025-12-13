# CLAUDE.md - WitchcraftForBeginners.com Project

## Project Overview

**Site**: WitchcraftForBeginners.com
**Type**: Authority / Spiritual Education
**Status**: FLAGSHIP - Highest Priority
**Theme**: Blocksy (with custom child theme)

---

## Brand Identity

### Voice & Persona
A wise, experienced witch who remembers what it was like to be a beginner. Welcoming but respectful of the craft's depth. Mystical warmth with accessible wisdom and grounded practice.

### Tone Attributes
- Warm and inviting, never condescending
- Mystical but grounded (NOT fluffy or Hollywood)
- Respectful of diverse traditions
- Ethical emphasis without preaching
- Beginner-friendly without dumbing down

### CTA Language
Use these, NOT "Learn More":
- "Begin Your Journey"
- "Discover the Magic"
- "Unlock Ancient Wisdom"
- "Join the Circle"
- "Explore the Grimoire"

---

## Design System

### Design Tokens Location

| Format | Path | Purpose |
|--------|------|---------|
| CSS | `./design-reference/tokens/variables.css` | WordPress/child theme |
| Tailwind | `./design-reference/tokens/tailwind.config.js` | v0/React components |

### Color Palette

```css
/* PRIMARY - Deep Purple (wisdom, mystery) */
--color-primary: #4A1C6F;
--color-primary-light: #6B3FA0;
--color-primary-dark: #2D1149;

/* SECONDARY - Gold (sacred, magical) */
--color-secondary: #C9A962;
--color-secondary-light: #E5D4A1;
--color-secondary-dark: #9A7B3D;

/* ACCENT - Midnight Blue (depth) */
--color-accent: #1E3A5F;

/* DARK THEME NEUTRALS */
--color-background: #0D0D0D;
--color-surface: #1A1A1A;
--color-surface-elevated: #242424;
--color-text: #E8E8E8;
--color-text-muted: #A0A0A0;
--color-border: #333333;
```

### Typography

| Use | Font | Fallback |
|-----|------|----------|
| Display/Headlines | Cinzel | Cormorant Garamond, Playfair Display, serif |
| Body | Lora | Crimson Text, EB Garamond, serif |
| Accent (script) | Tangerine | Great Vibes, cursive |
| Code/Technical | JetBrains Mono | Fira Code, monospace |

**Font Scale:**
```css
--font-hero: clamp(2.5rem, 7.5vw, 5rem);
--font-4xl: clamp(2.25rem, 5vw, 4rem);
--font-3xl: clamp(1.875rem, 3.125vw, 3rem);
--font-2xl: clamp(1.5rem, 1.875vw, 2.25rem);
--font-xl: clamp(1.25rem, 1.25vw, 1.75rem);
--font-base: clamp(1rem, 0.5vw, 1.125rem);
```

---

## Visual Implementation References

### v0 Component References

Components generated via v0.dev serve as visual implementation targets.

| Component | Prompt File | Code Reference | Status |
|-----------|-------------|----------------|--------|
| Hero | `./v0-prompts/hero.md` | `./v0-components/Hero.tsx` | ⏳ Ready for v0 |
| Navigation | `./v0-prompts/navigation.md` | `./v0-components/Navigation.tsx` | ⏳ Ready for v0 |
| Cards | `./v0-prompts/cards.md` | `./v0-components/Cards.tsx` | ⏳ Ready for v0 |
| Footer | `./v0-prompts/footer.md` | `./v0-components/Footer.tsx` | ⏳ Ready for v0 |
| Newsletter | `./v0-prompts/newsletter.md` | `./v0-components/Newsletter.tsx` | ⏳ Ready for v0 |

### Implementation Protocol

1. **Go to https://v0.dev**
2. **Copy prompt** from `./v0-prompts/[component].md`
3. **Paste into v0** and generate
4. **Iterate if needed** (ask v0 for adjustments)
5. **Export code** to `./v0-components/[Component].tsx`
6. **Claude Code implements** from this reference

### Critical Rule

> **Match v0 reference components EXACTLY in visual output.**
> Adapt code for WordPress but maintain 100% visual fidelity.
> NEVER implement without v0 reference OR explicit token values.

---

## Anti-Patterns (NEVER USE)

### WitchcraftForBeginners Specific
- ❌ Halloween imagery (skulls, pumpkins, bats, orange+purple)
- ❌ Centered text layouts (always left-align or asymmetric)
- ❌ Sans-serif fonts ANYWHERE
- ❌ Bright, saturated colors
- ❌ Stock photo witches with costumes/props
- ❌ Pentagram clichés (unless contextual)
- ❌ Glitter or sparkle effects
- ❌ "Learn More" as CTA

### Universal (All Sites)
- ❌ Purple-to-blue gradients (AI hallmark)
- ❌ Roboto/Inter/Arial as primary fonts
- ❌ Generic stock photos
- ❌ Heavy drop shadows
- ❌ Template-obvious patterns

---

## Content Strategy

### Categories
```
├── Getting Started
│   ├── Beginner Basics
│   ├── Ethics & Safety
│   └── Setting Intentions
├── The Craft
│   ├── Types of Witchcraft
│   ├── Tools & Supplies
│   └── Creating Sacred Space
├── Spells & Rituals
│   ├── Protection
│   ├── Manifestation
│   ├── Cleansing
│   └── Love & Relationships
├── Moon Wisdom
│   ├── Moon Phases
│   ├── Lunar Rituals
│   └── Moon Calendar
├── The Grimoire
│   ├── Herbs & Plants
│   ├── Crystals & Stones
│   └── Symbols & Sigils
└── Seasonal
    ├── Sabbats
    └── Esbats
```

### Post Types
| Type | Purpose | Template |
|------|---------|----------|
| Guide | In-depth educational content | Long-form with TOC |
| Spell | Step-by-step magical working | Structured card format |
| Reference | Quick-lookup info (herbs, crystals) | Grid/database layout |
| Seasonal | Sabbat/Esbat celebrations | Feature with imagery |

---

## Technical Stack

### Theme
- **Base**: Blocksy Pro
- **Child Theme**: `./theme/blocksy-child/`
- **Custom CSS**: `./theme/blocksy-child/assets/css/`

### Essential Plugins
| Plugin | Purpose |
|--------|---------|
| RankMath SEO Pro | SEO (NOT Yoast) |
| LiteSpeed Cache | Performance |
| AI Engine | MCP Connection |
| WPCode | Custom snippets |
| Complianz | GDPR compliance |

---

## Quality Gates

### Before ANY Component Ships

**Visual Check:**
- [ ] Matches v0 reference exactly
- [ ] No anti-patterns present
- [ ] Left-aligned text (not centered)
- [ ] Serif fonts only (Cinzel/Lora)
- [ ] Gold accents used sparingly
- [ ] Dark theme with proper contrast
- [ ] At least one memorable element

**Functional Check:**
- [ ] All links work
- [ ] CTAs use approved language
- [ ] Animations are subtle
- [ ] Responsive on all breakpoints

**Brand Check:**
- [ ] Feels mystical but grounded
- [ ] NOT Halloween/spooky
- [ ] NOT fluffy/new-age generic
- [ ] Would a real practitioner respect this?

---

## v0 Workflow Reminder

```
1. Open prompt file: ./v0-prompts/[component].md
2. Copy everything below "---" line
3. Paste into v0.dev
4. Generate component
5. Request refinements if needed
6. Click "Code" tab
7. Copy React component
8. Save to: ./v0-components/[Component].tsx
9. Tell Claude to implement from reference
```

---

## File Structure

```
WitchcraftForBeginners-DesignPackage/
├── CLAUDE.md                     # This file
├── design-reference/
│   ├── tokens/
│   │   ├── variables.css         # CSS custom properties ✓
│   │   └── tailwind.config.js    # Tailwind config ✓
│   ├── v0-prompts/               # Ready to paste into v0.dev
│   │   ├── hero.md               ✓
│   │   ├── navigation.md         ✓
│   │   ├── cards.md              ✓
│   │   ├── footer.md             ✓
│   │   └── newsletter.md         ✓
│   └── v0-components/            # USER saves v0 exports here
│       ├── Hero.tsx              (pending)
│       ├── Navigation.tsx        (pending)
│       ├── Cards.tsx             (pending)
│       ├── Footer.tsx            (pending)
│       └── Newsletter.tsx        (pending)
├── theme/
│   └── blocksy-child/
│       └── assets/
└── docs/
```

---

## Quick Commands

### Generate New v0 Prompt
```
Generate a v0.app prompt for [NEW_COMPONENT] based on this CLAUDE.md.
Include all token values from the Design System section.
Include all anti-patterns in the MUST NOT section.
Output as markdown ready to paste into v0.dev.
```

### Implement from v0 Reference
```
Implement the [COMPONENT] in WordPress.
Reference file: ./v0-components/[Component].tsx
Use CSS custom properties from ./design-reference/tokens/variables.css
Match visual output EXACTLY.
Output as Blocksy-compatible PHP + CSS.
```

---

*Visual-to-Code Pipeline v1.0*
*Site: WitchcraftForBeginners.com*
*Generated: December 2024*
