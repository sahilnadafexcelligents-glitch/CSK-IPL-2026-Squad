# CSK IPL 2026 Squad

A static website showcasing the Chennai Super Kings IPL 2026 squad with interactive search, filtering, and player details.

**Live URL:** https://csk-ipl-2026.vercel.app

## Features

- Search players by name, role, state, region, city, or type
- Filter by role (Batter, WK-Batter, All-Rounder, Bowler)
- Filter by state/region and player type (Indian/Overseas)
- Live squad summary counters
- Player detail modal
- Fully responsive design (desktop and mobile)
- Accessible markup with ARIA attributes

## Tech Stack

- HTML5
- CSS3 (CSS custom properties, Grid, Flexbox)
- Vanilla JavaScript
- Hosted on Vercel

## Getting Started

```bash
npm start
```

Or open `index.html` in your browser.

## Deploy

```bash
npx vercel --prod --yes
```

## Project Structure

```
├── index.html              # Main website (HTML + CSS + JS)
├── package.json            # Project metadata
├── .vercel/                # Vercel CLI local config
├── .gitignore              # Ignores .vercel/
└── PROJECT_DOCUMENTATION.txt  # Detailed project docs
```

## Data Source

Squad data from the official IPLT20 CSK 2026 squad page:
https://www.iplt20.com/teams/chennai-super-kings/squad/2026
