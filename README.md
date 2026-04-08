
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=700&amp;size=22&amp;pause=1000&amp;color=2B3990&amp;center=true&amp;vCenter=true&amp;multiline=true&amp;width=750&amp;height=60&amp;lines=Vanilla+HTML+%7C+CSS+%7C+JavaScript+%E2%80%94+No+Frameworks;Sticky+Header+%7C+Image+Zoom+Carousel+%7C+Responsive;Pixel-Perfect+Figma+Implementation" alt="Typing SVG" />

<br/>
<br/>
<br/>

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Flexbox%20%26%20Grid-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Figma](https://img.shields.io/badge/Figma-Design%20Source-F24E1E?style=for-the-badge&amp;logo=figma&amp;logoColor=white)](https://www.figma.com/design/DOv07H7C2tA5UrVLhmfwfW/Gushwork-Assignment)

[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-3DDC84?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white)](#)
[![Accessibility](https://img.shields.io/badge/Accessibility-ARIA%20Ready-FF6B6B?style=for-the-badge)](#)
[![Performance](https://img.shields.io/badge/Performance-Optimized-brightgreen?style=for-the-badge)](#)
[![Assignment](https://img.shields.io/badge/Gushwork-Assignment-2B3990?style=for-the-badge)](#)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

---

## 📋 Table of Contents

<div align="center">

| # | Section |
|---|---------|
| 1 | [🌟 About the Project](#-about-the-project) |
| 2 | [✨ Features](#-features) |
| 3 | [🏗️ Page Architecture](#️-page-architecture) |
| 4 | [🛠️ Tech Stack](#️-tech-stack) |
| 5 | [📁 Project Structure](#-project-structure) |
| 6 | [🚀 Getting Started](#-getting-started) |
| 7 | [📱 Responsive Breakpoints](#-responsive-breakpoints) |
| 8 | [🎨 Design System](#-design-system) |
| 9 | [⚙️ Key Interactions](#️-key-interactions) |
| 10 | [👨‍💻 Developer](#-developer) |

</div>

---

## 🌟 About the Project

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=16&amp;pause=1000&amp;color=2B3990&amp;center=false&amp;vCenter=true&amp;width=700&amp;lines=Pixel-perfect+Figma+implementation+for+Mangalam+HDPE+Pipes...;Built+with+pure+Vanilla+HTML%2C+CSS+%26+JavaScript!" alt="About" />

**Mangalam HDPE Pipes** is a fully responsive product landing page built as part of the **Gushwork Frontend Assignment**. The page showcases premium HDPE pipe products with a modern, professional design—faithfully recreating every detail from the Figma specification.

The implementation uses **zero frameworks or libraries**—only semantic HTML5, modern CSS (Flexbox/Grid), and vanilla JavaScript for all interactivity.

### 🎯 Assignment Objectives Covered

- ✅ Pixel-perfect Figma implementation (node: `490-8785`)
- ✅ Sticky header that appears on scroll-down, disappears on scroll-up
- ✅ Interactive image carousel with zoom preview on hover
- ✅ Fully responsive across mobile, tablet, and desktop
- ✅ Clean, commented-free, well-organized code
- ✅ Semantic HTML5 with ARIA attributes for accessibility
- ✅ Smooth animations and CSS transitions throughout

---

## ✨ Features

<div align="center">

| Feature | Description | Status |
|---------|-------------|--------|
| 🔝 **Sticky Header** | Appears when scrolling past hero fold, with smooth slide animation | ✅ Done |
| 🖼️ **Image Carousel with Zoom** | Magnifying lens on hover shows zoomed preview panel to the right | ✅ Done |
| 📐 **Pixel-Perfect Design** | Matches Figma specs — colors, fonts, spacing, shadows | ✅ Done |
| 📱 **Full Responsiveness** | Tested on 320px mobile to 1600px desktop | ✅ Done |
| ⚙️ **Manufacturing Stepper** | 8-step process carousel with tab navigation and badges | ✅ Done |
| 📊 **Tech Specs Table** | Dark-theme table with download modal | ✅ Done |
| 🗂️ **FAQ Accordion** | Smooth expand/collapse with rotating chevron icon | ✅ Done |
| 💬 **Testimonials Carousel** | Drag/swipe-enabled carousel | ✅ Done |
| 📋 **Contact Form** | Validated contact form with country code selector | ✅ Done |
| 🏷️ **Application Cards Carousel** | Horizontal scroll carousel with navigation arrows | ✅ Done |
| 📩 **Modals** | Brochure download & custom quote modals with focus trapping | ✅ Done |
| 🦶 **Multi-column Footer** | Responsive 4-column layout with social links | ✅ Done |

</div>

---

## 🏗️ Page Architecture

```
┌─────────────────────────────────────────────────────────┐
│                     STICKY NAVBAR                        │
│  Logo │ About Us │ Products ▾ │ Contact Us              │
└─────────────────────────────────────────────────────────┘
                          │
┌─────────────────────────▼───────────────────────────────┐
│               MANUFACTURING STICKY BAR                   │
│  (Appears when Manufacturing section is in viewport)     │
│  [Thumbnail] Product Title │ Price │ [Get Custom Quote]  │
└─────────────────────────────────────────────────────────┘
                          │
┌─────────────────────────▼───────────────────────────────┐
│                    HERO SECTION                          │
│  ┌──────────────────┐  ┌────────────────────────────┐  │
│  │  Image Carousel  │  │  BIS / ISO / CE Badges      │  │
│  │  (with zoom)     │  │  Product Title (H1)         │  │
│  │                  │  │  Feature List               │  │
│  │  [← Prev][Next→] │  │  Pricing Card               │  │
│  │  [Thumbnails]    │  │  [Get Quote] [Tech Specs]   │  │
│  └──────────────────┘  └────────────────────────────┘  │
└─────────────────────────────────────────────────────────┘
         │
         ├── TRUST LOGOS (auto-scroll on mobile)
         ├── TECHNICAL SPECS (dark section + table)
         ├── BUILT TO LAST (6-card features grid)
         ├── FAQ ACCORDION + CATALOGUE FORM
         ├── VERSATILE APPLICATIONS (horizontal scroll chips)
         ├── MANUFACTURING PROCESS (8-step stepper)
         ├── TESTIMONIALS (drag carousel)
         ├── PRODUCT PORTFOLIO (3 cards + expert CTA)
         ├── RESOURCES & DOWNLOADS
         ├── CONTACT FORM SECTION (ready to submit)
         └── FOOTER (4 columns + bottom bar)
```

---

## 🛠️ Tech Stack

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

### Languages

<p>
  <img src="https://img.shields.io/badge/HTML5-Semantic%20Elements-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-Flexbox%20%26%20Grid-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-ES6%2B%20Vanilla-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript"/>
</p>

### Design & Fonts

<p>
  <img src="https://img.shields.io/badge/Figma-Design%20Reference-F24E1E?style=for-the-badge&amp;logo=figma&amp;logoColor=white" alt="Figma"/>
  <img src="https://img.shields.io/badge/Google%20Fonts-Urbanist-4285F4?style=for-the-badge&amp;logo=google-fonts&amp;logoColor=white" alt="Urbanist"/>
  <img src="https://img.shields.io/badge/Google%20Fonts-Instrument%20Serif-4285F4?style=for-the-badge&amp;logo=google-fonts&amp;logoColor=white" alt="Instrument Serif"/>
</p>

### Browser APIs Used

<p>
  <img src="https://img.shields.io/badge/IntersectionObserver-Sticky%20Bar-orange?style=for-the-badge" alt="IntersectionObserver"/>
  <img src="https://img.shields.io/badge/Pointer%20Events-Zoom%20Lens-blue?style=for-the-badge" alt="Pointer Events"/>
  <img src="https://img.shields.io/badge/CSS%20Custom%20Props-Design%20Tokens-purple?style=for-the-badge" alt="CSS Custom Props"/>
</p>

### Assets

<p>
  <img src="https://img.shields.io/badge/Cloudinary-Product%20Images-3448C5?style=for-the-badge&amp;logo=cloudinary&amp;logoColor=white" alt="Cloudinary"/>
  <img src="https://img.shields.io/badge/SVG%20Icons-15%20Icons-yellow?style=for-the-badge" alt="SVG Icons"/>
</p>

</div>

---

## 📁 Project Structure

```
Mangalam-HDPE-Pipes/
│
├── 📄 index.html              # Main HTML file — all page sections
├── 📄 styles.css              # Complete stylesheet (3900+ lines)
├── 📄 script.js               # All JavaScript interactions
├── 📄 README.md               # This file
│
└── 📂 public/
    ├── 🖼️  hero_bg.png         # Subtle textured background pattern
    │
    ├── 📂 assets/             # Figma-exported PNG assets
    │   ├── hero-fold-v2.png
    │   ├── Frame 2147224*.png  (section references)
    │   ├── Noise & Texture.png
    │   └── ...
    │
    └── 📂 svgs/               # Icon SVG files (15 icons)
        ├── bag.svg            # Feature icon
        ├── pin.svg            # Feature icon
        ├── box.svg            # Feature icon
        ├── set.svg            # Feature icon
        ├── tag.svg            # List bullet
        ├── right.svg          # Arrow icon
        ├── phone.svg          # CTA phone icon
        ├── comma.svg          # Testimonial quote mark
        ├── mail.svg           # Footer contact
        ├── call.svg           # Footer contact
        ├── MapPinLine.svg     # Footer location
        ├── Headset.svg        # Footer support
        ├── linkedin.svg       # Social link
        ├── x.svg              # Social link (Twitter/X)
        └── insta.svg          # Social link
```

---

## 🚀 Getting Started

### Prerequisites

```bash
# No installation required — pure HTML/CSS/JS!
# Just a modern browser (Chrome, Firefox, Safari, Edge)
```

### Running Locally

```bash
# Option 1: Open directly in your browser
start index.html

# Option 2: Use VS Code Live Server (recommended)
# Install "Live Server" extension, then right click index.html and choose "Open with Live Server"

# Option 3: Use Python's built-in HTTP server
python -m http.server 5500
# Then open: http://localhost:5500

# Option 4: Use Node.js serve
npx serve .
# Then open: http://localhost:3000
```

> [!TIP]
> Use VS Code with the **Live Server** extension for the best development experience. Hot reload works automatically on file save.

---

## 🚀 Deploying To GitHub Pages

This project is a static site, so GitHub Pages works well once the asset paths are relative. That is already fixed in `index.html` and `styles.css`.

### Publish Steps

1. Push the repository to GitHub.
2. Open the repo on GitHub and go to `Settings` > `Pages`.
3. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
4. Select the branch you want to publish from, usually `main`, and set the folder to `/root`.
5. Save the settings and wait for GitHub to build the site.
6. Open the Pages URL GitHub shows after deployment completes.

### Important Notes

- Keep asset references relative, like `public/svgs/right.svg`, not `/public/svgs/right.svg`.
- If you add new images or icons, place them under `public/` so they publish with the site.
- If your repo name changes, GitHub Pages still works because this setup does not depend on a hard-coded base path.

### Optional Local Check

Before deploying, verify the site with a local server instead of opening the HTML file directly. That matches how GitHub Pages serves the project.

---

## 📱 Responsive Breakpoints

| Breakpoint | Range | Layout |
|------------|-------|--------|
| 📱 Mobile | `≤ 768px` | Single column, stacked hero, full-width buttons |
| 📲 Tablet | `769px – 1024px` | Two-column grid, collapsed carousel |
| 🖥️ Desktop | `≥ 1025px` | Full two-column hero, side-by-side zoom preview |
| 🖥️ Wide | `≥ 1240px` | Max-width container at 1240px centered |

### Mobile-Specific Behaviors
- Hero carousel moves below title area
- Thumbnail row shows only 5 thumbnails (6th hidden via CSS)
- Zoom feature disabled (pointer: fine detection)
- Manufacturing stepper becomes single-card with prev/next arrows
- Testimonials carousel becomes touch-swipeable
- Logo grid auto-scrolls every 2.5 seconds
- Sticky bar adapts to full-width vertical layout

---

## 🎨 Design System

### Color Palette

| Token | Hex | Usage |
|-------|-----|-------|
| `Primary Blue` | `#2B3990` / `#1C3080` | Buttons, active states, brand |
| `Dark BG` | `#111827` | Tech specs dark section |
| `Dark Text` | `#1A202C` | Headings, body text |
| `Medium Gray` | `#4A5568` | Nav links, secondary text |
| `Light Gray` | `#717171` | Subtitles, descriptions |
| `Border` | `#E5E7EB` | Card borders, dividers |
| `Tag Yellow` | `#FEF3C7` | Price tags, labels |
| `White` | `#FFFFFF` | Cards, backgrounds |

### Typography

All text uses **Urbanist** (headings) + **Inter** (body) from Google Fonts:

| Element | Font | Size | Weight |
|---------|------|------|--------|
| Page H1 (Hero) | Urbanist | 56px | 700 |
| Section Headings | Urbanist | 42–48px | 700 |
| Card Titles | Urbanist | 18–26px | 700 |
| Body / Descriptions | Inter | 14–18px | 400 |
| Nav Links | Urbanist | 16px | 600 |
| Buttons | Inter | 14–16px | 500–700 |

### Shadows

```css
--shadow-sm:   0 4px 20px rgba(0,0,0,0.03);
--shadow-md:   0 8px 30px rgba(0,0,0,0.04);
--shadow-lg:   0 12px 30px rgba(0,0,0,0.06);
--shadow-dark: 0 10px 40px rgba(0,0,0,0.3);
```

---

## ⚙️ Key Interactions

### 1. Sticky Header (Navbar)
```
Scroll DOWN → Navbar hides (slides up)
Scroll UP   → Navbar reappears (slides down)
At top (0px)→ Always visible
Menu open   → Always visible
Transition  → transform: translateY, 0.3s ease
```

### 2. Manufacturing Sticky Bar
```
Trigger     → IntersectionObserver on .manufacturing-section
Threshold   → 20% of section in viewport
On enter    → Bar slides down from below navbar (z-index: 900)
On leave    → Bar slides up and fades out
```

### 3. Image Carousel with Zoom
```
Trigger         → pointerenter / pointermove events
Zoom disabled   → touch devices (pointer: coarse) + viewport < 1024px
Lens size       → 140×140px square with blue border
Preview size    → 240×240px rounded panel
Preview position→ Right of hero container, 80px from top
Zoom level      → preview / lens = ~1.7× magnification
```

### 4. Manufacturing Process Stepper
```
Desktop → Click tabs to switch content
Mobile  → Use ← / → arrows for single-card view
Badge   → "Step 3/8: Cooling" updates dynamically
```

---

## 👨‍💻 Developer

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<div align="center">

### **Kinshuk Saxena**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=500&amp;size=18&amp;pause=1000&amp;color=2B3990&amp;center=true&amp;vCenter=true&amp;width=500&amp;lines=Frontend+Developer;HTML+%7C+CSS+%7C+JavaScript+Enthusiast;React+Native+%7C+Expo+Builder;Music+Lover+%F0%9F%8E%B5;Always+Learning+%F0%9F%9A%80" alt="Typing SVG" />

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-kinshukkush-181717?style=for-the-badge&amp;logo=github)](https://github.com/kinshukkush)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kinshuk--saxena-0077B5?style=for-the-badge&amp;logo=linkedin)](https://www.linkedin.com/in/kinshuk-saxena-/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Website-2B3990?style=for-the-badge&amp;logo=google-chrome&amp;logoColor=white)](https://portfolio-frontend-mu-snowy.vercel.app/)
[![Email](https://img.shields.io/badge/Email-kinshuksaxena3%40gmail.com-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white)](mailto:kinshuksaxena3@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B91%209057538521-25D366?style=for-the-badge&amp;logo=whatsapp&amp;logoColor=white)](tel:+919057538521)

<br/>

**Made with ❤️ and 🔵 by Kinshuk Saxena**

⭐ **Star this repo if you found it helpful!** ⭐

<a href="https://github.com/kinshukkush">
  <img src="https://img.shields.io/github/followers/kinshukkush?style=social" alt="GitHub Followers"/>
</a>

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=2,4,12,20&amp;height=120&amp;section=footer" width="100%"/>
</div>
