# Giga 🌌

> **AI Enterprise Platform** — Intelligence, vast as the night sky.

![Giga Preview](./preview.png)

---

## 🏷️ Tags

`AI / Enterprise SaaS` &nbsp; `Industry: Developer Tools` &nbsp; `Target: Engineering Teams & Tech Startups`

---

## 📌 About the Project

**Giga** is a landing page for an enterprise AI platform designed with a **"deep night, mountain vista"** aesthetic — blending cosmic visual tranquility with the sharpness of technical information.

The platform is tailored for **engineering teams, tech leads, and decision-makers** in enterprises who require serious AI solutions: ranging from agent builders, model gateways, and observability dashboards, to zero-trust security. All packed into a single platform that feels calming, precise, and enterprise-ready.

This project was built purely using **HTML, CSS, and Vanilla JavaScript** — zero frameworks, zero UI libraries — utilizing a consistent design system driven by CSS custom properties from the `variables.css` and `DESIGN.md` files.

---

## ❗ Problems Solved

### 1. Difficulty Building Trust in the Enterprise AI Category
Enterprise AI platforms often appear overly technical or overly generic. Decision-makers — especially CTOs and Staff Engineers — find it hard to feel a sense of "trust" from standard, run-of-the-mill interfaces. They need to feel that the product is **mature, stable, and reliable at scale**.

### 2. Overwhelming Information Lacking Clear Hierarchy
Products with an extensive list of technical features (model routing, agent builder, observability, security compliance, etc.) often present all information simultaneously. This leaves visitors confused: _"Who is this actually for, and what should I do first?"_

### 3. Lack of a Distinct Visual Identity
The majority of AI platforms look identical — clean white or dark purple with generic gradients. There is an absence of visual character that makes the product memorable after the browser tab is closed.

### 4. Weak First-Page Conversions
Many AI landing pages fail to turn first-time visits into tangible actions (signing up, booking a demo, etc.) because the core message isn't sharp enough and the CTAs fail to stand out visually and positionally.

### 5. Hero Sections Heavily Dependent on Heavy Assets
Most premium landing pages rely heavily on photos, video backgrounds, or heavy illustrations to build a strong visual impact. This slows down page loading speeds and increases dependency on external assets.

---

## ✅ Solutions Provided

### Consistent Dark Premium Design System
The entire page leverages **design tokens** from `variables.css` — colors, typography, spacing, border-radius, and shadows are all strictly defined as CSS custom properties. This yields a cohesive look and feel from header to footer, giving the impression of a well-engineered product.

The primary tokens used include:

| Token                      | Value                  | Function                                     |
| -------------------------- | ---------------------- | -------------------------------------------- |
| `--color-obsidian`         | `#000000`              | Main background                              |
| `--color-ghost`            | `#ffffff`              | Primary text                                 |
| `--color-ember-glow`       | `#fe2c02`              | Red accent — CTAs, labels, ticker dots       |
| `--color-growth-green`     | `#49de80`              | Positive indicators — badges, checks, metrics|
| `--color-night-sky`        | `#161717`              | Secondary surface — cards, CTA section       |
| `--color-cosmic-dust`      | `#8a8f98`              | Description / caption text                   |
| `--gradient-subtle-violet` | `linear-gradient(...)` | Product card — Agent Studio                  |
| `--gradient-soft-mint`     | `linear-gradient(...)` | Product card — Analytics Hub                 |
| `--gradient-sky-blue`      | `linear-gradient(...)` | Product card — Model Gateway                 |

### Immersive Hero Section — Pure CSS, Zero Image Assets
Instead of photos or video backgrounds, the hero section is constructed **entirely via CSS and inline SVGs**:

- **Layered mountain silhouettes** — 3 SVG path layers with distinct gradients creating visual depth.
- **Starry night sky** — 17 star elements manually positioned using `radial-gradient`.
- **Aurora effect** — an ellipse `radial-gradient` placed at the top of the sky.
- **Noise texture overlay** — an SVG `feTurbulence` filter used to achieve a subtle texture.

The result: an immersive and on-brand visual experience **without loading a single image file**.

### Strategic Information Hierarchy
The page structure is purposefully engineered to follow the logical decision-making funnel of B2B users:


```

Sticky Navbar (navigation + CTA always accessible)
↓
Hero (first impression — positioning + main CTA)
↓
Ticker Marquee (passive trust signals — features & certifications)
↓
Metrics Bar (numerical proof — 12B+ tokens, 340ms, 99.99% uptime)
↓
Features Grid (detailed breakdown of 6 core capabilities)
↓
Product Showcase (interface visualization + benefit list)
↓
Product Cards (3 solutions per category with gradient branding)
↓
Testimonials (social proof from engineering & CTO personas)
↓
CTA Banner (final push to contact sales)
↓
Footer (complete navigation + branding)

```

Each section serves one distinct communication goal, nothing more.

### Expressive Typography — Light Font with Negative Tracking
Utilizing **Inter weight 300** with a `letter-spacing: -0.03em` for large headings. The result delivers a sense of sophistication and calm — not shouting, but speaking with authority. A visual signature commonly found across premium brands like Linear, Vercel, and Anthropic.

### Three-Variant Button System
Aligned with the design spec using `border-radius: 1000px` as a visual signature:

| Variant            | Background          | Usage                                   |
| ------------------ | ------------------- | --------------------------------------- |
| **Ghost Pill**     | Transparent + border| Secondary actions (Log in)              |
| **Primary Filled** | White over dark     | Primary CTA (Get started)               |
| **Dark Filled**    | Night sky `#161717` | CTAs positioned in lighter sections     |

### Ticker Marquee — Passive Social Proof
An auto-scrolling text bar showcasing key features and compliance standards (SOC 2 Type II, 99.99% Uptime, Edge Deployment, etc.). Visitors subconsciously absorb these details — establishing credibility without interrupting the main reading flow.

