# 🌸 Vietnamese Women's Day Interactive Greeting Card (20/10)

An aesthetic, interactive web-based greeting card built to celebrate **Vietnamese Women's Day (October 20th)**. It features dynamic letter-decoding animations, floating heart particle effects, smooth glassmorphism design, custom cursor tracking, and background music integration.

<p align="center">
  <img src="https://github.com/user-attachments/assets/138c1d14-2078-405d-8512-1a38e95634e1" alt="Preview" width="100%" />
</p>

---

## ✨ Features

- 💖 **Letter Decoding Effect:** Dynamic scramble and fly-in text animations that decode the secret message upon clicking.
- 🎨 **Glassmorphism UI:** Modern, responsive card layout designed with CSS backdrop filters and soft glowing effects.
- 🐾 **Interactive Particle System:** Floating hearts, star twinkling, explosion bursts, and a custom mouse trail cursor.
- 🎵 **Background Music:** Seamless audio playback integration with low ambient volume.
- 📊 **Visit Counter:** Integrated visitor tracking powered by `CounterAPI`.
- 📱 **Fully Responsive:** Optimized for both mobile devices and desktop screens.

---

## 🛠️ Built With

- **HTML5 & Pure CSS3** (CSS Grid, Flexbox, Keyframes, Animations, Glassmorphism)
- **Vanilla JavaScript** (ES6+, `requestAnimationFrame`, Canvas/DOM animations)
- **Google Fonts** (*Playfair Display*, *Dancing Script*, *Be Vietnam Pro*)
- **CounterAPI** (for real-time visit tracking)

---

## 🚀 Getting Started

No build tools or external installation required!

1. **Clone the repository:**

```bash
   git clone https://github.com/spirizdev/vietnamese-womens-day-greeting.git
   cd vietnamese-womens-day-greeting
```

2. **Run locally:**
   - Open `index.html` directly in any modern web browser.
   - Alternatively, serve it using the VS Code **Live Server** extension.

---

## ⚙️ Customization

To customize the message, recipient name, or wishes, edit the `CFG` object inside `index.html`:

```javascript
const CFG = {
  l1: "CHÚC MỪNG 20/10",
  l2: "BÉ MÈO CUTE 🐱",
  name: "Bé Mèo Cute 🐾",
  intro: "Nhân ngày 20/10, chúc cậu luôn rạng rỡ, xinh tươi...",
  wishes: [
    ["🌸", "Rạng rỡ xinh tươi", "Lúc nào cũng siêu cute và yêu đời."],
    // Add or modify wishes here
  ],
  quote: "Cảm ơn cậu vì đã luôn mang năng lượng tích cực...",
  sign: "— Một người bạn luôn nghĩ đến cậu 🌿",
};
```

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 💌 Credits

Made with ❤️ by [@spiriz](https://ayo.so/aowvn).
