# Pulse Page – SaaS Landing UI (HTML + CSS)

Responsive, animated SaaS landing page built using pure HTML and CSS. Includes hero section, pricing cards with toggle functionality, dark mode support, and container-query-based responsiveness.


---

## 🛠️ Built With

- HTML5 (semantic layout)
- CSS (container queries, custom animations)
- No JavaScript
- No frameworks or libraries

---

## ⚙️ Features

- **Container Queries:**  
  `@container` used to control layout at section scope for modular responsiveness.

- **Hero Section:**  
  Two-column layout with animated image and responsive text blocks.

- **Pricing Cards with Toggle:**  
  Pure CSS `:has()` selector used to switch between Monthly and Yearly prices.

- **Dark Mode:**  
  Enabled via `prefers-color-scheme: dark`.

- **Responsive Typography & Layout Units:**  
  Layouts and text scale using `clamp()`, `cqi`, and `cqh`.

- **CSS Animations:**  
  Includes `fadeInL`, `fadeInR`, `fadeUp`, and `glow` on hover.

---

## 📱 Responsive Behavior

| Viewport Range       | Layout Behavior                              |
|----------------------|----------------------------------------------|
| `< 400px`            | Single-column layout                         |
| `400px – 768px`      | Vertical stack, image and cards adapt        |
| `768px – 1000px`     | Two-column layout with fluid card grid       |
| `> 1000px`           | Full three-column pricing layout             |

Card/image sizing controlled with `cqi/cqh` and grid templates scoped to their containers.

---

## 🧪 CSS System

- CSS Custom Properties for:
  - Color (`--clr-*`)
  - Padding/gap/radius (`--pad`, `--gap`, `--rad`)
- Utility class patterns (`.hero-text`, `.card-container`, `.price-toggle`)
- Modular animations and delays using `:nth-child()`

---

## 🚀 Live Demo
👉 [View Live Demo](https://pulse-page.vercel.app)


---

## 🧼 Code Quality

- Logical sectioning of layout vs presentation styles
- No repetition across breakpoints
- Scoped container-query rules to minimize global CSS bloat
- Animations defined and reused cleanly across sections

---
