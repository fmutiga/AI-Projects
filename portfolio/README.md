# Portfolio – Enterprise Architect Banner

Professional interactive portfolio banner showcasing enterprise architecture expertise.

## 🎨 Features

- **Animated Starfield** – 120 twinkling stars with dynamic opacity and scale animations
- **Modern Design** – Dark theme with gold (#f0b429) and blue (#3a8fff) accent colors
- **Responsive Typography** – Barlow Condensed and Barlow font families
- **Skill Ribbons** – Angled clip-path design with hover effects
- **Decorative Elements** – Hexagonal SVG patterns, grid lines, radial glow effects
- **Gradient Accents** – Subtle blue gradients with gold underlay

## 🎯 Key Sections

### Header
- **Name:** Faith K. Mutiga (top-left, prominent)
- **Title:** Enterprise Architect
- **Tagline:** "Aligning Business Strategy with Technology Execution"

### Core Competencies
Tagged expertise areas:
- Digital Transformation
- Banking & Fintech
- Enterprise IT Solutions
- Data-Driven Decisions

### Skill Areas
1. 🎯 IT Strategy
2. 📊 Solution Architecture
3. 🔗 API & Integration
4. 🤖 Data & AI Strategy
5. 🔒 Cloud Adoption

## 🎨 Design Specifications

| Property | Value |
|----------|-------|
| **Dimensions** | 1440px × 340px |
| **Primary Color** | #020b1e (dark navy) |
| **Accent Gold** | #f0b429 |
| **Accent Blue** | #3a8fff |
| **Text Color** | rgba(210,230,255,0.9) |
| **Font Stack** | Barlow, Barlow Condensed, sans-serif |

## 🚀 Deployment Options

### Local View
```bash
# Open directly in browser
open portfolio/index.html
```

### GitHub Pages (Recommended)
1. Go to **Settings → Pages**
2. Select **Deploy from a branch**
3. Choose **main** branch
4. Access: `https://fmutiga.github.io/AI-Projects/portfolio/`

### Live Server (Development)
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx http-server

# Then visit: http://localhost:8000/portfolio/
```

## 🔧 Customization

### Update Name
Edit line in `index.html`:
```html
<div class="name-topleft">Your Name Here</div>
```

### Change Title & Tagline
```html
<div class="title">Your Title</div>
<div class="tagline">
  <div class="tagline-dot"></div>
  Your tagline text
</div>
```

### Modify Tags
```html
<span class="tag">Your Tag</span>
```

### Update Skills
```html
<div class="skill-item">
  <div class="skill-icon">📚</div>
  <span class="skill-label">Your Skill</span>
</div>
```

### Change Colors
Update CSS variables:
- `.banner` – gradient background
- `.tag` – competency tag colors
- `.title` – title color (currently #f0b429)
- `--d` animation durations for star twinkle

## 📱 Browser Compatibility

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile browsers (responsive viewport meta tag included)

## 📄 Files

- `index.html` – Complete portfolio page (standalone)
- `README.md` – This documentation

---

**Last Updated:** May 22, 2026
