# Guillaume Rachet — Resume & Interactive Showcase

> **Lead Software Developer | Full-Stack Architect (Scala, Angular, TypeScript, PostgreSQL)**  
> Specialized in High-Performance Enterprise SaaS, Data Architecture & Regulated Systems (FDA 21 CFR Part 11 / GxP).

---

## 🌐 Live Website & Showcase

* **Live Resume & 10 Design Themes**: [https://guillaume-rachet.github.io/guillaume-rachet/](https://guillaume-rachet.github.io/guillaume-rachet/)
* **Portfolio**: [https://guillaume-rachet.github.io](https://guillaume-rachet.github.io)
* **Direct PDF Download**: [guillaume_rachet_resume.pdf](guillaume_rachet_resume.pdf)

---

## 🎨 10 Interactive Design Themes

This repository houses an interactive resume engine allowing instant toggling between 10 visual and structural designs for the exact same underlying content:

1. **Figma Classic**: 1:1 replica of the original two-column layout with circular photo and sidebar metadata.
2. **Modern Executive**: Clean slate/navy accents, linear dividers, high-contrast headings for scale-ups (Stripe, Linear).
3. **Minimalist ATS Clean**: Pure single-column format, optimized for 100% ATS score across enterprise recruiting systems (Workday, Taleo).
4. **Swiss Grid**: High-contrast, bold Plus Jakarta Sans typography, architectural grid alignment.
5. **Cupertino**: Apple-inspired clean UI, rounded tags, soft borders, modern sans-serif rhythm.
6. **Editorial Serif**: Warm background tone, elegant Newsreader serif headings, dignified senior presence.
7. **Dev Terminal**: Monospaced accents (JetBrains Mono), terminal prompt indicators (`$`), dev-centric aesthetic.
8. **Compact High-Density**: Engineered to guarantee strict 1-page fit even with heavy metric density.
9. **Nordic Slate**: Muted Scandinavian teal/slate accents, balanced whitespace.
10. **Bold Director / Leader**: Prominent header banner, executive title callout, metrics-forward presentation.

---

## 🛠️ How to Update with AI

1. Edit the clean semantic tags in `index.html`.
2. To compile directly to a vector 1-page PDF using Google Chrome on Mac:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless=new \
  --disable-gpu \
  --no-pdf-header-footer \
  --print-to-pdf="guillaume_rachet_resume.pdf" \
  "file://$(pwd)/index.html"
```

3. Commit and push:
```bash
git add .
git commit -m "Update resume content"
git push origin main
```
GitHub Actions will automatically re-deploy your site to GitHub Pages.
