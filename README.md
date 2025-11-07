# ✨ Daily Quote

Unlock a spark of inspiration every day. Browse, filter, listen, save, and share quotes — all in a sleek, responsive UI.

[![Made with HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff)](#)
[![Made with CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff)](#)
[![Made with JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![Font Awesome](https://img.shields.io/badge/Icons-Font%20Awesome-528DD7?logo=fontawesome&logoColor=fff)](https://fontawesome.com/)
[![Google Fonts](https://img.shields.io/badge/Fonts-Google%20Fonts-4285F4?logo=google&logoColor=fff)](https://fonts.google.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

---

## 🌟 Features

- 🗂️ Category filter: Browse quotes by Motivation, Wisdom, Humor, Productivity, Perseverance, or view All.
- 🔀 New Quote: Generate a fresh quote anytime.
- 🧠 Author + Category: Clean presentation with author and tags.
- ❤️ Favorites Drawer: Save and manage favorite quotes (persisted with LocalStorage).
- 🌓 Theme Toggle: Light/Dark/Auto theme with a single click.
- 🔊 Speak: Listen to quotes via the Web Speech API.
- 📋 Copy: Copy quote text to your clipboard instantly.
- 📤 Share: Share quotes via the Web Share API (when supported).
- ▶️ Auto-play: Automatically cycle through new quotes at configurable intervals.
- 📱 Responsive: Works beautifully on mobile, tablet, and desktop.
- ♿ Accessible: Semantic HTML, ARIA attributes, and keyboard-focusable controls.

---

## 📸 Preview

![image](https://github.com/MdSaifAli063/Daily-Quote/blob/8261d6e970e18f68b79fa3da478f28c708bb2462/Screenshot%202025-09-03%20003103.png)

-Favorite view

![image](https://github.com/MdSaifAli063/Daily-Quote/blob/6444311597d02608e5bebfd0d9f91ae8786524b2/Screenshot%202025-09-03%20004010.png)

---

## 🚀 Quick Start

- Option A: Double-click index.html to open it in your browser.
- Option B: Serve locally for best results (especially for some browser APIs):
  - Using VS Code: Install the “Live Server” extension and click “Go Live”.
  - Using npm http-server:
    - npm install -g http-server
    - http-server . -p 8080
    - Open http://localhost:8080

No build step. No dependencies. Pure HTML/CSS/JS.

---

## 🧭 How to Use

- Filter by Category: Use the dropdown to narrow quotes by theme.
- New Quote: Click “New Quote” to fetch another one.
- Auto-play:
  - Toggle Auto-play on.
  - Choose a speed: every 5s, 10s, or 20s.
- Copy: Click “Copy” to put the quote and author on your clipboard.
- Speak: Click “Speak” to hear the quote (browser must support SpeechSynthesis).
- Share: Click “Share” to open the native share dialog (mobile-friendly).
- Favorite:
  - Click “Favorite” to save the current quote.
  - Open the Favorites drawer via the heart icon in the header.
  - Manage saved items from the drawer.

---

## 🧩 Tech Stack & APIs

- HTML5, CSS3 (custom styles), JavaScript (vanilla)
- Fonts: Google Fonts (Poppins)
- Icons: Font Awesome 6
- Browser APIs:
  - LocalStorage (persist favorites)
  - Clipboard API (copy to clipboard)
  - Web Speech API (text-to-speech)
  - Web Share API (share to native targets; availability varies by browser/device)

---

## 🗂️ Project Structure

. ├─ index.html # App markup and structure ├─ style.css # Styling and themes (light/dark/auto) └─ script.js # App logic: quotes, filters, autoplay, favorites, actions

---

## ⚙️ Configuration Notes

- Theme:
  - UI supports light, dark, and auto (system) themes via the toggle.
- Auto-play:
  - Default interval: 10 seconds (selectable: 5s, 10s, 20s).
- Favorites:
  - Stored locally in the browser (LocalStorage).
  - No server or external database required.

---

## 🌍 Browser Support

- Modern browsers (Chromium, Firefox, Safari, Edge).
- Web Speech and Web Share APIs may have limited support on desktop; best on mobile browsers.
- If a feature isn’t supported, the app degrades gracefully.

---

## 🔐 Privacy

- All data (favorites) is stored locally on your device via LocalStorage.
- No tracking. No external backend calls by default.

---

## ♿ Accessibility

- Semantic landmarks: header, main, footer, aside.
- ARIA labels on interactive controls.
- Keyboard-navigable buttons.
- Color contrast mindful themes.
- Screen reader friendly labels on icons and controls.

---

## 🛠️ Development Tips

- Use a local server to ensure Clipboard/Web Speech/Web Share behave consistently.
- Keep quotes data and UI interactions decoupled in script.js.
- Consider adding debounce for rapid user actions (if needed).

---

## 🗺️ Roadmap Ideas

- Add more categories and quote sources.
- Keyboard shortcuts (e.g., N for next, F for favorite).
- Export favorites as JSON or text.
- PWA support for offline caching.
- Multilingual quotes and localization.

---

## 🤝 Contributing

Contributions are welcome!

- Fork the repo
- Create a feature branch: git checkout -b feat/amazing-improvement
- Commit changes: git commit -m "Add amazing improvement"
- Push the branch: git push origin feat/amazing-improvement
- Open a Pull Request

Please keep UI/UX consistent and accessible.

---

## 🙏 Acknowledgements

- Fonts by Google Fonts (Poppins)
- Icons by Font Awesome
- Inspiration from countless quote apps and minimalist UI patterns

---

## 📄 License

MIT License — feel free to use and modify for personal or commercial projects.

---

## 🔗 Links

- Live Demo: null
- Issues: open an issue with steps to reproduce and environment details
- Discussions: propose ideas or enhancements

Made with ❤️ to brighten your day.
