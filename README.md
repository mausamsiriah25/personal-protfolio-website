# Mausam Siriah — Portfolio

A premium, futuristic single-page portfolio built with semantic HTML5, vanilla CSS3, and JavaScript — no frameworks, no build step. Dark glassmorphism UI with red neon accents, scroll-driven reveals, and an interactive 3D-style avatar card.

**Live preview:** add your deployed link here once hosted (e.g. GitHub Pages / Vercel / Netlify).

## Features

- Semantic HTML5 structure (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- Cinematic hero section with typewriter role animation, magnetic CTA buttons, and a parallax avatar card
- Scroll-triggered reveal animations via `IntersectionObserver`
- Animated scroll progress bar, glowing timeline, and tilting project cards
- Custom cursor, spotlight-follow effect, and ambient particles
- Fully responsive, with `prefers-reduced-motion` support
- Zero dependencies — just open `index.html` in a browser

## Tech Stack

- HTML5
- CSS3 (custom properties, keyframes, glassmorphism)
- Vanilla JavaScript (`requestAnimationFrame`, `IntersectionObserver`)

## Project Structure

```
.
├── index.html        # entire site — markup, styles, and scripts
├── assets/
│   └── avatar.png     # hero/about avatar image
└── README.md
```

## Getting Started

No build tools required.

```bash
git clone https://github.com/<mausamsiriah25>/<personal-portfolio-website>.git
cd <your-repo>
```

Then just open `index.html` in your browser, or serve it locally:

```bash
# Python
python3 -m http.server 5500

# Node
npx serve .
```

Visit `http://localhost:5500` (or whatever port your tool prints).

## Deploying

**GitHub Pages**

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set source to the `main` branch, root folder.
4. Your site will be live at `https://<your-username>.github.io/<your-repo>/`.

**Vercel / Netlify**
Just import the repo — no build command needed, output directory is the project root.

## Customizing

- **Content:** edit the text directly inside `index.html` (About, Skills, Projects, Journey, Achievements, Contact sections).
- **Avatar:** swap `assets/avatar.png` with your own image (same filename, or update the `src` path in the hero and about sections).
- **Colors:** tweak the CSS custom properties at the top of the `<style>` block (`--red`, `--bg-0`, etc.) to re-theme the site.

## Contact

- Email: siriahmausam@gmail.com
- LinkedIn: [linkedin.com/in/mausam-siriah](https://www.linkedin.com/in/mausam-siriah)
- GitHub: [github.com/mausamsiriah25](https://github.com/mausamsiriah25)

## License

Personal portfolio — feel free to use the structure/code as a learning reference, but please don't republish the content or avatar as your own.
