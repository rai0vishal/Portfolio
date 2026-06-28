<div align="center">

# 💼 Vishal Rai — Portfolio Website

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](https://rai0vishal.github.io/Portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-rai0vishal-black?style=for-the-badge&logo=github)](https://github.com/rai0vishal)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-VishalRai0108-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/VishalRai0108)

</div>

A modern, responsive personal portfolio website showcasing my work as a Full Stack MERN Developer. Built with HTML, CSS, JavaScript, GSAP animations, and integrated with live GitHub activity — designed to be fast, clean, and professional.

---

## 🚀 Features

### ✨ **Core Features**
- Fully responsive design across all screen sizes
- Animated hero section with GSAP-powered name reveal
- Interactive loading screen animation
- Smooth scroll navigation with active section detection
- Custom cursor implementation
- Dark theme with consistent color system
- Particle background in the Projects section

### 📧 **Contact Form**
- Functional contact form powered by Formspree
- Client-side validation with real-time feedback
- Loading states, success and error messages
- Floating sidebar email link for quick access

### ⚡ **Performance**
- Lazy loading for all images
- Service Worker for offline caching (PWA-ready)
- Reduced motion support for accessibility
- Optimised GSAP animations with `will-change`
- Critical resource preloading

### 🐙 **GitHub Integration**
- Live GitHub stats — repos, stars, followers, recent commits
- Recent public activity feed (Push, PR, Issue events)
- Most used programming languages display
- Graceful fallback data if API is unavailable

### 🎨 **UI / UX**
- GSAP ScrollTrigger animations on scroll
- Hover effects on all interactive elements
- Animated skill icon grid
- Project cards with tech badges, live demo, and GitHub links
- Timeline-style Journey section

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup with accessibility attributes
- **CSS3** — Custom styles + Bootstrap 5 + Tailwind CSS (Play CDN)
- **JavaScript (ES6+)** — Core interactivity, GitHub API, form handling
- **GSAP 3** — Hero animations, scroll reveals, timeline effects
- **Particles.js** — Particle background in Projects section
- **Formspree** — Contact form backend (no server required)
- **GitHub API** — Live coding activity and stats
- **Service Worker** — Offline support and asset caching

---

## 📁 Project Structure

```
Portfolio/
├── index.html        # Main HTML — all sections live here
├── styles.css        # Custom styles and animation definitions
├── script.js         # All JS — GitHub API, GSAP, form, cursor
├── sw.js             # Service Worker for PWA/offline support
├── manifest.json     # PWA manifest
├── assets/           # Images, screenshots, resume PDF
│   ├── VishalRaiPortfolio.jpg      # Profile photo
│   ├── Vishal_Rai_Resume.pdf       # Downloadable resume
│   ├── taskflow-ss.png             # TaskFlow screenshot
│   ├── skillx-ss.png               # SKillX screenshot
│   └── ...                         # Other project screenshots
└── README.md
```

---

## 🧩 Sections

| Section | Description |
|---|---|
| **Hero** | Animated name reveal, tagline, View Projects CTA |
| **About** | Bio, profile photo, social links, resume download |
| **Journey** | Timeline — Internship, B.Tech, XII, X |
| **Skills** | Tech stack icons grouped by Frontend / Backend / Database / Tools |
| **GitHub Activity** | Live stats + recent public events |
| **Projects** | Cards with screenshots, tech badges, live demo + GitHub links |
| **Contact** | Formspree form + email + location info |

---

## 🔧 Setup & Configuration

### Run Locally

```bash
# Clone the repo
git clone https://github.com/rai0vishal/Portfolio.git
cd Portfolio

# Open with a local server (recommended)
npx serve .

# Or simply open index.html directly in your browser
```

### Configure Contact Form

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy your endpoint
3. In `script.js`, replace the endpoint:

```javascript
const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

### Configure GitHub Stats

In `script.js`, the username is already set to:

```javascript
const username = 'rai0vishal';
```

Update this if you fork and customise for yourself.

---

## 🌟 Featured Projects

### [TaskFlow](https://github.com/rai0vishal/TaskFlow)
Full-stack Kanban project management app with real-time collaboration via Socket.IO, drag-and-drop boards, RBAC, and JWT authentication.
`React.js` `Node.js` `Express.js` `MongoDB` `Socket.IO` `JWT`

### [SKillX](https://github.com/rai0vishal/SKillX)
AI-powered peer-to-peer skill exchange platform with WebRTC video sessions, Gemini AI roadmap generation, custom matching algorithm, and Firebase auth
`React.js` `Node.js` `MongoDB` `WebRTC` `Gemini AI` `Socket.IO` `Firebase`

---

## 📱 PWA Support

- Installable as a native app on mobile and desktop
- Offline support via Service Worker caching
- Optimised for fast load on all network conditions

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 📞 Contact

- **Email**: raivishal2121@gmail.com
- **LinkedIn**: [linkedin.com/in/VishalRai0108](https://linkedin.com/in/VishalRai0108)
- **GitHub**: [@rai0vishal](https://github.com/rai0vishal)
- **Location**: Lucknow, Uttar Pradesh, India
