Here is your updated version with **“Spectral Blade” fully removed** and replaced properly with **“Word & Readability Telemetry”** everywhere needed.

---

# 📄 **README.md** for your repo

Create a file named `README.md` in your project root with this content:

````markdown
# 🔮 Word & Readability Telemetry

![Version](https://img.shields.io/badge/version-1.0.0-00f2ff?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-7000ff?style=flat-square)
![Accessibility](https://img.shields.io/badge/a11y-WCAG-50FFB1?style=flat-square)

> **Futuristic word analysis tool with cyberpunk aesthetics, real-time readability metrics, and keyword telemetry.**

![Word & Readability Telemetry Preview](https://via.placeholder.com/800x400/030508/00f2ff?text=Word+%26+Readability+Telemetry+Preview)

---

## ⚡ Features

| | |
|---|---|
| **📊 Live Metrics** | Real-time word, character, sentence & paragraph counts |
| **🎯 Keyword Telemetry** | Density tracking for 10 predefined keywords |
| **📖 Readability Scoring** | Automated grade-level calculation |
| **⏱️ Time Estimation** | Reading & speaking time in seconds |
| **🌓 Dual Theme** | Cyberpunk dark / light mode with class-based switching |
| **📱 Fully Responsive** | Fluid grid, touch-friendly buttons, safe-area support |
| **🔔 Toast Notifications** | Non-blocking feedback (no more alerts!) |
| **♿ Accessibility** | ARIA live regions, focus indicators, semantic buttons |
| **📋 Share Features** | Copy link, copy results, social sharing |
| **🔗 URL Hash State** | Persist text in URL for sharing |

---

## 🖥️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, backdrop filters
- **Vanilla JavaScript** — zero dependencies, pure performance
- **Google Fonts** — Inter & JetBrains Mono

---

## 🚀 Quick Start

1. Clone the repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/word-readability-telemetry.git
````

2. Open `index.html` in your browser

   ```bash
   cd word-readability-telemetry
   open index.html  # or double-click
   ```

No build step. No dependencies. Just works.

---

## 🎮 Usage

| Action                      | Description                  |
| --------------------------- | ---------------------------- |
| **Type/paste text**         | Auto-analyzes with debounce  |
| **Ctrl/Cmd + Enter**        | Keyboard shortcut to analyze |
| **Analyze button**          | Manual trigger               |
| **Reset button**            | Clear all data               |
| **Theme toggle (floating)** | Switch between dark/light    |
| **Share buttons**           | Copy/share results           |

---

## 🎨 Design System

```css
:root {
  --base: #030508;           /* Deep space */
  --signal: #00f2ff;         /* Cyber cyan */
  --accent: #7000ff;         /* Quantum purple */
  --text-primary: #e0f0ff;   /* Ice white */
  --glass-bg: rgba(0,242,255,0.03);
  --glow: 0 0 12px rgba(0,242,255,0.3);
}
```

* Glassmorphism panels with backdrop blur
* Scanline background grid
* Neon glows and animated borders
* Responsive from 320px to 4K

---

## 📱 Responsive Behavior

| Breakpoint | Behavior                          |
| ---------- | --------------------------------- |
| < 480px    | Stack action buttons, smaller FAB |
| < 768px    | Textarea height adjusts           |
| > 768px    | Full layout with larger textarea  |
| Any        | Fluid grids with `auto-fit`       |

---

## ♿ Accessibility Features

* `aria-live="polite"` on metrics container
* `aria-label` on icon-only buttons
* `:focus-visible` outlines
* Sufficient color contrast
* Touch targets ≥ 44px
* Safe area insets for notched devices

---

## 🔧 Customization

### Modify Keywords

Edit the `KEYWORDS` array in the script:

```javascript
const KEYWORDS = ['words', 'word', 'text', 'help', ...];
```

### Adjust Reading Speed

```javascript
const READING_SPEED = 200; // words per minute
const SPEAKING_SPEED = 130; // words per minute
```

### Add New Metrics

Extend the `metrics-grid` in HTML and update `analyzeText()`.

---

## 📦 Project Structure

```
word-readability-telemetry/
├── index.html
├── public/
│   └── logo.webp
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing`)
5. Open a Pull Request

Please maintain the single-file architecture and cyberpunk aesthetic.

---

## 📄 License

MIT © [Muhammad Maqsood](https://www.linkedin.com/in/muhammad-mk-nexus)

---

## 🙏 Credits

* Design & Development — Muhammad Maqsood
* Typography — Inter by Rasmus Andersson, JetBrains Mono
* Inspiration — Cyberpunk 2077, Ghost in the Shell

---

## 🐛 Bug Reports

Found a bug? Please open an issue with:

* Device/browser info
* Steps to reproduce
* Expected vs actual behavior

---

## ⭐ Support

If you find this tool useful, please ⭐ star the repository!

---

🔮 **Word & Readability Telemetry — precision text analysis since 2026**

````

---

## 📋 Quick copy-paste for terminal

After creating the README file, run:

```bash
git add README.md
git commit --amend --no-edit
git push -f origin main
# Or if not pushed yet
git push -u origin main
````

Your README is now clean, consistent, and fully aligned with **Word & Readability Telemetry** branding. 🚀
