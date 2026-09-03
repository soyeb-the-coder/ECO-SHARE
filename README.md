# EcoShare — Surplus to Sustain

> **Turning food waste into food, fuel, and a better future.**

EcoShare is a zero-waste cascade platform that connects surplus campus food with hungry people, malnourished animals, and biogas facilities — ensuring nothing goes to landfill.

EcoShare — Surplus to Sustain

---

## The Problem

- India wastes **67 million tonnes** of food every year
- **194 million Indians** are undernourished
- **60 million stray animals** are starving on our streets
- Food rotting in landfills produces **methane — 25x more potent than CO₂**

## The Solution — Zero-Waste Cascade

```
Food Waste Detected
       ↓
  Edible for Humans?  →  YES  →  Feed People 🍽️
       ↓ NO
  Safe for Animals?   →  YES  →  Feed Animals 🐾
       ↓ NO
  Organic Waste?      →  YES  →  Biogas → Fuel Cars ⚡🚗
       ↓ NO
  Compost 🌱
```

**No existing platform handles all three tiers.** EcoShare is the only one.

---

## Features

### Core Platform
- **Live Food Feed** — Real-time surplus food listings from campus canteens
- **Animal Rescue** — Routes animal-safe food to shelters, Gaushalas, and street feeders
- **Biogas Tracker** — Tracks food waste → biogas → vehicle fuel with an interactive calculator

### Story Mode
- **5-act animated narrative** with custom Canvas 2D scenes for each act
- Real statistics about food waste, hunger, and climate impact

### Authentication & Admin
- **Login system** — Google, Email/Password, or Demo Login
- **Judge Admin Panel** — Impact dashboard, activity log, exportable reports

### Impact Dashboard
- **Chart.js visualizations** — Cascade breakdown pie chart, weekly impact bar chart
- **Interactive campus map** — Live pins showing food sources, shelters, and biogas facilities
- **Gamification** — Leaderboard with badges (Green Warrior, Animal Hero, Energy Pioneer)
- **Toast notifications** — Real-time alerts for every action

### UX
- **Mobile-first** — Bottom navigation bar for phones
- **Indian Folk theme** — Bold red/gold/green signboard aesthetic
- **Data persistence** — localStorage saves all data across sessions

---

## Tech Stack

| Technology | Use |
|---|---|
| **HTML/CSS** | Single-file structure, Indian folk design |
| **Tailwind CSS** | Utility-first styling (CDN) |
| **Vanilla JavaScript** | All logic, state management, rendering |
| **Canvas 2D API** | 5 animated story scenes |
| **Chart.js** | Impact dashboard visualizations |
| **GSAP** | Page transitions and animations |
| **Firebase SDK** | Auth + Firestore (optional, plug & play) |
| **localStorage** | Persistent data without backend |

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/soyeb-the-coder/ECO-SHARE.git
   ```
2. Open `index.html` in any browser
3. No build step needed — everything runs from a single file

---

## Enabling Firebase (Optional)

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a project → Add Web App
3. Copy your config and paste it in the `index.html` script section
4. Enable Google Auth and Firestore in the Firebase console
5. Change `USE_FIREBASE = false` to `true`

---

## Project Structure

```
ECO-SHARE/
  index.html    — Everything: HTML, CSS, JS, animations
  README.md     — This file
```

---

## Impact Numbers

| Metric | Value |
|---|---|
| Meals saved from trash | Tracked in real-time |
| CO₂ prevented | Calculated per meal (2.5 kg avg) |
| Animals fed | Tracked per shelter delivery |
| Biogas produced | 0.6 m³ per kg waste |
| Car distance from waste | 1.5 km per kg waste |
| Fuel cost saved | ₹60 per km vs petrol |

---

## What Makes This Different

| Existing Apps | EcoShare |
|---|---|
| Only feed humans | Feed humans + animals + produce biogas |
| Ad-hoc donations | Real-time cascade matching |
| No impact tracking | Charts, maps, leaderboard, export |
| No campus focus | Built specifically for campus ecosystem |

---

## Future Roadmap

- [ ] Real-time WebSocket notifications
- [ ] PWA support (installable on phone)
- [ ] Food safety temperature tracking
- [ ] Delivery route optimization
- [ ] Multi-campus expansion
- [ ] Integration with government food programs

---

## License

Built with ❤️ for a sustainable future

**Soyeb Ahmad** — [GitHub](https://github.com/soyeb-the-coder)
