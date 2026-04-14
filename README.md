# NeighbourWatch — Hyperlocal Crime Pattern Mapper

A community-driven, browser-based crime awareness dashboard for residential neighbourhoods. Citizens can anonymously report incidents, view live risk zones on an interactive map, and analyse crime patterns through heatmaps and timelines — all without any backend or database.

🔗 **Live Demo:** [Click here to try it](https://dev-harshyadav.github.io/NeighbourWatch)

---

## Screenshots

> *(Add a screenshot here — open the project in browser → press F12 → right-click → Screenshot, or use Windows Snipping Tool)*

---

## Features

### Dashboard
- Interactive SVG neighbourhood map with colour-coded risk zones (High / Medium / Low)
- Hover tooltips on each zone showing incident count, risk level, and crime type
- Click any zone for a detailed AI-pattern analysis popup
- Live alerts sidebar with real-time incident feed (auto-updates every 25 seconds)
- Stats cards showing total reports, active alerts, AI accuracy, and safe zones
- Hourly risk timeline bar chart

### Analytics
- Weekly crime heatmap (day × hour) showing peak crime windows
- Colour-coded intensity from safe (teal) to critical (red)
- Clickable heatmap cells with incident breakdown

### Report an Incident
- Anonymous incident submission — no login required
- 6 incident types: Theft, Snatching, Harassment, Suspicious Activity, Vandalism, Other
- Severity levels: Low / Medium / High
- Location input with date-time picker
- Optional description field
- Encrypted submission simulation with unique report ID (e.g. `NW-A3F8C2D1`)
- New reports appear instantly in the live alerts feed

### UI / UX
- Fully responsive dark-themed interface
- Sticky navigation with tab-based views
- Smooth animations and transitions throughout
- Modal popups for detailed zone/heatmap info
- Alert filtering by neighbourhood zone

---

## Tech Used

- **HTML5** — structure and semantic layout
- **CSS3** — custom properties, grid, flexbox, keyframe animations, backdrop-filter
- **Vanilla JavaScript** — all logic, DOM manipulation, live updates, SVG interaction
- **SVG** — hand-crafted interactive neighbourhood map
- **Google Fonts** — Syne (headings) + DM Sans (body)

> No frameworks. No libraries. No backend. 100% frontend.

---

## How to Run

1. Clone the repo:
   ```
   git clone https://github.com/dev-harshyadav/NeighbourWatch
   ```
2. Open `index.html` in any browser. Done — no server needed.

Or just visit the live demo link above.

---

## Project Structure

```
NeighbourWatch/
│
├── index.html      ← entire project (HTML + CSS + JS in one file)
└── README.md       ← this file
```

---

## What I Learned

- Building interactive SVG maps with JavaScript event listeners
- Using CSS custom properties for consistent dark-theme design
- DOM manipulation to simulate real-time live data feeds with `setInterval`
- Designing multi-view single-page applications (SPA) without any framework
- Creating data visualisations (bar charts, heatmaps) using pure HTML/CSS/JS
- Thinking about real-world civic problems and designing UI around user needs

---

## Future Improvements (planned)

- [ ] Connect to a real backend (Node.js + MongoDB) to store reports permanently
- [ ] Add real map using Leaflet.js or Google Maps API
- [ ] User authentication for verified community members
- [ ] Push notifications for high-risk alerts in your area
- [ ] Export incident reports as PDF

---

## Author

**Harsh Yadav** — B.Tech CSE, NIET Noida (2024–2028)

- GitHub: [@dev-harshyadav](https://github.com/dev-harshyadav)
- LinkedIn: [linkedin.com/in/your-link](https://linkedin.com/in/your-link)

---

*Built as part of my frontend development journey | #100DaysOfCode*
