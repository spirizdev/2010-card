<div align="center">

# 🌸 20/10 Greeting Card

**A tiny interactive card for Vietnamese Women's Day.**
Click, watch the message decode itself, and let the hearts fly.

[![Live Demo](https://img.shields.io/badge/Live-Demo-ff69b4?style=for-the-badge)](https://meow.spiriz.id.vn)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
![No Build](https://img.shields.io/badge/Build-None-success?style=for-the-badge)

<img src="https://github.com/user-attachments/assets/138c1d14-2078-405d-8512-1a38e95634e1" alt="Preview" width="100%" />

</div>

---

## ✨ Highlights

| | Feature | Description |
|---|---|---|
| 💌 | **Letter decoding** | Scrambled letters fly in and resolve into your message on click |
| 🪟 | **Glassmorphism** | Frosted-glass card with soft glow and backdrop blur |
| 💖 | **Particles** | Floating hearts, twinkling stars, click bursts and a cursor trail |
| 🎵 | **Ambient music** | Background track at a gentle, low volume |
| 📊 | **Visit counter** | Live visitor count via CounterAPI |
| 📱 | **Responsive** | Looks good on phones, tablets and desktops |

## 🚀 Quick Start

No build tools, no dependencies.

```bash
git clone https://github.com/spirizdev/2010-card.git
cd 2010-card
```

Then open `index.html` in your browser, or use the **Live Server** extension in VS Code.

## 🎀 Make It Yours

Everything personal lives in one place: the `CFG` object inside `index.html`.

```javascript
const CFG = {
  l1: "CHÚC MỪNG 20/10",            // top line of the decoded title
  l2: "BÉ MÈO CUTE 🐱",             // second line of the title
  name: "Bé Mèo Cute 🐾",           // recipient name
  intro: "Nhân ngày 20/10, chúc cậu luôn rạng rỡ, xinh tươi...",
  wishes: [
    // [emoji, title, description]
    ["🌸", "Rạng rỡ xinh tươi", "Lúc nào cũng siêu cute và yêu đời."],
  ],
  quote: "Cảm ơn cậu vì đã luôn mang năng lượng tích cực...",
  sign: "— Một người bạn luôn nghĩ đến cậu 🌿",
};
```

> 💡 Add as many entries to `wishes` as you like, one per card.

## 🌐 Live Demo

See it live at **[meow.spiriz.id.vn](https://meow.spiriz.id.vn)** 🐱

Want your own? Fork the repo, edit `CFG` in `index.html`, then deploy to any static host (GitHub Pages, Vercel, Netlify, Cloudflare Pages...).

Send the link to someone special. 💝

## 🧰 Tech Stack

- **HTML5 + CSS3**: Grid, Flexbox, keyframes, backdrop-filter
- **Vanilla JavaScript (ES6+)**: `requestAnimationFrame`, DOM/Canvas animation
- **Google Fonts**: Playfair Display, Dancing Script, Be Vietnam Pro
- **CounterAPI**: visit tracking

## 📜 License

Released under the [MIT License](LICENSE). Free to use, remix and share.

## 💌 Credits

Made with ❤️ by [@spiriz](https://ayo.so/aowvn)

<div align="center">

⭐ If you like this card, leave a star!

</div>
