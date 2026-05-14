# 🚀 Aditya Kumar Singh — Developer Portfolio

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-00d4ff?style=for-the-badge&logo=google-chrome&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-a855f7?style=for-the-badge)

**A futuristic, cinematic, single-file developer portfolio with dark cyberpunk aesthetics, interactive particle effects, multi-page navigation, and a fully working contact form.**

[View Portfolio](#) · [Report Bug](https://github.com/2184-Aditya-Kumar-Singh/2184-Aditya-Kumar-Singh/issues) · [Connect on LinkedIn](https://www.linkedin.com/in/aditya-kumar-singh-799ab0173/)

</div>

---

## ✨ Features

### 🎨 Visual Design
- **Dark futuristic theme** — deep navy, graphite, and black backgrounds
- **Neon accent palette** — electric blue (`#00d4ff`), cyan (`#00ffcc`), purple (`#a855f7`), and magenta
- **Glassmorphism cards** with glow borders and hover effects
- **Animated ambient glows** that drift across the background
- **CSS grid background** with radial fade mask
- **Google Fonts** — Orbitron, Space Grotesk, JetBrains Mono

### ⚡ Interactivity
- **Custom animated cursor** with a lagging ring follower
- **Mouse trail particles** that fade out behind the cursor
- **Interactive particle network** — 100 floating particles that connect to each other and react to mouse position
- **3D card tilt** on project cards (mouse-tracked perspective rotation)
- **Mouse glow spotlight** inside skill cards
- **Typewriter role animation** cycling through 7 developer roles
- **Glitch effect** on hero name hover
- **Animated stat counters** that count up on page load
- **Animated skill bars** that fill on entry

### 🗂️ Multi-Page SPA Navigation
The portfolio uses a fixed-position page system (no scrolling between sections) with smooth fade transitions:

| Key | Page |
|-----|------|
| `1` | Home |
| `2` | About |
| `3` | Skills |
| `4` | Experience |
| `5` | Projects |
| `6` | Achievements |
| `7` | Contact |

- **Arrow keys** (`←` `→` `↑` `↓`) — navigate between pages
- **Mouse wheel** — scroll to the edge of a page to go to the next/previous
- **Side dot indicator** — always shows which page you're on, clickable
- **Top nav bar** with active link highlight
- **Mobile hamburger menu** for small screens
- **Scroll progress bar** at the top of each page

### 📬 Working Contact Form
Uses **[FormSubmit.co](https://formsubmit.co)** AJAX — emails land directly in Gmail with no backend or account required.

- Real-time validation (name, email format, message)
- "SENDING…" loading state on the button
- Green success message on delivery
- Red error message with email fallback if it fails

> ⚠️ **First-time activation:** FormSubmit.co will send one confirmation email to `aditya.k.singhh@gmail.com` on the first submission. Click the link to activate the endpoint — all future submissions then work automatically.

---

## 📄 Pages & Content

### 🏠 Home
- Animated hero name with glitch-on-hover effect
- Typewriter cycling through: Android Developer, Java Engineer, DSA Problem Solver, Firebase Specialist, Software Developer, Open Source Builder, App Architect
- CTA buttons linking to Projects and Contact pages
- Social links: GitHub, LinkedIn, LeetCode, HackerRank, Email
- Live animated particle network background

### 👤 About
- Animated avatar with three rotating orbital rings and a pulse glow
- Animated stat counters: 300+ problems, 8.58 CGPA, Top 13, Top 30
- Info pills: location, university, tech stack, availability
- Detailed bio paragraphs

### 🛠️ Skills
- Category filter tabs: All / Languages / Tools & Platforms / Concepts
- 24 skill cards with emoji icons and mouse-glow effect
- Animated horizontal proficiency bars (Java 92%, Android 88%, Firebase 85%, DSA 82%, SQL 80%, Python 72%)
- Domain cards: Android Development, Software Development, Data Analytics, App Automation

### 💼 Experience
- Two-column layout: timeline on left, education on right
- **Timeline entries:**
  - Google App Developer Program — Cohort 10
  - ICDCIT 2025 — Student Coordinator
  - ICDCIT 2026 — Transport Coordinator
- Education cards: KIIT University (B.Tech CSE, CGPA 8.58) and Delhi Public School (12th CBSE, 80.8%)
- Key achievement highlights at the bottom

### 🚧 Projects
Four fully detailed project cards with 3D tilt hover, feature lists, GitHub links, and live status indicators:

| # | Project | Stack |
|---|---------|-------|
| 01 | [KIIT Chat Portal](https://github.com/2184-Aditya-Kumar-Singh/KIIT_ChatApp) | Java · Firebase · Android |
| 02 | [Virtual Blood Bank](https://github.com/2184-Aditya-Kumar-Singh/Virtual-Blood-Bank) | Java · Firebase · Google Maps API |
| 03 | [Migration Manager Discord Bot](https://github.com/2184-Aditya-Kumar-Singh/Migration-Manager-Discord) | Python · Discord API · Automation |
| 04 | [InterviewAce](https://github.com/2184-Aditya-Kumar-Singh/InterviewAce) | Android · Java · AI-Powered |

### 🏆 Achievements
- 30-Day Coding Challenge Winner — USC KIIT
- Relaython Top 13 — GeeksForGeeks
- Smart India Hackathon Top 30
- 300+ LeetCode Problems Solved
- HackerRank Certifications: Java, Python, SQL, Problem Solving
- Coding profile cards: LeetCode, GitHub, LinkedIn, HackerRank

### 📬 Contact
- Contact info cards: email, phone, LinkedIn, GitHub
- Working AJAX contact form
- Terminal-style availability status widget
- Footer with full details

---

## 🗂️ Project Structure

```
portfolio/
└── index.html          # The entire portfolio — HTML + CSS + JS in one file
```

Everything is self-contained in a single HTML file. No build step, no dependencies to install, no Node.js required.

---

## 🚀 Getting Started

### Option 1 — Open Directly
Just download `index.html` and open it in any modern browser. That's it.

```bash
# Clone the repo
git clone https://github.com/2184-Aditya-Kumar-Singh/2184-Aditya-Kumar-Singh.git

# Open in browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Option 2 — Local Dev Server (recommended for form testing)
```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using VS Code
# Install the "Live Server" extension, then right-click index.html → Open with Live Server
```

Then visit `http://localhost:8000` in your browser.

### Option 3 — Deploy to GitHub Pages
1. Push `index.html` (rename to `index.html` if needed) to your repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your portfolio will be live at `https://2184-aditya-kumar-singh.github.io/<repo-name>/`

---

## 🎨 Customisation

All content is in plain HTML — no framework, no config files. To personalise:

| What to change | Where to find it |
|----------------|-----------------|
| Name, bio, description | Search for `Aditya Kumar` in the HTML |
| Social links | `hero-socials` section and `contact-items` section |
| Projects | `pg-projects` div — 4 `.proj-card` blocks |
| Skills | `sk-grid` div — add/remove `.sk-card` elements |
| Experience | `pg-exp` div — `.tl-item` blocks |
| Achievements | `pg-achieve` div — `.ach-card` blocks |
| Color scheme | `:root` CSS variables at the top of `<style>` |
| Contact email | Search for `aditya.k.singhh@gmail.com` and replace all |

### Color Variables
```css
:root {
  --blue:    #00d4ff;   /* Primary accent */
  --cyan:    #00ffcc;   /* Secondary accent */
  --purple:  #a855f7;   /* Tertiary accent */
  --magenta: #f0abfc;   /* Highlight */
  --gold:    #fbbf24;   /* Achievement color */
  --bg:      #020408;   /* Main background */
}
```

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

> Requires a browser with CSS `backdrop-filter`, `clip-path`, and `Canvas 2D` support.

---

## 📬 Contact

**Aditya Kumar Singh**

- 📧 Email: [aditya.k.singhh@gmail.com](mailto:aditya.k.singhh@gmail.com)
- 📱 Phone: +91 7368971774
- 💼 LinkedIn: [aditya-kumar-singh-799ab0173](https://www.linkedin.com/in/aditya-kumar-singh-799ab0173/)
- 🐙 GitHub: [2184-Aditya-Kumar-Singh](https://github.com/2184-Aditya-Kumar-Singh)
- ⚡ LeetCode: [Aditya_Chauhan_12](http://leetcode.com/u/Aditya_Chauhan_12/)
- ⬡ HackerRank: [aditya_k_singhh](https://www.hackerrank.com/profile/aditya_k_singhh)

---

## 📜 License

This project is open source under the [MIT License](LICENSE). Feel free to use it as a template — just change the content to your own.

---

<div align="center">

Made with ☕ Java, 🔥 Firebase, and a lot of late nights

**⭐ If you found this useful, drop a star!**

</div>
