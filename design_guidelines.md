# Carbon Coin Design Guidelines

## Design Approach
**Reference-Based Approach**: Drawing inspiration from gamification leaders like Duolingo for engagement mechanics and eco-focused platforms like Tesla's interface for sustainability aesthetics.

## Core Design Elements

### A. Color Palette
**Primary Colors:**
- Forest Green: 142 76% 36% (primary brand)
- Ocean Blue: 200 85% 45% (secondary)
- Pure White: 0 0% 100% (backgrounds)

**Supporting Colors:**
- Deep Green: 142 76% 28% (darker states)
- Light Green: 142 65% 85% (backgrounds)
- Charcoal: 210 15% 25% (text)

### B. Typography
**Primary Font**: Poppins (Google Fonts)
- Headers: 600-700 weight
- Body: 400-500 weight
- UI Elements: 500 weight

**Hierarchy:**
- Hero Title: text-4xl to text-6xl
- Section Headers: text-2xl to text-3xl
- Body Text: text-base to text-lg

### C. Layout System
**Tailwind Spacing Units**: Consistent use of 2, 4, 8, 12, 16
- Micro spacing: p-2, m-2 (8px)
- Standard spacing: p-4, m-4 (16px)
- Section spacing: p-8, m-8 (32px)
- Large gaps: gap-12, gap-16

### D. Component Library

**Navigation:**
- Sticky header with glass morphism effect
- Mobile hamburger menu with slide-in animation

**Cards:**
- Rounded corners (rounded-xl)
- Subtle shadows (shadow-lg)
- Hover lift effects (hover:shadow-xl)

**Buttons:**
- Primary: Green gradient with white text
- Secondary: Outline style with green border
- CTA buttons: Larger padding (px-8 py-4)

**Forms:**
- Clean input fields with focus states
- Green accent borders on focus
- Validation messaging in red/green

**Data Visualization:**
- Animated progress bars for streaks
- Circular coin counters with spin animations
- Tree visualization with branch growth states

**Gamification Elements:**
- Badge cards with hover reveals
- Leaderboard table with alternating row colors
- Animated coin collecting effects

## Visual Treatments

**Eco-Futuristic Theme:**
- Subtle leaf patterns as background textures
- Floating particle effects (coins, leaves)
- Gradient overlays: Green to blue (142 76% 36% to 200 85% 45%)

**Tree Visualization:**
- SVG-based animated tree
- Growth states tied to coin balance
- Seasonal color changes based on progress

**Animations:**
- Page transitions: Smooth fade-ins
- Scroll animations: AOS.js slide-ups
- Micro-interactions: Button hover states, coin flip effects
- Loading states: Organic, leaf-inspired spinners

## Images Section
**Hero Background**: Large abstract eco-pattern with subtle animation
**Tree Illustration**: Central animated tree that grows/withers based on user progress
**Badge Icons**: Small SVG icons for achievements (leaves, coins, recycling symbols)
**Sponsor Logos**: Clean company logos in prizes sidebar
**No large hero image** - the animated tree serves as the primary visual focus

## Responsive Design
- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px)
- Collapsible sidebar on mobile
- Stacked card layouts on smaller screens