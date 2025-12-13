# v0 Prompt: WitchcraftForBeginners Hero Section

**Instructions**: Copy everything below the line and paste directly into https://v0.dev

---

Create a full-viewport hero section with these EXACT specifications:

## DESIGN SYSTEM TOKENS
- Background: #0D0D0D (near-black)
- Primary: #4A1C6F (deep purple)
- Secondary: #C9A962 (gold - use for accents)
- Accent: #1E3A5F (midnight blue)
- Text: #E8E8E8 (light gray)
- Text muted: #A0A0A0
- Surface: #1A1A1A (dark gray - for cards/elevated elements)

## TYPOGRAPHY
- Display font: Cinzel (Google Fonts - serif, mystical) - for headlines
- Body font: Lora (Google Fonts - elegant serif) - for body text
- Headline: 4.2rem (clamp to be responsive), color #C9A962 (gold), letter-spacing: 0.02em, line-height: 1.1
- Subhead: 1.25rem, color #A0A0A0, line-height: 1.8, max-width: 500px
- Button text: Inter or system font, 0.875rem, uppercase, letter-spacing: 0.1em

## COMPONENT SPECIFICATIONS
- Full viewport height (100vh)
- Content positioned LEFT (not centered) - about 10% from left edge
- Max content width: 550px
- Content vertical centering with flex
- Subtle radial gradient overlay from center: rgba(74, 28, 111, 0.12) fading to transparent at 70%
- No background image - pure color with gradient overlay

## CONTENT STRUCTURE (top to bottom)
1. Small moon phase icon (crescent moon, gold color, 32px)
2. Gap: 1.5rem
3. Main headline (Cinzel, gold)
4. Gap: 1.5rem  
5. Subheadline (Lora, muted)
6. Gap: 2.5rem
7. Two buttons side by side (gap: 1rem)
8. Scroll indicator at very bottom center (subtle, animated)

## BUTTON STYLES
Primary CTA:
- Transparent background
- 2px solid gold border (#C9A962)
- Gold text
- Padding: 1rem 2.5rem
- On hover: gold background (#C9A962), dark text (#0D0D0D)
- Transition: 300ms ease

Secondary CTA:
- No border, no background
- Gold text with subtle underline
- On hover: underline opacity increases

## STYLE & ATMOSPHERE
- Candlelit study atmosphere - warm but mysterious
- Content emerges from darkness feeling
- Premium, mystical, wise (NOT Halloween, NOT spooky)
- Subtle text-shadow glow on headline: 0 0 30px rgba(201, 169, 98, 0.3)

## ANIMATIONS
- Headline: fade-in + translateY from 20px, 1s duration, ease-out, delay 0.2s
- Subhead: same animation, delay 0.4s  
- Buttons: same animation, delay 0.6s
- Scroll indicator: subtle bounce animation (translateY 5px), infinite, 2s

## SCROLL INDICATOR
- Position: absolute bottom center
- Chevron down icon or simple line with dot
- Color: #A0A0A0 (muted)
- Animated bounce

## MUST INCLUDE
- Moon icon above headline (use Lucide React moon icon, or SVG crescent)
- Text glow effect on headline
- Staggered entrance animations
- Scroll indicator with bounce
- Proper Google Font imports (Cinzel and Lora)
- Responsive: on mobile, padding should be 2rem, font sizes should scale down

## MUST NOT INCLUDE (CRITICAL ANTI-PATTERNS)
- Centered text alignment (keep left-aligned)
- Sans-serif fonts anywhere
- Purple-to-blue gradients
- Halloween imagery (no skulls, pumpkins, bats)
- Stock photo backgrounds
- "Learn More" or "Get Started" as button text
- Heavy shadows or 3D effects
- Glitter or sparkle animations
- Multiple colors competing (keep it gold + muted)
- Pentagram symbols

## EXACT COPY TO USE
- Headline: "Where Ancient Wisdom Meets Modern Seekers"
- Subhead: "Your trusted guide into authentic witchcraft practice. Learn the craft with respect, wisdom, and grounded intention."
- Primary CTA: "Begin Your Journey"
- Secondary CTA: "Explore the Grimoire"

## OUTPUT REQUIREMENTS
- React functional component with Tailwind CSS
- Include Google Fonts import at top of component
- Make fully responsive (mobile-first)
- Export as default
- Component should be self-contained (no external dependencies except icons)
- Use Lucide React for the moon icon if available

Create this component now.
