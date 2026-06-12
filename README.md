<!-- prettier-ignore -->
# Animated React Landing (Vite + Tailwind + GSAP)

![Vite](https://img.shields.io/badge/Vite-5.4.9-brightgreen) ![React](https://img.shields.io/badge/React-18.x-blue) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-teal) ![GSAP](https://img.shields.io/badge/GSAP-3.x-purple) ![License](https://img.shields.io/badge/License-MIT-lightgrey)

A modern, animated React landing page built with Vite, Tailwind CSS and GSAP for smooth interactions and micro-animations.

---

## Demo

![Hero screenshot](images/Background.avif)

Open locally to see the full interactive animation.

---

## Highlights

- Smooth, performant animations with `gsap` and `@gsap/react`
- Built with `Vite` for fast HMR and quick development
- Styling with `Tailwind CSS` for a responsive, utility-first workflow
- Clean component structure for easy customization

---

## Quick Start

Install dependencies:

```bash
npm install
```

Run the dev server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## Project Structure (important files)

- `src/main.jsx` — App bootstrap
- `src/App.jsx` — Top-level app layout
- `src/Components/Home/Home.jsx` — Main landing section and animations
- `src/Components/Header/Header.jsx` — Navigation/header
- `src/Components/Footer/Footer.jsx` — Footer
- `src/Components/PageImages/Image.jsx` — Image components used in the hero
- `src/index.css` / `src/App.css` — Tailwind + custom styles

---

## Technologies

- React 18
- Vite
- Tailwind CSS
- GSAP (+ @gsap/react)

---

## Tips & Customization

- Replace images in the `images/` folder for your own branding.
- Tweak animation timelines in the `Home` and `PagesVideo` components using GSAP.
- Use Tailwind utility classes in components for rapid styling changes.

---

## Contributing

Contributions, issues and feature requests are welcome. For small fixes, open a PR and describe the change.

---

## License

This project is provided under the MIT License.
