# 🎙️ TechWave — Podcast Landing Page

A clean, fully responsive landing page for **TechWave**, a fictional tech podcast covering AI, productivity, and personal growth. Built as a front-end assignment using pure HTML and CSS.

## 🌐 Live Demo

👉 [View Live Site](https://tomal5085.github.io/ASSIGNMENT-002/)

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, layout (Flexbox & Grid), responsiveness |
| **Google Fonts – Inter** | Typography |
| **Font Awesome 7** | Icons (star ratings, etc.) |
| **YouTube Embed API** | Featured episode video cards |

---

## ✨ Key Features

- **Responsive Navbar** — Hamburger menu for mobile, full nav for desktop
- **Hero / Banner Section** — Gradient circle with mic icon, CTA buttons (Spotify & Subscribe)
- **About Section** — Podcast description with animated stats grid (150K+ listeners, 200+ episodes, 4.9 rating, 50+ experts)
- **Why Choose TechWave** — Feature cards with custom icons (audio quality, mobile-friendly, global community, interviews, resources)
- **Featured Episodes** — Embedded YouTube videos with episode metadata
- **Meet the Host** — Host profile card with social media links
- **Footer** — Platform links (Spotify, Apple Podcasts, YouTube, Twitter)

---

## 📦 Dependencies

This is a **zero-dependency** static project. External resources are loaded via CDN:

```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap" rel="stylesheet">

<!-- Font Awesome 7 -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
```

No `npm install` required. No build process.

---

## 🚀 Running Locally

Since this is a plain HTML/CSS project, you just need a browser:

**Option 1 — Open directly**
```bash
git clone https://github.com/TOMAL5085/ASSIGNMENT-002.git
cd ASSIGNMENT-002
# Open index.html in your browser
```

**Option 2 — Use VS Code Live Server (recommended)**
1. Clone the repo (same as above)
2. Open the folder in [VS Code](https://code.visualstudio.com/)
3. Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
4. Right-click `index.html` → **Open with Live Server**

---

## 🔗 Links

| | |
|---|---|
| 🌐 Live Site | [tomal5085.github.io/ASSIGNMENT-002](https://tomal5085.github.io/ASSIGNMENT-002/) |
| 📁 Repository | [github.com/TOMAL5085/ASSIGNMENT-002](https://github.com/TOMAL5085/ASSIGNMENT-002) |

---

## 📁 Project Structure
ASSIGNMENT-002/
├── index.html          # Main HTML file
├── styles/
│   └── style.css       # All styles
└── assets/
├── microphone.png
├── hamburger-menu.png
├── spotify.png
├── host.png
└── ...             # Other icons and images