### Scroll Animations with Intersection Observer
All cards leverage the `.fade-up` class triggered by the **Intersection Observer API** — entirely free of external JavaScript libraries. Smooth transition entry animations trigger as elements cross into the viewport, utilizing staggered `transition-delay` values between grid cards.

---

## 🎨 Design Decisions

| Aspect               | Decision                          | Reason                                         |
| -------------------- | --------------------------------- | ---------------------------------------------- |
| **Style**            | Deep black + red/green accents    | Premium, bold, distinct from competitors       |
| **Primary font**     | Inter 300 (light)                 | Sophistication without sacrificing legibility  |
| **Heading tracking** | `-0.03em`                         | Premium brand visual signature                 |
| **Button shape**     | Pill `border-radius: 1000px`      | Consistent visual identity                     |
| **Hero background**  | Pure CSS + SVG                    | Zero image dependency, fast load times         |
| **Product cards**    | Bright gradients on a dark page   | High contrast, easily distinguishable          |
| **Primary accent**   | Ember glow `#fe2c02`              | Energetic, memorable, non-generic              |

**Color Palette:**

| Name         | Hex       | Function                    |
| ------------ | --------- | --------------------------- |
| Obsidian     | `#000000` | Main background             |
| Ghost        | `#ffffff` | Text & primary buttons      |
| Ember Glow   | `#fe2c02` | Primary accent & CTAs       |
| Growth Green | `#49de80` | Positive indicators         |
| Night Sky    | `#161717` | Card surfaces & CTA section |
| Cosmic Dust  | `#8a8f98` | Secondary text / description|
| Pebble Gray  | `#969696` | Tertiary text / nav links   |

---

## 🛠️ Tech Stack

| Technology                    | Usage                                                           |
| ----------------------------- | --------------------------------------------------------------- |
| **Semantic HTML5**            | `nav`, `section`, `footer` for accessibility & SEO              |
| **CSS Custom Properties**     | Design token system — all visual variables are pre-defined      |
| **CSS Grid**                  | Layout for features (3 col), products (3 col), footer (4 col)   |
| **CSS Flexbox**               | Navbar, hero actions, metric items, testimonial author layouts  |
| **Inline SVG**                | Layered mountain landscape illustrations, feature icons         |
| **CSS Gradients**             | Hero sky, product cards, aurora, stars, dividers                |
| **CSS Keyframes**             | Ticker marquee scroll, hero badge pulse animation               |
| **Intersection Observer API** | Scroll-triggered fade-up animations                             |
| **Google Fonts**              | Inter + Inter Display                                           |

> **Zero framework. Zero UI library. Zero build process.** Launch `index.html` straight inside your browser.

---

## ✨ Key Features of the Landing Page

- 🌄 **CSS-only mountain hero** — layered night landscape completely devoid of image assets.
- ⭐ **Starfield background** — manually generated stars using `radial-gradient`.
- 📡 **Live badge** featuring a green pulsing animation inside the hero section.
- 📰 **Ticker marquee** automatically scrolling through core features & certifications.
- 📊 **Metrics bar** — 4 key metrics highlighted with ember glow accents.
- 🃏 **6 feature cards** utilizing hover states and top-line gradients.
- 🖥️ **Product showcase** — high-fidelity mock UI screens complete with floating stat badges.
- 🎨 **3 gradient product cards** — violet / mint / sky blue styles following design tokens.
- 💬 **3 testimonial cards** — engineering, AI lead, and CTO personas.
- 💡 **Sticky navbar** with premium glassmorphism backdrop blur effects.
- 📱 **Fully responsive** — adaptive 3 col → 2 col → 1 col breakpoint system.

---

## 📁 File Structure

```

giga/
├── index.html          # Entire page (HTML + Inline CSS + JS)
├── css                 # Design tokens — color, typography, spacing, radius
│    └── login.css
│    └── page.css
│    └── style.css
├── page                 # Page focus (login, register, blog, pricing, contact)
│    └── login.html
│    └── register.html
│    └── blog.html
│    └── pricing.html
│    └── contact.html
├── preview.png         # Screenshot for this README file
└── README.md           # This documentation file

```

---

## 🌐 Live Demo

[🔗 [View Live Demo](https://giga-azure.vercel.app/)](#) 

---

## 💡 Key Takeaways from This Project

1. **Design tokens are the foundation** — with organized CSS custom properties, adjustments to spacing or coloring can be executed from a single locus and immediately propagate globally.
2. **Modern CSS is incredibly powerful** — immersive, multi-layered mountain vistas can be rendered flawlessly without forcing asset image downloads.
3. **Visual hierarchy = business hierarchy** — section mapping isn't purely an aesthetic choice; it's a strategic sequence influencing user acquisition funnel paths.
4. **Restraint builds premium appeal** — exercising disciplined boundaries with color and motion delivers a significantly more sophisticated product finish.
5. **Zero dependency = full control** — bypassing frameworks means stripping out unaccounted "magic" formulas. Every line of CSS works for a specific, transparent purpose.

---

## 👤 Developer

**Putu Dio** — Web Developer

- 🌐 Portfolio: [Coming Soon](#)
- 💼 LinkedIn: [[linkedin.com/in/putudiokenneta](https://www.linkedin.com/in/putu-dio-kenneta-09818440b/)]
- 🐙 GitHub: [[github.com/PutuDio](https://github.com/PutuDio)]

---

## 📄 License

This project is open-source and free to be used as an educational learning reference.

---

<p align="center">
  <em>"Intelligence, vast as the night sky."</em><br/>
  Crafted with ☕, multiple iterations, and a rock-solid, unified design system.
</p>

```
