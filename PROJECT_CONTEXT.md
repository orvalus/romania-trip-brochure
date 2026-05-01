# Romania Luxury Brochure Project

## Working Environment
- Location: WSL (Ubuntu)
- Working Directory: /home/cornel/src/brosura
- Main File: index.html
- GitHub: https://github.com/orvalus/romania-trip-brochure
- GitHub Pages: https://orvalus.github.io/romania-trip-brochure/

## Project Overview
Interactive HTML brochure showcasing a luxury 7-day journey through Romania and Transylvania. Hosted on GitHub Pages.

## Trip Details
- Dates: June 25 - July 1, 2026
- Group: Private itinerary (formerly 3 couples)
- Departure/Return: Bucharest (Otopeni), flexible for early departure

## Design Philosophy
- Style: Ultra-luxury, elegant, minimal
- Theme: Dark theme with gold accents
- Typography: Cormorant Garamond + Inter
- Approach: Cinematic visuals, minimal text, aspirational tone

## Brochure Structure (12 Slides)
1. Cover — Hero image (local: peles.jpg)
2. Why Romania — Pitch with Transfăgărășan image
3. Journey Highlights — 6 cards (Peleș, Bran, Brașov, Viscri, Sighișoara, Sibiu) with UNESCO World Heritage references
4. Day 1 — Bucharest → Sinaia → Brașov (Peleș Castle, Kuib lunch, Dei Frati dinner)
5. Day 2 — Brașov & Bran Castle
6. Day 3 — Viscri → Sighișoara
7. Day 4 — Sighișoara → Biertan → Sibiu
8. Day 5 — Sibiu & Corvin Castle (combined, no longer OR option)
9. Day 6 — Transfăgărășan → Bucharest (includes Posada Vidraru dinner)
10. Transport — Option 1: Private Van & Driver / Option 2: Self-Drive
11. Additional Experiences — 5 individual cards + 1 grouped wine card (Villa Vinea, Vinothek, Apoldium, Bethlen-Haller + Jidvei)
12. Closing — "The Promise"

## Stay Blocks
- Days 1-2: Radisson Blu Aurum (Brașov)
- Day 3: Fronius Residence (Sighișoara)
- Days 4-5: Noblesse Boutique (Sibiu)
- Day 6: Hilton Garden Inn (Otopeni)

## Key Features
- Keyboard navigation (Arrow keys, Space)
- Mouse click navigation (dots at bottom)
- Touch swipe support
- Ken Burns animation on hero images
- Smooth reveal animations
- Mouse spotlight effect
- Fully responsive with mobile scroll support
- Lightbox for image galleries

## Technical Stack
- HTML5 + Tailwind CSS (CDN v4)
- Vanilla JavaScript
- Google Fonts (Cormorant Garamond + Inter)
- No build process — runs directly in browser
- Images stored locally in /images/

## Local Images (30 files)
- Cover: peles.jpg
- Why Romania: transfagarasan.jpg
- Highlights thumbs: peles_thumb, bran_thumb, brasov_thumb, viscri_thumb, sighisoara_thumb, sibiu_thumb
- Day 1: valea-prahovei_day1, peles_day1, brasov_day1
- Day 2: brasov_day2, bran_thumb
- Day 3: viscri_day3, Sighisoara_day3
- Day 4: biertan_day4, sibiu_thumb
- Day 5: sibiu_day5, hunedoara_castle_day5
- Day 6: transfagarasan
- Additional: sinaia_monastery_thumb, sinaia_casino_thumb, rupea_thumb, alba_iulia_thumb, curtea_arges_thumb, wine_experiences_thumb
- Closing: last_page
- Other: biertan, bran_thumb (jpeg), hotel-valea-prahovei (webp)

## UNESCO World Heritage Sites Referenced
- Sighișoara — Historic Centre (individual site)
- Viscri — Villages with Fortified Churches in Transylvania (composite site)
- Biertan — Villages with Fortified Churches in Transylvania (composite site)

## Changes Applied (from opencode change files)
- Removed hotel slide, added Stay blocks to each day
- Shortened restaurant descriptions to single line
- Compact layout spacing (space-y-2, smaller text)
- Updated transport slide with two options (subtly favoring van)
- Improved text polish across all slides
- Added Additional Experiences slide with 6 cards (5 individual + 1 grouped wine)
- Combined Day 5 (Sibiu & Corvin Castle, removed OR choice)
- Removed particle canvas effect (was causing artifact)
- All images migrated to local /images/ folder
- Added UNESCO World Heritage labels (brick color #c4643d)
- Fixed page numbering for 12-slide structure

## Git Info
- Remote: git@github.com:orvalus/romania-trip-brochure.git
- Branch: main
- .gitignore: *.Zone.Identifier, *.deb

## Current Status
✅ 12 slides complete and functional
✅ All images local and optimized
✅ Design system consistent
✅ Navigation working perfectly
✅ Mobile responsive with scroll support
✅ Deployed on GitHub Pages
✅ Ready for content refinements

---
Last Updated: May 1, 2026
Version: 2.0
