# v0 Prompt: WitchcraftForBeginners Navigation

**Instructions**: Copy everything below the line and paste directly into https://v0.dev

---

Create a transparent navigation header with these EXACT specifications:

## DESIGN SYSTEM TOKENS
- Background default: transparent (rgba(0, 0, 0, 0))
- Background scrolled: rgba(13, 13, 13, 0.95) with backdrop-blur: 12px
- Text: #E8E8E8 (light gray)
- Text hover: #C9A962 (gold)
- Accent/Active: #C9A962 (gold)
- Border: rgba(201, 169, 98, 0.2) (subtle gold)

## TYPOGRAPHY
- Logo: Cinzel, 1.5rem, letter-spacing: 0.05em, color #C9A962
- Nav links: Lora, 0.875rem, letter-spacing: 0.03em, text-transform: none

## COMPONENT SPECIFICATIONS
- Fixed position at top
- Full width
- Height: 80px
- Z-index: 100
- Padding: 0 5% (matches hero content area)

## LAYOUT STRUCTURE
Left: Logo/brand name
Center-Right: Navigation links (6 items max)
Right: CTA button

## NAV ITEMS (Use These)
1. The Craft
2. Spells & Rituals  
3. Moon Wisdom
4. The Grimoire
5. About
[CTA] Join the Circle

## LOGO
- Text-based: "Witchcraft for Beginners" or abbreviated "WFB" with decorative element
- Cinzel font, gold color
- Small moon icon beside it (optional)

## SCROLL BEHAVIOR
On scroll past 50px:
- Add background: rgba(13, 13, 13, 0.95)
- Add backdrop-filter: blur(12px)
- Add subtle border-bottom: 1px solid rgba(201, 169, 98, 0.1)
- Transition: all 300ms ease

## LINK HOVER EFFECT
- Color transition to gold (#C9A962)
- Animated underline that scales from center (scaleX 0 to 1)
- Underline: 1px solid gold, positioned 2px below text

## CTA BUTTON STYLE
- Ghost style (transparent bg)
- 1px gold border
- Gold text
- Padding: 0.5rem 1.25rem
- Border-radius: 0
- Hover: gold background, dark text

## MOBILE MENU (below 768px)
- Hamburger icon (three lines, gold)
- Slide-in menu from right
- Full-height overlay (rgba(13, 13, 13, 0.98))
- Links stacked vertically, centered
- Links larger on mobile: 1.25rem
- Close button (X icon) in top right
- Transition: 400ms ease

## MUST INCLUDE
- Scroll detection with useState/useEffect
- Smooth transitions between transparent and solid states
- Animated underline on hover (scale from center)
- Mobile hamburger menu with slide-in
- Proper focus states for accessibility
- ARIA labels

## MUST NOT INCLUDE
- Heavy drop shadows
- Multiple CTA buttons
- Dropdown menus (keep navigation flat)
- Sans-serif fonts
- Centered logo (keep left)
- Background image or patterns

## ANIMATIONS
- Link hover underline: scaleX from 0 to 1, 200ms ease
- Mobile menu slide: translateX from 100% to 0, 400ms ease
- Scroll state change: 300ms ease transition

## OUTPUT REQUIREMENTS
- React functional component with Tailwind CSS
- Include scroll detection logic
- Include mobile menu state management
- Import Lucide icons for hamburger/close (Menu, X)
- Fully responsive
- Export as default

Create this navigation component now.
