# Freedom Factory USA — Astro Website Redesign

A complete ground-up redesign of freedomfactoryusa.com, built with Astro. Dark, industrial motorsport aesthetic with aggressive typography and a clear UX hierarchy for both spectators and competitors.

## 🏁 Features

- **Homepage** — Hero with stats bar, upcoming events grid, feature split (fans vs. racers), track history, and driving experience CTA
- **Schedule** — Full 2026 season calendar organized by month with venue key and ticket links
- **Events** — Detailed event cards for every event type with dates and descriptions
- **Competitors** — Full competitor hub with 12 class rule downloads, step-by-step registration guide, and contact info
- **About** — Track history, facts table, and quick links
- **Contact** — Contact form, address, email, social links

## 🎨 Design System

- **Fonts**: Bebas Neue (display) + Barlow Condensed (headers/labels) + Barlow (body)
- **Colors**: Deep black `#0a0a0a`, Freedom Red `#e8192c`, Racing Yellow `#f5c518`
- **Motifs**: Checker bar stripe, diagonal texture overlays, motorsport SVG track diagram
- **Animations**: CSS keyframe fade-up on hero elements, hover lifts on cards

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
src/
├── layouts/
│   └── Layout.astro        # Base layout with nav + footer
├── pages/
│   ├── index.astro          # Homepage
│   ├── schedule.astro       # Full 2026 schedule
│   ├── events.astro         # Events overview
│   ├── competitors.astro    # Competitor hub (rules + registration)
│   ├── about.astro          # About the track
│   ├── contact.astro        # Contact page
│   └── 404.astro            # 404 page
└── styles/
    └── global.css           # Design system / global styles
```

## 📋 Competitor Resources

All competitor rule PDFs link directly to the original URLs from freedomfactoryusa.com:

- General Rules (required for all)
- Crown Victoria
- Burnout Rivals
- Danger Ranger 9000
- Spectator Drags
- Mini Stocks (DOCX)
- Altima 600 Enduro
- Open Wheel Modified
- Pure Stock
- Pro Trucks
- Super Late Models
- Mod Mini

## 🔧 Customization

Update the event data arrays in `schedule.astro`, `events.astro`, and `index.astro` to keep the schedule current. Rule PDF links are stored in `competitors.astro`.

## 📬 Contact Info

- Email: events@fffl.com
- Address: 21050 FL-64, Bradenton, FL 34212
- Tickets: https://tickets.thefoat.com/FreedomFactory
