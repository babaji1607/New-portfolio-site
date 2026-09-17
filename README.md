# Mohit Ashliya — Premium Portfolio Website

A **$50,000-tier** portfolio website for a DevOps & Mobile App Developer, built with Astro, Tailwind CSS v4, and GSAP animations.

> ✨ Every section features cinematic scroll-driven animations, interactive elements, and premium micro-interactions that set this apart from generic portfolio templates.

---

## 🎬 What Makes This Premium

### Hero Section
- **Completed Headline Statement** — *"I build & deploy systems that scale with ease."* with staggered GSAP split-text reveal
- **Direct Connect CTA Button** — *"Let's Connect Directly"* button with hover scale effects scrolling directly to contact
- **Background Video Audio & Sound Control** — Default video audio enabled with interactive top-left **SOUND ON / SOUND OFF** toggle button
- **Cinematic video background** with dynamic gradient overlay and SVG grain/noise texture for a film-quality look
- **Cursor-following ambient light** — a soft gradient orb follows the mouse across the hero
- **Scroll-driven parallax** — video subtly zooms in (1.0 → 1.15) as you scroll while text moves at a different rate
- **Animated scroll indicator** — pulsing line at the bottom that fades out on scroll
- **Role badges** — "DevOps Engineer", "Mobile Developer", "Cloud Architect" slide in with spring physics
- **Global scroll progress bar** — thin line at the top filling as you scroll the entire page

### Projects Section (Horizontal Scroll Gallery)
- **Pinned horizontal scroll** — projects scroll horizontally as you scroll vertically, using GSAP ScrollTrigger with `scrub` and `snap`
- **Full-viewport project cards** with large imagery and parallax image movement within each card
- **Massive outlined project numbers** (01, 02, 03, 04) in stroke typography
- **Staggered tech stack tags** that animate in with spring easing
- **Live progress indicator** — shows current project number / total, updating in real-time
- **Animated "View Project" links** with text-swap hover effect

### Skills Section
- **Dual-direction infinite marquee** — two rows of skill pills scrolling in opposite directions, powered by GSAP (not CSS animation) with gradient edge masks
- **Clean uniform 3-column grid** — structured layout with tilt micro-interactions on hover
- **Stat counters** — numbers that count up (8+ years, 40+ projects) when scrolled into view

### Dedicated Experience Section
- **Highlighted timeline view** featuring career progression from 2021 to Present
- **Large year indicators** with "Now" badge for current role
- **Scroll-triggered entry animations** with scale-pop effect on year numbers
- **Structured role titles & detailed descriptions**

### Creative Testimonials Section
- **Dark-themed cards** (`#111`) with subtle background number watermarks (`01`, `02`, `03`)
- **5-Star Rating Indicators** & key metric badges (*"99.99% Uptime Achieved"*, *"2x App Performance"*, *"40% Cost Reduction"*)
- **Quotes from VP of Engineering, Head of Product, and CTO**
- **ScrollTrigger staggered reveal animations**

### About Section (Dark Theme)
- **Cohesive dark styling** (`#0a0a0a`) seamlessly matching the site palette
- **Parallax profile photo** with subtle dark gradient overlay for depth
- **Floating detail cards** ("AWS Certified", "50+ Projects", "3+ Years") with subtle continuous float
- **Restrained typography & quote callout** — clean, confident, and readable without distracting motion

### Footer / Contact
- **Massive word-by-word CTA** — "Let's build something together" in ~10vw text, revealing line by line on scroll
- **Magnetic button** — the "Get in Touch" circle follows your cursor when nearby, with elastic snap-back
- **Rolling hover links** — email, GitHub, LinkedIn links with text-swap and underline animations
- **Live clock** — displays your current local time, updating every second
- **Giant parallax name** — "MOHIT" in 20vw outlined stroke text with scroll parallax

### Creative Overlay Navigation
- **Fixed top-right trigger button** with glassmorphism styling
- **Full-page panel wipe transition** on open/close powered by GSAP timelines
- **Large, numbered nav links** (01 Home, 02 Projects, 03 Skills, 04 Experience, 05 Testimonials, 06 About, 07 Contact) with hover displacement
- **Hamburger icon morphs into 'X' close button**
- **Keyboard navigation support (Escape to close)**

### Premium Extras
- **Page preloader** — name reveal + progress bar animation that masks the page during load
- **Custom cursor** — dot + ring cursor that follows the mouse at different speeds, with interactive scale states on hoverable elements
- **Custom scrollbar** — minimal 6px translucent scrollbar
- **Selection color** — branded blue selection highlight

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| **Astro 7.x** | Static site generator with component islands |
| **Tailwind CSS v4** | Utility-first CSS with `@tailwindcss/vite` plugin |
| **GSAP 3** | Professional-grade animation library |
| **ScrollTrigger** | Scroll-linked animations, pinning, scrubbing |
| **Inter + Space Grotesk** | Typography (Google Fonts) |

---

## 📂 Project Structure

```
src/
├── components/
│   ├── Hero.astro           # Video hero with sound toggle, complete line & CTA
│   ├── Projects.astro       # Horizontal scroll gallery with pinned viewport
│   ├── Skills.astro         # Marquee ticker + clean 3-col skill cards
│   ├── Experience.astro     # Dedicated highlighted career timeline
│   ├── Testimonials.astro   # Creative client feedback & metrics grid
│   ├── About.astro          # Dark theme profile & bio
│   ├── Footer.astro         # Magnetic CTA + giant parallax name
│   ├── FloatingNav.astro    # Full-page creative overlay navigation
│   ├── Preloader.astro      # Page load animation
│   └── CustomCursor.astro   # Custom cursor with interactive states
├── layouts/
│   └── Layout.astro         # Base layout with fonts, GSAP CDN, global styles
├── pages/
│   └── index.astro          # Page composition
└── styles/
    └── global.css           # Tailwind import
```

---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```
