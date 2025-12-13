# v0 Prompt: WitchcraftForBeginners Newsletter Signup

**Instructions**: Copy everything below the line and paste directly into https://v0.dev

---

Create an inline newsletter signup section with these EXACT specifications:

## DESIGN SYSTEM TOKENS
- Background: #1A1A1A (surface - slightly elevated from page)
- Border: #333333 (default), #C9A962 (focus)
- Primary: #4A1C6F (deep purple)
- Secondary: #C9A962 (gold)
- Text: #E8E8E8 (light)
- Text Muted: #A0A0A0
- Input Background: #0D0D0D (darker than section)

## TYPOGRAPHY
- Headline: Cinzel, 2rem, gold color (#C9A962)
- Description: Lora, 1rem, text-muted, line-height: 1.75
- Button: Inter, 0.875rem, uppercase, letter-spacing: 0.1em
- Privacy text: Inter, 0.75rem, text-muted

## SECTION LAYOUT
- Full-width section
- Max-content width: 600px, centered
- Padding: 5rem vertical, 2rem horizontal
- Background: #1A1A1A
- Optional: subtle border top and bottom (1px #333333)

## CONTENT STRUCTURE (top to bottom)
1. Small decorative icon (moon phases or triple moon) - gold, 48px
2. Gap: 1.5rem
3. Headline (Cinzel, gold, centered)
4. Gap: 1rem
5. Description (Lora, centered, max-width 500px)
6. Gap: 2rem
7. Form row (input + button)
8. Gap: 1rem
9. Privacy note (tiny, centered)

## FORM STRUCTURE
Desktop: Email input and button on same row
- Input takes 70% width
- Button takes 30% width
- Gap: 0 (connected)

Mobile: Stack vertically
- Input full width
- Button full width
- Gap: 1rem between them

## INPUT FIELD STYLE
- Background: #0D0D0D
- Border: 2px solid #333333
- Text color: #E8E8E8
- Placeholder: #666666
- Padding: 1rem 1.25rem
- Font: Lora, 1rem
- Border-radius-left: 0.25rem (desktop) or all corners (mobile)
- Border-radius-right: 0 (desktop) or all corners (mobile)

Input Focus State:
- Border color: #C9A962 (gold)
- Box-shadow: 0 0 0 3px rgba(201, 169, 98, 0.15)
- Outline: none

## BUTTON STYLE
Default:
- Background: transparent
- Border: 2px solid #C9A962
- Text: #C9A962
- Padding: 1rem 2rem
- Border-radius-left: 0 (desktop) or all corners (mobile)
- Border-radius-right: 0.25rem (desktop) or all corners (mobile)
- Cursor: pointer

Hover:
- Background: #C9A962
- Text: #0D0D0D
- Transition: all 300ms ease

Loading State:
- Show spinner icon (replace text)
- Disable button
- Opacity: 0.7

## DECORATIVE ICON
- Triple moon symbol (waxing crescent, full, waning crescent) OR simple crescent moon
- Color: #C9A962
- Size: 48px width
- Can be SVG or use Lucide icons creatively

## SUCCESS STATE
When form submits successfully, replace form with:
- Checkmark icon (gold, 48px)
- "Welcome to the circle" headline (Cinzel, gold)
- "Check your inbox for your first moon guide" description
- Fade in animation

## ERROR STATE
- Red border on input: #A34545
- Error message below input (Inter, 0.875rem, #A34545)
- "Please enter a valid email address"

## COPY TO USE
- Headline: "Join the Circle"
- Description: "Receive moon phase guides, spell crafting wisdom, and exclusive rituals directly to your inbox. New and full moon insights await."
- Placeholder: "Enter your email address"
- Button: "Subscribe"
- Privacy: "We honor your privacy. Your email stays sacred. Unsubscribe anytime."
- Success headline: "Welcome to the Circle"
- Success description: "Check your inbox for your first moon guide. Blessed be."

## BACKGROUND EFFECT (Optional)
- Very subtle radial gradient behind the section
- Center: rgba(74, 28, 111, 0.08)
- Edge: transparent
- This creates a slight mystical glow effect

## MUST INCLUDE
- Focus states with gold glow effect
- Loading state with spinner
- Success state transformation
- Error state handling
- ARIA labels for accessibility
- Form validation (email format)
- Placeholder text
- Privacy note

## MUST NOT INCLUDE
- Name field (email only for simplicity)
- Multiple form fields
- Checkboxes or consent toggles
- Heavy decoration
- Social login options
- Excessive animation

## ANIMATIONS
- Section fade-in when entering viewport
- Button hover transitions (300ms)
- Success state: fade out form, fade in success (400ms each)
- Input focus: smooth border/shadow transition (200ms)

## OUTPUT REQUIREMENTS
- React functional component with Tailwind CSS
- Include form state management (useState)
- Include form validation
- Include loading/success/error states
- Lucide icons (Check, Loader2, Moon icons)
- Fully responsive
- Export as default

Create this newsletter signup section now.
