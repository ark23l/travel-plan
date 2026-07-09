---
name: travel-plan-viz
description: Use this skill when the user wants to create a visual travel plan (旅行计划) with an HTML itinerary. Triggers include: "旅行计划", "travel plan", "行程", "itinerary", or requests to plan a trip. Creates a visual HTML travel plan with day-by-day timeline, route maps, and tips, then deploys to GitHub Pages for a permanent shareable link.
---

# Travel Plan Visualization

## Overview

Creates beautiful, visual HTML travel plans with detailed day-by-day itineraries, route maps, and travel tips. Always deploys to GitHub Pages for a permanent shareable link.

## Workflow

1. **Gather requirements** — destinations, dates, hotel, must-visit spots, preferences
2. **Design the itinerary** — group activities geographically, avoid backtracking
3. **Generate HTML** — write to `/Users/arkkkkkk/travel-plan-viz/index.html`
4. **Deploy to GitHub Pages** — commit and push to `ark23l/sanya-travel-plan` repo (or create a new repo per trip), enable Pages

## HTML Template

Use the existing `index.html` as a template reference. Key design principles:
- Ocean/beach color palette (blues, greens, warm sands)
- Day cards with timeline layout
- Info cards grid for quick facts
- Route map section showing travel connections
- Tips section with practical advice
- Mobile responsive

## Sharing

Always generate a shareable link. The preferred approach is GitHub Pages for a permanent URL. If the user needs a quick temporary link, use localtunnel as a fallback.

## Location Context

- Hotel: 天丽湾凯悦酒店 (Sanya Bay, near airport, ~10 min drive)
- Airport: 三亚凤凰国际机场
- Key areas: 三亚湾 (west), 海棠湾 (east, duty-free + 蜈支洲岛), 亚龙湾 (east-central)
