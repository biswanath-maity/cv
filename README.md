# Biswanath Maity - Professional CV & Interactive Portfolio Web App

An interactive, responsive portfolio and curriculum vitae web application built for **Biswanath Maity**, Senior Testing & Commissioning Engineer specializing in mission-critical Tier-III/IV Data Centers, Electrical Panels, and EPMS/BMS Systems.

---

## ⚡ Key Highlights
- **Interactive Portfolio Web App**: Built with vanilla HTML5, CSS3, and JavaScript with fast loading and zero external heavyweight dependencies.
- **Theme Switcher**: Instant Dark & Light mode toggle with persistent user preference storage.
- **ATS & Print-Ready PDF Resume**: Includes custom `@media print` rules. Simply click **"Print / PDF"** in the navigation bar or hero section to generate a formatted printable/exportable resume.
- **1-Click Contact Copy**: Click-to-copy phone and email with interactive toast feedback.
- **Interactive Skills Explorer**: Filter skills by category (Panels & Switchgear, Testing & QA, Automation & EPMS, Standards & Delivery).
- **Comprehensive Project Showcase**: Detailed breakdowns of hyperscale deployments for NTT GDC, Colt DCS, Nxtra, and Digital Edge DC.
- **ATS Markdown Resume**: A clean Markdown format CV included in [`resume.md`](./resume.md).

---

## 🚀 How to Run Locally

### Option 1: Double-Click
Open `index.html` directly in any modern browser (Chrome, Edge, Safari, Firefox).

### Option 2: Local HTTP Server (Python / Node)
Using Python 3:
```bash
python3 -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

Using Node.js `npx serve`:
```bash
npx serve .
```

---

## 📄 File Structure
- `index.html`: Semantic HTML5 markup, structured metadata, and content sections.
- `styles.css`: Complete CSS design system, responsive rules, animations, and `@media print` stylesheet.
- `app.js`: Interactive functionality (theme toggle, skill filter, copy feedback, scroll spy).
- `resume.md`: ATS-compliant plaintext / markdown resume.
