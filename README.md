<div align="center">

# CSS Animations Showcase

**A curated collection of pure CSS animations demonstrating modern front-end techniques.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-None-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

[Live Demo](#-getting-started) · [Source Code](https://github.com/ngoriest/css-animations-showcase) · [Issues](https://github.com/ngoriest/css-animations-showcase/issues)

</div>

---

## Overview

This project explores the full range of CSS animation capabilities — from subtle hover feedback to complex loading states — using only HTML and CSS. It was built as a structured learning exercise with a focus on writing clean, maintainable animation code without relying on JavaScript or external libraries.

---

## Animations

| Category | Effects |
|---|---|
| **Hover Effects** | Scale transform, color transitions, rotation |
| **Loading Animations** | Spinning circle, bouncing dots, pulse |
| **Text Animations** | Typing effect, glow, wavy hover |
| **Buttons** | Pulse, sliding icon, border glow |

All animations are implemented with CSS `transition` and `@keyframes`. No libraries. No JavaScript.

---

## Getting Started

**Prerequisites:** Any modern browser (Chrome, Firefox, Safari, Edge).

```bash
git clone git@github.com:ngoriest/css-animations-showcase.git
cd css-animations-showcase
open index.html
```

Or simply double-click `index.html` — no build step or local server required.

---

## Project Structure

```
css-animations-showcase/
├── index.html      # Markup and demo layout
├── style.css       # All transitions and keyframe animations
└── README.md       # Project documentation
```

---

## Key Learnings

This project deepened my understanding of several CSS fundamentals:

**Transitions vs. Keyframes** — Transitions handle simple state changes (hover, focus) elegantly. Keyframes are better suited for multi-step, looping, or auto-playing sequences.

**Easing functions** — The difference between `linear`, `ease-in-out`, and a custom `cubic-bezier` is the difference between an animation that looks mechanical and one that feels natural.

**Performance** — Animating `transform` and `opacity` is significantly smoother than animating layout properties like `width` or `margin`, because they don't trigger reflow.

**Staggered delays** — Using `animation-delay` on sibling elements creates coordinated sequences from a single keyframe definition.

---

## AI Prompt Journal

A record of how I used AI assistance throughout the project.

---

**Prompt 1 — Getting Started**
> *"What are some easy CSS animations for beginners?"*

This introduced me to the core concepts: `transition` for interactive state changes, `transform` for visual effects, and `@keyframes` for full animation sequences. A strong foundation to build from.

---

**Prompt 2 — Debugging**
> *"Why isn't my hover effect working?"*

The issue was that `transition` needs explicitly named properties to animate — `transition: all` works but is inefficient, while `transition: transform 0.3s ease` is precise and performant. Small detail, big difference.

---

**Prompt 3 — Loading Spinners**
> *"How can I make loading spinners with pure CSS?"*

Learned the border technique: set three sides of a border to a visible color, one to transparent, then rotate infinitely. Combined with `border-radius: 50%`, this produces a clean spinner with minimal markup.

---

**Prompt 4 — Smoothness & Polish**
> *"How do I make my animations smoother?"*

Discovered that easing functions and staggered `animation-delay` values dramatically improve perceived quality. An animation that starts and ends abruptly feels broken; one with a natural ease feels intentional.

---

## Troubleshooting

| Issue | Solution |
|---|---|
| Animations not playing | Verify browser support; add `-webkit-` prefixes for older browsers |
| Hover effects feel too fast | Aim for `0.2s–0.4s` transition duration — the sweet spot for most UI interactions |
| Layout shifting during animation | Use `transform` instead of animating `width`, `height`, or `margin` |
| Choppy animations | Ensure you're only animating `transform` and `opacity`; add `will-change: transform` if needed |

---

## Resources

- [MDN Web Docs — CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations/Using_CSS_animations)
- [CSS Tricks — Transition](https://css-tricks.com/almanac/properties/t/transition/)
- [Animate.css](https://animate.style/) — Animation reference and inspiration
- [Easings.net](https://easings.net/) — Visual guide to easing functions

---

<div align="center">

Built by [ngoriest](https://github.com/ngoriest)

</div>
