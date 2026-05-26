# 🎬 StreamFlix — Netflix Clone

A full-featured Netflix clone built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no dependencies.

[![Demo Preview](https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?w=800&q=60)](https://your-demo-link.com)

---

## ✨ Features

### Pages
| Page | Description |
|------|-------------|
| `index.html` | Home page with hero section, content rows, and modal |
| `browse.html` | Browse/search with genre filters and grid layout |
| `player.html` | Full-featured video player |
| `signin.html` | Authentication page with form validation |

### Home Page
- 🎯 **Hero section** with animated title, movie details, and CTA buttons
- 📺 **Continue Watching** row with progress bars
- 🔥 **Trending Now** horizontally scrollable row with hover effects
- 🏆 **Top 10 in India** row with large number overlays (Bebas Neue font)
- 🆕 **New Releases** featured grid
- 🎭 **"Because You Watched"** personalized row
- ℹ️ **Info Modal** with cast details, match score, and play button
- 🏷️ **Genre category pills** for filtering
- 🔍 **Search bar** in navbar

### Browse Page
- 🗃️ **Responsive card grid** (auto-fill, scales to screen size)
- 🎛️ **Multi-filter system** — genre pills, type selector, year selector
- 📊 **Sort** by match %, year, or A–Z
- 🔖 **Ribbon badges** (New, Series, Anime, Doc)
- ♾️ **Load More** pagination
- 48 sample titles with real metadata

### Video Player
- ▶️ **Simulated playback** with live time counter
- ⏭️ **Progress bar** — click to seek, hover for time tooltip
- ⏩ **±10s skip** buttons
- 🔊 **Volume slider** (expand on hover)
- 📋 **Episodes panel** overlay with full episode list
- ⏭ **Skip Intro** button
- 🎬 **Next Episode** card popup
- 4K Ultra HD badge
- ⌨️ **Keyboard shortcuts**: Space (play/pause), ←→ (seek), F (fullscreen), Esc

### Sign In Page
- ✅ **Form validation** with animated floating labels
- 🔒 **Password show/hide** toggle
- ⏳ **Loading spinner** on submit
- 🎨 Blurred hero background
- Responsive layout

### UI/UX Details
- 🖱️ **Card hover** — scale + shadow + overlay with actions
- 📜 **Scroll buttons** for horizontal rows (appear on section hover)
- 🌑 **Smooth navbar** — transparent → solid on scroll
- 🎞️ **Staggered hero animation** on page load
- 📱 **Fully responsive** — works on mobile
- 🔲 **Skeleton loader** (browse page)

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Semantic structure, 4 pages |
| CSS3 | Grid, Flexbox, custom properties, animations |
| Vanilla JS | DOM manipulation, state, events |
| Google Fonts | Bebas Neue + Inter |
| Unsplash | Placeholder images |

**No Node.js. No npm. No build step.** Just open `index.html`.

---

## 🚀 Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/streamflix-clone.git
cd streamflix-clone
# open index.html in your browser
```

Or use VS Code Live Server:
```
Right-click index.html → Open with Live Server
```

---

## 📁 Project Structure

```
streamflix-clone/
├── index.html       # Home page
├── browse.html      # Browse & filter
├── player.html      # Video player
├── signin.html      # Authentication
└── README.md
```

All CSS and JS is **inline per page** for maximum portability — no external files to miss.

---

## 📸 Screenshots

### Home Page
Hero section, content rows, Top 10, modal

### Browse Page
Grid layout with filters and genre pills

### Player Page
Full video player with episodes panel

---

## 🎓 About

Built as a **portfolio project** after completing 2nd year of college. This project demonstrates:

- CSS layout mastery (Grid + Flexbox)
- JavaScript DOM manipulation and state management
- Responsive design without any frameworks
- UI/UX patterns from real-world streaming apps
- Clean, organized multi-page architecture

---

## 🔮 Future Plans

- [ ] Add React/Next.js version
- [ ] Integrate TMDB API for real movie data
- [ ] Add localStorage for watchlist persistence
- [ ] User authentication with Firebase
- [ ] Actual video playback with HLS.js
- [ ] PWA support

---

## 📄 License

MIT License — feel free to use this for your own learning!

---

> **Disclaimer:** StreamFlix is a fan-made portfolio project. All content, images, and movie data shown are placeholders. This is not affiliated with Netflix in any way.

⭐ **Star this repo if you found it helpful!**
