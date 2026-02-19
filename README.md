<div align="center">

# ✨ CSS Animations Showcase

**A beginner-friendly collection of pure CSS animations — no JavaScript required.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![No JS](https://img.shields.io/badge/JavaScript-0%25-brightgreen?style=for-the-badge)

[View Demo](#-quick-start) · [Report Bug](https://github.com/ngoriest/css-animations-showcase/issues) · [Give Feedback](https://github.com/ngoriest/css-animations-showcase/issues)

</div>

---

## 📖 About

This project is a hands-on exploration of CSS animations built while learning front-end development. Every effect — from loading spinners to glowing text — is powered entirely by CSS transitions and keyframes.

---

## 🎬 Animations Included

| Category | Effects |
|---|---|
| **Hover Effects** | Scale on hover, color transitions, rotation |
| **Loading Animations** | Spinning circle, bouncing dots, pulsing effect |
| **Text Animations** | Typing effect, glowing text, wavy text |
| **Animated Buttons** | Pulse, sliding icon, border glow |

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone git@github.com:ngoriest/css-animations-showcase.git

# Navigate into it
cd css-animations-showcase

# Open in browser
open index.html
```

> Or just double-click `index.html` — it works in any modern browser with no setup needed.

---

## 📁 Project Structure

```
css-animations-showcase/
├── index.html      # Main HTML file
├── style.css       # All animations live here
└── README.md       # You are here
```

---

## 🧠 What I Learned

- CSS is powerful enough to create complex, polished animations on its own
- `@keyframes` give you precise, frame-by-frame control over motion
- Transitions make interfaces feel alive with just one line of CSS
- Easing functions (`ease-in-out`, `cubic-bezier`) are the secret to smooth motion
- `box-sizing: border-box` will save you from a lot of layout headaches

---

## 🤖 AI Prompt Journal

A log of the key prompts that helped me build this project.

**Getting started**
> *"What are some easy CSS animations for beginners?"*

Learned the core trio: `transition`, `transform`, and `@keyframes`.

**Debugging**
> *"Why isn't my hover effect working?"*

Discovered I needed to define the properties to transition explicitly (e.g., `transition: transform 0.3s ease`).

**Loading spinners**
> *"How can I make loading spinners with pure CSS?"*

Learned the border trick — making three sides of a border one color and one side transparent, then rotating it.

**Smoothness**
> *"How do I make my animations smoother?"*

Discovered easing functions and `animation-delay` for staggered effects.

---

## 🐛 Troubleshooting

**Animations not playing** — Check browser compatibility. All modern browsers support CSS animations, but older ones may need vendor prefixes (`-webkit-`).

**Hover effects too fast** — Adjust the `transition-duration`. A value around `0.3s` tends to feel natural.

**Layout breaking** — Add `box-sizing: border-box` to your CSS reset.

---

## 📚 Resources

- [MDN — Using CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations/Using_CSS_animations)
- [CSS Tricks — A Guide to CSS Transitions](https://css-tricks.com/almanac/properties/t/transition/)
- [Animate.css](https://animate.style/) — Great source of animation inspiration

---

<div align="center">

Made with 💙 and a lot of `@keyframes`

</div>
