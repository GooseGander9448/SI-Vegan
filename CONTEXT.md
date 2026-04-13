# U HERB — Project Context for Claude Code

## What this is
A static HTML/CSS/JS website called "U HERB" (tab title) for a project called "Staten Island Plant Based" — a community guide to fully plant-based dishes on Staten Island, NY.

## Current files
- `index.html` — main page
- `about.html` — about us page

## Layout
- Left sidebar (fixed, ~370px) with white card sections stacked vertically:
  1. Site name: "Staten Island Plant Based" (two lines)
  2. Bio/description card with "Let's talk" email button
  3. Clock card showing live Staten Island, NY time (America/New_York timezone)
  4. Navigation card: Home, Plans for the Site, About Us, Restaurants
  5. Last updated card (timestamps when page was loaded)
- Right side: 3-column image grid (scrollable, images scale with window)

## Navigation pages built so far
- Home (index.html) — active
- About Us (about.html) — active
- Plans for the Site — not built yet
- Restaurants — not built yet

## Click-to-flip on images
Each image card should flip to black background with white text on click showing:
- Dish name (large, top)
- Description/ingredients (middle, muted)
- Restaurant name (bottom, bold)
- Address (bottom, muted)
This was implemented but had JS issues — needs to be verified and fixed.

## Known issues to fix
1. Click-to-flip on images may not be working correctly
2. Clock and "Last updated" JS occasionally breaks when file is edited — keep all JS in one clean <script> block at the bottom

## Design style
- Background: #e8e8e8
- Cards: #f7f6f4
- Font: DM Sans (Google Fonts)
- Border radius: 12px
- Subtle borders: 1px solid rgba(0,0,0,0.07)
- All text scales with clamp() for responsiveness
- No scrollbars visible anywhere
- Images use aspect-ratio classes: .tall (3/4), .sq (1/1), .wide (4/3)

## Next tasks
1. Verify and fix the click-to-flip functionality on image cards
2. Build out "Plans for the Site" page
3. Eventually build "Restaurants" page with real dish/restaurant data
4. Make layout mobile responsive

## Image sources
Currently using placeholder images from framerusercontent.com CDN.
These will eventually be replaced with real food photos.

## The person you're working with
Not a developer — city worker who built this with Claude chat. 
Keep explanations simple, make changes carefully, don't break working things.
