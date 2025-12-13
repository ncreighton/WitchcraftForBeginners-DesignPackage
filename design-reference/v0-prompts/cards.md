# v0 Prompt: WitchcraftForBeginners Article Cards

**Instructions**: Copy everything below the line and paste directly into https://v0.dev

---

Create a 3-column article card grid with these EXACT specifications:

## DESIGN SYSTEM TOKENS
- Section Background: #0D0D0D (near-black)
- Card Background: #1A1A1A (surface)
- Card Border: #333333 (default), #4A1C6F (hover)
- Primary: #4A1C6F (deep purple)
- Secondary: #C9A962 (gold)
- Text: #E8E8E8 (light)
- Text Muted: #A0A0A0

## TYPOGRAPHY
- Section Title: Cinzel, 2.5rem, gold color, centered
- Card Title: Cinzel, 1.25rem, text color #E8E8E8
- Card Excerpt: Lora, 0.95rem, text-muted #A0A0A0, line-height: 1.7
- Category Badge: Inter, 0.7rem, uppercase, letter-spacing: 0.08em
- Meta: Inter, 0.75rem, text-muted

## SECTION LAYOUT
- Full-width section with max-width container: 1200px
- Padding: 6rem vertical (clamp for responsive)
- Section title at top, centered
- Subtle gold line below title (80px wide, 1px, centered)
- 3rem gap between title and cards

## CARD GRID
- 3 columns on desktop (min 1200px)
- 2 columns on tablet (768px-1199px)
- 1 column on mobile (below 768px)
- Gap: 2rem between cards

## INDIVIDUAL CARD STRUCTURE
```
┌─────────────────────────┐
│ IMAGE (16:9 ratio)      │
│ with gradient overlay   │
├─────────────────────────┤
│ [Category Badge]        │
│ Title (2 lines max)     │
│ Excerpt (3 lines max)   │
│ ─────────────────────── │
│ 📅 Date • ⏱ 5 min read │
└─────────────────────────┘
```

## CARD SPECIFICATIONS
- Border-radius: 0.5rem
- Border: 1px solid #333333
- Background: #1A1A1A
- Padding (content area): 1.5rem
- Image height: fixed aspect ratio 16:9

## IMAGE AREA
- 16:9 aspect ratio
- Border-radius top corners only
- Gradient overlay at bottom: transparent to rgba(26, 26, 26, 0.9)
- Placeholder: deep purple gradient (#2D1149 to #1A1A1A)
- On hover: subtle zoom (scale 1.05) with overflow hidden

## CATEGORY BADGE
- Position: inside content area, above title
- Background: rgba(74, 28, 111, 0.3)
- Border: 1px solid #4A1C6F
- Text: #C9A962 (gold)
- Padding: 0.25rem 0.75rem
- Font: Inter, 0.7rem, uppercase
- Border-radius: 0.25rem
- Small moon icon before text (optional)

## CARD HOVER STATE
- Transform: translateY(-6px)
- Border color: #4A1C6F (purple)
- Box-shadow: 0 10px 30px rgba(74, 28, 111, 0.2)
- Image zoom: scale(1.05)
- Transition: all 300ms ease-out

## TEXT TRUNCATION
- Title: 2 lines max, ellipsis
- Excerpt: 3 lines max, ellipsis (line-clamp-3)

## META ROW
- Border-top: 1px solid #333333
- Padding-top: 1rem
- Margin-top: 1rem
- Flex row with space-between or justify-start with gap
- Icons: Calendar and Clock (from Lucide)
- Text: #A0A0A0

## SAMPLE CONTENT (Create 3 Cards)

Card 1:
- Category: Moon Wisdom
- Title: "Understanding the Full Moon's Influence on Your Practice"
- Excerpt: "Discover how lunar cycles affect energy work, spellcasting, and spiritual development. Learn to align your practice with the moon's natural rhythms."
- Date: December 8, 2024
- Read time: 8 min

Card 2:
- Category: Beginner Basics
- Title: "Setting Up Your First Altar: A Complete Guide"
- Excerpt: "Create a sacred space that honors your path. From choosing the right location to selecting meaningful objects, learn altar fundamentals."
- Date: December 5, 2024
- Read time: 12 min

Card 3:
- Category: Spellwork
- Title: "Protection Spells for the Modern Witch"
- Excerpt: "Shield yourself and your space with these accessible protection techniques. Perfect for beginners building their magical toolkit."
- Date: December 1, 2024
- Read time: 6 min

## ANIMATIONS
- Cards fade-in + translateY(30px) on viewport enter
- Staggered delays: card 1 = 0ms, card 2 = 100ms, card 3 = 200ms
- Duration: 500ms ease-out

## MUST INCLUDE
- Section title with decorative underline
- Proper line clamping for titles and excerpts
- Category badges with icons
- Hover lift effect with purple glow
- Meta row with icons
- Viewport entrance animation (use Intersection Observer or Framer Motion)

## MUST NOT INCLUDE
- Author avatars (keep cards clean)
- Social share buttons
- Heavy shadows
- Centered card text (keep left-aligned)
- Sans-serif fonts for title/excerpt
- "Read More" links (whole card is clickable)

## OUTPUT REQUIREMENTS
- React functional component with Tailwind CSS
- Include Lucide icons (Moon, Calendar, Clock)
- Include viewport animation logic
- Fully responsive grid
- Export as default

Create this article cards section now.
