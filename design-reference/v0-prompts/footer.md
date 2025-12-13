# v0 Prompt: WitchcraftForBeginners Footer

**Instructions**: Copy everything below the line and paste directly into https://v0.dev

---

Create a multi-column footer with these EXACT specifications:

## DESIGN SYSTEM TOKENS
- Background: #0D0D0D (matches page background)
- Surface: #1A1A1A (if using cards or elevated elements)
- Accent Border: #C9A962 (gold) - thin line at top
- Text Default: #A0A0A0 (muted)
- Text Hover: #E8E8E8 (bright)
- Accent: #C9A962 (gold)
- Border: #333333

## TYPOGRAPHY
- Logo/Brand: Cinzel, 1.25rem, gold
- Column Headers: Cinzel, 0.875rem, uppercase, gold, letter-spacing: 0.08em
- Links: Lora, 0.9rem, text-muted
- Copyright: Inter, 0.75rem, text-muted
- Description: Lora, 0.875rem, text-muted, line-height: 1.7

## SECTION LAYOUT
- Full-width
- Top border: 1px solid #C9A962 (gold accent line)
- Max-content width: 1200px centered
- Padding: 4rem vertical, 2rem horizontal

## STRUCTURE

```
┌─────────────────────────────────────────────────────────────┐
│ ═══════════════ GOLD LINE ════════════════════════════════ │
├─────────────────┬───────────────┬───────────────┬──────────┤
│ BRAND/ABOUT     │ EXPLORE       │ RESOURCES     │ CONNECT  │
│                 │               │               │          │
│ Logo            │ Link          │ Link          │ Socials  │
│ Description     │ Link          │ Link          │ Contact  │
│ (2-3 lines)     │ Link          │ Link          │          │
│                 │ Link          │ Link          │          │
│ Social Icons    │ Link          │ Link          │          │
├─────────────────┴───────────────┴───────────────┴──────────┤
│ © 2024 WitchcraftForBeginners.com │ Privacy │ Terms │ Site │
└─────────────────────────────────────────────────────────────┘
```

## COLUMN 1: BRAND (40% width)
- Logo text: "Witchcraft for Beginners" (Cinzel, gold)
- Description: 2-3 sentences about the site
- Gap: 1.5rem
- Social icons row (Instagram, Pinterest, Email)

## COLUMN 2: EXPLORE (20% width)
- Header: "EXPLORE" (Cinzel, gold, uppercase)
- Links:
  - The Craft
  - Spells & Rituals
  - Moon Wisdom
  - Beginner Guides
  - The Grimoire

## COLUMN 3: RESOURCES (20% width)
- Header: "RESOURCES" (Cincel, gold, uppercase)
- Links:
  - Free Downloads
  - Moon Calendar
  - Herb Guide
  - Crystal Directory
  - Book Recommendations

## COLUMN 4: CONNECT (20% width)
- Header: "STAY CONNECTED" (Cinzel, gold, uppercase)
- Mini newsletter or "Join our circle" text link
- Contact link
- About link

## SOCIAL ICONS
- Size: 24px
- Color default: #A0A0A0
- Color hover: #C9A962 (gold)
- Icons: Instagram, Pinterest, Mail (use Lucide)
- Gap: 1rem between icons

## LINK STYLES
Default:
- Color: #A0A0A0
- Text-decoration: none

Hover:
- Color: #E8E8E8
- Optional: subtle underline animation
- Transition: 200ms ease

## BOTTOM BAR
- Border-top: 1px solid #333333
- Margin-top: 3rem
- Padding-top: 2rem
- Flex row, space-between
- Left: Copyright text
- Right: Legal links (Privacy Policy • Terms • Sitemap)

## COPYRIGHT TEXT
"© 2024 WitchcraftForBeginners.com. All rights reserved. Blessed be."

## RESPONSIVE BEHAVIOR
Desktop (1200px+): 4 columns as shown
Tablet (768px-1199px): 2x2 grid
Mobile (below 768px): Stack vertically, centered text

## MUST INCLUDE
- Gold accent line at top
- Logo with brand description
- Social media icons with hover states
- Copyright year
- Legal links
- Proper column structure
- Responsive grid

## MUST NOT INCLUDE
- Heavy graphics or illustrations
- Multiple CTAs
- Newsletter form (keep it in dedicated section)
- Excessive links per column
- Bright colors competing
- Sans-serif fonts for headers

## ANIMATIONS
- Link hover color transition (200ms)
- Social icon hover scale (1.1) + color change
- Optional: fade-in when footer enters viewport

## ACCESSIBILITY
- All links have proper focus states
- Social icons have aria-labels
- Sufficient color contrast
- Keyboard navigable

## OUTPUT REQUIREMENTS
- React functional component with Tailwind CSS
- Lucide icons (Instagram, Pinterest, Mail)
- Responsive grid layout
- Proper semantic HTML (footer, nav elements)
- Export as default

Create this footer component now.
